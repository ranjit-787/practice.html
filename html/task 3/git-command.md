Git commands 
 ## After creating new projects 

 ***Note: All content with big brackets [] should be replace.***
 
  1. Git initialization  
        ```
     git init 
        ```

  2. Adding files and folders to git for tracking.
        ```
       Note: for specific files  
       git add [file_name]
       eg: git add index.html 
        ```
        ```
        --> To add all files and folders:   
       git add .
        ```

   3. Git version save or commit 
        ```
        git commit -m [your_commit-message]
        eg: git commit -m "auth feature done"
        ```

4. Change main branch [optional step]  
        ````
        git branch -M [your_new_branch_name]
        ````

5. Add remote url (link the remote repository url)
    ````
    git remote add origin [remote_repo_url]
    ````
6. Push the commited coed to the remote repo
    ```
    At initial (-u: upstream)
    git push -u origin [your_branch_name]
    After first push: git push
    ```
- https://[PAT]@github.com/[github_username]/[projectname]
