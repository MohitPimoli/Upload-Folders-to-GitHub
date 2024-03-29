# Upload-Folder-to-GitHub
This repository will tell you how to upload multiple Folders or a Project to GitHub Repository.


# How to Upload a Folder to a GitHub Repository

# Follow these steps to upload a folder to a GitHub repository:

# Note Download Git Bash for Better results.


1. Initialize a Git repository in your project directory:
'''bash
cd /path/to/your/project
git init
'''

2. Create a new file called LICENSE in your project directory, and copy the text of the MIT License into this file. You can find the MIT License text here.

3. Add all your project files to the Git repository:
\`\`\`bash
git add .
\`\`\`

4. Commit your files to the repository:
\`\`\`bash
git commit -m "Initial commit"
\`\`\`

5. Create a new repository on GitHub. Make sure to not initialize it with a README, .gitignore, or License. This is because you are pushing an existing repository.

6. Link the local repository to the remote repository:
\`\`\`bash
git remote add origin https://github.com/username/new-repo.git
\`\`\`
Replace https://github.com/username/new-repo.git with the URL of your newly created GitHub repository.

7. Rename your current branch to master:
\`\`\`bash
git branch -m main master
\`\`\`

8. Push your local repository to GitHub:
\`\`\`bash
git push -u origin master
\`\`\`
