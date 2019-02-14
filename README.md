## FIGG - A command line java development environment
<pre>


figg - a command line java development environment


Usage:         figg [-i] [-p] [-l] [-h]
               - &gtproject-name
               -i [&ltproject-name&gt/]&ltclass-name&gt        - enters interactive mode (i-mode)
               -p &ltproject-name&gt                       - select project (project folder)
               -l                                      - list project folder
               -h                                      - display usage

Typical uses:  figg                                    - enters i-mode (project == . and class-name == Main&gt
               figg -i &ltclass-name&gt                    - enters i-mode (project == . and class-name == &ltclass-name&gt
               figg -i &ltproject-name&gt/&ltclass-name&gt     - enters i-mode (project == &ltproject-name&gt & class-name == &ltclass-name&gt
               figg -p &ltproject-name&gt -i &ltclass-name&gt  - enters i-mode (project == &ltproject-name&gt & class-name == &ltclass-name&gt


Interactive mode commands
               f &ltclass-name&gt    - change the current class
               n &ltclass-name&gt    - create new file &ltproject-name&gt/src/&ltclass-name&gt.java
               p &ltproject-name&gt  - change the current project
               np &ltproject-name&gt - new project (project folder with sub folders)
               e                 - edit (vim) &ltproject-name&gt/src/&ltclass-name&gt.java
               cat               - cat &ltproject-name&gt/src/&ltclass-name&gt.java
               reset             - deletes all class for the current project
               ls                - ls &ltproject-name&gt/src
               c                 - compile &ltproject-name&gt/src/&ltclass-name&gt.java
               r                 - run &ltproject-name&gt/classes/&ltclass-name&gt.class
               R                 - run &ltproject-name&gt/classes/&ltclass-name&gt.class in split window
               j                 - generate and display javadoc &ltproject-name&gt/classes/&ltclass-name&gt.java


               q                 - quit
               h                 - help

Project directory organization
          &ltFIGGPROJECTSHOME&gt
          |--/&ltPROJECT&gt
             |--/src
                |--/&ltSourceFile&gt.java
             |--/classes
             |--/lib
             |--/doc
             |--/tmp

</pre>
