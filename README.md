# Upload-Folder-to-GitHub
This repository will tell you how to upload multiple Folders or a Project to GitHub Repository.

# Follow these steps to upload a folder to a GitHub repository:

# Note Download Git Bash First. Ignore if already Downloaded.

Git Bash https://git-scm.com/downloads

1. Open Git Bash CLI.
2. Navigate to the Desigered Folder or project.
      '''bash
cd /path/to/your/project

'''
3. Initialize a Git repository in your project directory:
      '''bash
git init
'''

4. Create a new file called LICENSE in your project directory, and copy the text of the desired Licence into this file. You can find the License text on internet. ( Optional )
   '''bash nano LICENCE '''
Paste the text inside and save it by pressing '''bash Ctrl+x''' then  '''bash y''' then '''bash Enter'''.

5. Add all your project files to the Git repository:
   '''bash
git add .
  '''

6. Commit your files to the repository:
'''bash
git commit -m "Initial commit"
   '''

7. Create a new repository on GitHub. Make sure to not initialize it with a README, .gitignore, or License. This is because you are pushing an existing repository.

8. Link the local repository to the remote repository:
\`\`\`bash
git remote add origin https://github.com/username/new-repo.git
\`\`\`
Replace https://github.com/username/new-repo.git with the URL of your newly created GitHub repository.

9. Rename your current branch to master:
\`\`\`bash
git branch -m main master
\`\`\`

8. Push your local repository to GitHub:
\`\`\`bash
git push -u origin master
\`\`\`
