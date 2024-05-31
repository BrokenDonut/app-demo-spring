Windows PowerShell                                                          
Copyright (C) Microsoft Corporation. Todos los derechos reservados.         
                                                                            
Prueba la nueva tecnología PowerShell multiplataforma https://aka.ms/pscore6

PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git init
Reinitialized existing Git repository in C:/Users/IDAT/Documents/DESARROLLO AVANZADO APLICACIONES 2/app-demo-sprint/.git/
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git add .
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git commit -m "nueva contribucion"
[master (root-commit) 06ab317] nueva contribucion                                                               
 10 files changed, 552 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 mvnw
 create mode 100644 mvnw.cmd
 create mode 100644 src/main/java/pe/edu/idat/app_demo_sprint/controller/HomeController.java
 create mode 100644 src/main/resources/application.properties
 create mode 100644 src/test/java/pe/edu/idat/app_demo_sprint/AppDemoSprintApplicationTests.java
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git branch
* master
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> ^C
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git remote add origin https://github.com/BrokenDonut/app-demo-spring.git
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/BrokenDonut/app-demo-spring.git'
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git push -u origin master
info: please complete authentication in your browser...
Enumerating objects: 30, done.
Writing objects: 100% (30/30), 8.86 KiB | 2.21 MiB/s, done.
Total 30 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/BrokenDonut/app-demo-spring.git
branch 'master' set up to track 'origin/master'.
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git config user.name "BrokenDonut"
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git config user.email "ronaldochulluncuy@gmail.com"
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git remotec set-url origin https://github.com/BrokenDonut/app-demo-spring.git
The most similar command is
        remote
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git remotec set-url origin https://github.com/BrokenDonut/app-demo-spring.git
git: 'remotec' is not a git command. See 'git --help'.

The most similar command is
        remote
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git remote set-url origin https://BrokenDonut@github.com/BrokenDonut/app-demo-spring.git
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint> git push -u origin master
branch 'master' set up to track 'origin/master'.
Everything up-to-date
PS C:\Users\IDAT\Documents\DESARROLLO AVANZADO APLICACIONES 2\app-demo-sprint>
