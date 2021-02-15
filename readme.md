# Steps to upload a local repo to a remote repo:

1. Navigate to desired directory in command line interface.
2. Do a _git init <repo-name>_
3. Change directory (cd) into the newly created local repo.
4. Create new .gitignore and README.md files using touch command.
5. Then do a _git remote add origin https://github.com/pr4sh4nth/<repo-name>.git_
6. Do a _git add ._ to add all changes to staging environment.
7. Commit the changes with _git commit -m "<message>"_
8. Finally, push the changes from the local repo to the newly created remote repo by _git push -u origin master_
