# Upload-Folder-to-GitHub
This repository will tell you how to upload multiple Folders or a Project to GitHub repository.

---

## Follow these steps to upload multiple folder or a project  to  GitHub repository:

#### Note Download Git Bash First. Ignore if already Downloaded.

[Git Bash](https://git-scm.com/downloads)

1. Open Git Bash CLI.
2. Navigate to the desired Folder or Project.
    ```bash
    cd /path/to/your/project
    ```
3. Initialize a Git repository in your project directory:
    ```bash
    git init
    ```
4. Create a new file called LICENSE in your project directory, and copy the text of the desired License into this file. You can find the License text on internet. ( Optional Step. )
    ```bash
    nano LICENSE
    ```
Paste the text inside and save it by pressing Ctrl+x >>> then  y >>> then  Enter.

5. Add all your project files to the Git repository:
   - For adding all files at once use.
        ```bash
        git add .
        ```
    - For adding one file at a time use.
       ```bash
        git add <file_name>
        ```
7. Commit your files to the repository:
    ```bash
    git commit -m "Your Commit"
    ```

8. Create a new repository on GitHub. Make sure to not initialize it with a README, .gitignore, or License. This is because you are pushing an existing repository.

9. Link the local repository to the remote repository:
    ```bash
    git remote add origin https://github.com/username/new-repo.git
    ```
    or
    ```bash
    git remote add origin git@github.com:username/new-repo.git
    ```
   
Replace https://github.com/username/new-repo.git with the URL of your newly created GitHub repository.

9. Rename your current branch to master:
    ```bash
    git branch -m main master
    ```
10. Push your local repository to GitHub:
    ```bash
    git push -u origin master
    ```
    
---

## Git Cheat Sheet

[Have a look](https://github.com/MohitPimoli/Upload-Folders-to-GitHub/blob/main/Git%20and%20Git%20Hub.pdf)
