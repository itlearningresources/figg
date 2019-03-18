
## FIGG - A command line java development environment
#### written in Korn Shell and Vim
<pre>


figg - a command line java development environment


Usage:         figg [-i] [-p] [-l] [-h]
               -i [&ltproject-name&gt/]&ltclass-name&gt        - enters interactive mode (i-mode)
               -p &ltproject-name&gt                       - select project (project folder)
               -l                                      - list project folder
               -h                                      - display usage

Typical uses:  figg                                    - i-mode, project=., class-name == Main&gt
               figg -i &ltc-name&gt                        - i-mode, project=., class-name=&ltc-name&gt
               figg -i &ltp-name&gt/&ltc-name&gt               - i-mode, project=&ltp-name&gt, class-name=&ltc-name&gt
               figg -p &ltp-name&gt -i &ltc-name&gt            - i-mode, project=&ltp-name&gt, class-name=&ltc-name&gt


Interactive mode commands
               f &ltclass-name&gt    - change the current class
               n &ltclass-name&gt    - create new file &ltproject-name&gt/src/&ltclass-name&gt.java
               sa &ltclass-name&gt   - save as &ltproject-name&gt/src/&ltclass-name&gt.java
               p &ltproject-name&gt  - change the current project
               np &ltproject-name&gt - new project (project folder with sub folders)
               init              - resets interactive mode (sets to Main/Main)
               e                 - edit (vim) &ltproject-name&gt/src/&ltclass-name&gt.java
               cat               - cat &ltproject-name&gt/src/&ltclass-name&gt.java
               tmp               - write &ltclass-name&gt.java to /tmp
               t                 - create QuickClass using QuickClass template
               tb                - create QuickClass without using a template (blank QuickClass)
               eq                - edit the QuickClass template
               reset             - deletes all class for the current project
               ls                - lists classes in &ltproject-name&gt
               c                 - compile &ltproject-name&gt/src/&ltclass-name&gt.java
               r                 - run &ltproject-name&gt/classes/&ltclass-name&gt.class
               R                 - run &ltproject-name&gt/classes/&ltclass-name&gt.class in split window
               g                 - compile/runi/create listing for &ltproject-name&gt/classes/&ltclass-name&gt
               gg                - display last listing for  &ltproject-name&gt/classes/&ltclass-name&gt
               j                 - generate and display javadoc &ltproject-name&gt/classes/&ltclass-name&gt.java
               lss               - list the src directory for &ltproject-name&gt
               lst               - list the templates directory


               q                 - quit
               h                 - help

Project directory organization
          &ltFIGGPROJECTSHOME&gt
          |--/templates
          |--/&ltPROJECT&gt
             |--/src
                |--/&ltclass-name&gt.java
             |--/classes
             |--/lib
             |--/doc
             |--/lst
             |--/tmp

</pre>
