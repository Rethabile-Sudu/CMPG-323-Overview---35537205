A repository is an area where you can keep your code, files and each file's editing records.
Repositories can be public, internal or private and can also be accessed by several collaborators.
In this project I will use 5 repositories. All the repositories will be private so that they cannot be acessed by anyone else except the people I have granted admin permissions' for.


Branching Strategies to be used within each project:
A branch is a parallel version of your code that is stored inside the repository, but makes no diffrence main branch. Each repository has its  own default branch, and you can also add several other branches. Branches can be combined together using a pull request. There are 3 types of branches, feature branches, bug branches and hotfix branches. Feature branches are used when creating a new feature which could possibly have a longer lifespan than one deployment. Bug branches are created when there is a bug on the current site that needs to be fixed and combined into the next deoployment. Hotfix branches come from the need to make use of an unwanted state of live production version. A hotfix branch does not need to be pushed during an arranged deployment. I will be using feature branches in all of the projects that I will be creating.

GitIgnore
The .gitignore file in Github isused to notify git which files and directories to ignore when you make a change or a commit. This file is useful for stopping sensitive data, temporary files, and other files that are not related to the project from being included in the repository.

Storage of credentials and sensitive information
Storing credentials and sensitive information in github is not advised as it it can pose a huge security threat. Github is a public platform  and placing confidential information in your repository can make it accessible by unwanted users. Storing confidential information in github could breach the compliance regulations like GDPR and HIPAA.
If you plan on posting credentials or sensitive information make sure to use strong encryption,restrict access to sensitive data, use safe storage methods, check-up and audit access to sensitive data. 
