## FIGG - A command line java development environment
<pre>
<code>


figg - a command line java development environment


Usage:         figg [-i] [-p] [-l] [-h]
               - &gtproject-name
               -i [<gtproject-name>/]<gtclass-name>        - enters interactive mode (i-mode)
               -p <gtproject-name>                       - select project (project folder)
               -l                                      - list project folder
               -h                                      - display usage

Typical uses:  figg                                    - enters i-mode (project == . and class-name == Main>
               figg -i <gtclass-name>                    - enters i-mode (project == . and class-name == <gtclass-name>
               figg -i <gtproject-name>/<gtclass-name>     - enters i-mode (project == <gtproject-name> & class-name == <gtclass-name>
               figg -p <gtproject-name> -i <gtclass-name>  - enters i-mode (project == <gtproject-name> & class-name == <gtclass-name>


Interactive mode commands
               f <gtclass-name>    - change the current class
               n <gtclass-name>    - create new file <gtproject-name>/src/<gtclass-name>.java
               p <gtproject-name>  - change the current project
               np <gtproject-name> - new project (project folder with sub folders)
               e                 - edit (vim) <gtproject-name>/src/<gtclass-name>.java
               cat               - cat <gtproject-name>/src/<gtclass-name>.java
               reset             - deletes all class for the current project
               ls                - ls <gtproject-name>/src
               c                 - compile <gtproject-name>/src/<gtclass-name>.java
               r                 - run <gtproject-name>/classes/<gtclass-name>.class
               R                 - run <gtproject-name>/classes/<gtclass-name>.class in split window
               j                 - generate and display javadoc <gtproject-name>/classes/<gtclass-name>.java


               q                 - quit
               h                 - help

Project directory organization
          <gtFIGGPROJECTSHOME>
          |--/<gtPROJECT>
             |--/src
                |--/<gtSourceFile>.java
             |--/classes
             |--/lib
             |--/doc
             |--/tmp

</code>
</pre>
