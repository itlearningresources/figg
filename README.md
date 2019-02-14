

figg - a command line java development environment


Usage:         figg [-i] [-p] [-l] [-h]
               -i [<project-name>/]<class-name>        - enters interactive mode
               -p <project-name>                       - select project (project folder)
               -l                                      - list project folder
               -h                                      - display usage

Typical uses:  figg                                    - enters interactive mode (project == . and class-name == Main>
               figg -i <class-name>                    - enters interactive mode (project == . and class-name == <class-name>
               figg -i <project-name>/<class-name>     - enters interactive mode (project == <project-name> & class-name == <class-name>
               figg -p <project-name> -i <class-name>  - enters interactive mode (project == <project-name> & class-name == <class-name>


Interactive mode commands
               f <class-name>    - change the current class
               n <class-name>    - create new file <project-name>/src/<class-name>.java
               p <project-name>  - change the current project
               np <project-name> - new project (project folder with sub folders)
               e                 - edit (vim) <project-name>/src/<class-name>.java
               cat               - cat <project-name>/src/<class-name>.java
               reset             - deletes all class for the current project
               ls                - ls <project-name>/src
               c                 - compile <project-name>/src/<class-name>.java
               r                 - run <project-name>/classes/<class-name>.class
               R                 - run <project-name>/classes/<class-name>.class in split window
               j                 - generate and display javadoc <project-name>/classes/<class-name>.java


               q                 - quit
               h                 - help

Project directory organization
          <FIGGPROJECTSHOME>
          |--/<PROJECT>
             |--/src
                |--/<SourceFile>.java
             |--/classes
             |--/lib
             |--/doc
             |--/tmp

