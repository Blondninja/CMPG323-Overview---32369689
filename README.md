# CMPG323-Overview---32369689

I have created 1 repository for this project in this Repo we have split it into 5 different branches for each specific individual project for eg. Project 2 will contain all the neccessary files for that project, we will then Push all the branches into the main branch where all the projects can be found.

Below is a Text diagram explaining the project and repo context and how they intergrate.

CMPG323-Overview Repo--->Main Branch--->Project 1--->Project 2--->Project 3--->Project 4--->Project 5
Above in the text diagram we have shown you that from the Repo we have branched 5 different projects from the main branch from the same repository. They are intergrated in such a way that Project 1 will not have an influence on other branches for example. Work that was done in project 1 will not affect project 2-5 and vice versa the only affect the branches will have is on the main branch when it is pushed or pulled.

explaining the branching strategy to be used within each project:

All projects are branched from 1 repository meaning that Project 1/Branch will not have an influence on other branches for example. Work that was done in project 1 will not affect project 2-5 and vice versa the only affect the branches will have is on the main branch when it is pushed or pulled. The branches are specifically set up in a way so that each project can be individually worked on, unless if they specify that we have to create an new repository for each project.

explain the use of a .gitignore file

gitnore is a file that tells the GIT to ignore a  project , because they are certain parts  in the project that you dont want it to be publish to your repository it could be credential files that you dont want them to be access by others  its not secure.
.gitignore tells git which files (or patterns) it should ignore. It's usually used to avoid committing transient files from your working directory that aren't useful to other collaborators, such as compilation products, temporary files IDEs create, etc.


explain the  storage of credentials and sensitive information:

 you can use the git store to store your passwords
 you can use the git store from the data being leaked 
