
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
         cat                        Cat &ltproject-name&gt/src/&ltclass-name&gt.java
         cc                         Compile &ltproject-name&gt/src/&ltclass-name&gt.java"
         c &ltclass-name&gt             Change the current class"
         d                          vim srcfile.java.lst and srcfile.java.java
         e                          edit (vim) &ltproject-name&gt/src/&ltclass-name&gt.java"
         eq                         Edit the QuickClass template
         .figg                      Edit ~/.figg file   
         g                          Compile/run/create listing for &ltproject-name&gt/classes/&ltclass-name&gt"
         gg                         Display last listing for &ltproject-name&gt/classes/&ltclass-name&gt
         ?                          Help                
         h                          Help                
         init                       Resets interactive mode (sets to Main/Main)
         j                          Generate and display javadoc &ltproject-name&gt/classes/&ltclass-name&gt.java
         l                          List project java files
         lsc                        list project class files
         ls                         Lists project classes
         lss                        List the src directory for &ltproject-name&gt
         lst                        List the templates directory
         n &ltclass-name&gt             Create new file &ltproject-name&gt/src/&ltclass-name&gt.java
         np &ltproject-name&gt          New project (project folder with sub folders)
         reset                      Delete all class for the current project
         rr                         Compile and Run srcfile.java
         r                          Run &ltproject-name&gt/classes/&ltclass-name&gt.class
         R                          Run &ltproject-name&gt/classes/&ltclass-name&gt.class in split window
         sa &ltclass-name&gt            Save as             
         tar                        tar all of $FIGGHOME into $FIGGHOME/archives
         tb                         Create QuickClass without using a template (blank QuickClass)
         t                          Create QuickClass using QuickClass template
         tmp                        Copy srcfile.java to /tmp/srcfile.java
         y                          Compile all project java files


</pre>
