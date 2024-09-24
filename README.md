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
   git rm --cached`<file_name>
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
    git remote add origin https://github.com/alakeshthakuria/delete-this.git
    ````
 +  From the above command url `delete-this.git` is the repository created in github which is similar to local repository `delete-this`
12. How to check reomte repository added or not
    ````
    git remote -v
    ````
13. How to authenticate git local repository to remote repository that is github, so that we can push to or pull from github to our local respository.
    ````
    git remote set-url origin https://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@github.com/alakeshthakuria/delete-this.git
    ````
 +  From the above code `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` this is personal access token generated from github. 
