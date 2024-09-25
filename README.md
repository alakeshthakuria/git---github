# git & github

1. Initialize git in empty repository
   ````
   git init
   ````
2. Check git status
   ````
   git status
   ````
3. Stage untrack file
   ````
   git add <file_name>
   ````
4. To unstage staged file.
   ```
   git rm --cached <file_name>
   ````
5. To track staged file.
   ````
   git commit -m "your message"
   ````
6. Recover deleted file in git version control system
   ````
   git restore <file_name>
   ````
7. Check git branch
   ````
   git branch
   ````
8. Create new git branch
   ````
   git checkout -b <branch_name>
   ````
9. Switch branch in git
   ````
   git checkout <branch_name>
   ````
10. Some command left
11. Add git initiated repository in local system to github repository that is in remote.
    ````
    git remote add origin https://github.com/github_username/repository.git
    ````
12. How to check reomte repository added or not
    ````
    git remote -v
    ````
13. First we have to add remote repository or github repository to our local repository to pull or push  the code from remote to local or local to remote .
    ````
    git remote add origin https://github.com/github_username/repository.git
    ````
13. Next we have to authenticate git local repository to remote repository that is github, so that we can push to or pull from github to our local respository. 
    There are two ways to authenticate:
    + 1st option: This option works with personal access token which is generated from github:
    ````
    git remote set-url origin https://<Personal_access_token>@github.com/git_userame/repository.git
    ````
    + 2nd option: This is option is about SSH key, which is generated in local system, private key is in the system and provide the public key to github, after 
    that we can configure git to use SSH by the below command:
    ````
    git remote set-url origin git@github.com:github_username/repository.git
    ````
14. Push code from local respository that is git to remote repository that is github
    ````
    git push origin <branch_name>
    ````
15. Pull code from remote repository that is github to local repository that is git
    ````
    git pull origin <branch_name>
    ````
16. To check git commit history
    ````
    git log
       or 
    git log --oneline
    ````
17. How to fetch all the branches from remote repository to local repository
    ````
    git fetch
    ````
