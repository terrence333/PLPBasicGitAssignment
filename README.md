# PLPBasicGitAssignment
1.Task 1: Repository Setup

2.Create a GitHub Repository:
Log in to GitHub.
Click on the "New repository" button on the right side of the GitHub dashboard.
Name your repository PLPBasicGitAssignment.
Check the box to initialize the repository with a README file.
Click "Create repository".

3. Task 2: Local Setup
4. Create a Local Folder:

On your local machine, create a folder named PLPBasicGitAssignment.
Initialize Git in Local Folder:

Open your terminal (or command prompt).
5. Navigate to your local folder using cd:
bash
cd path/to/PLPBasicGitAssignment
6. Initialize a new Git repository:
bash
git init
7. Connect to GitHub:

8. Link your local repository to the GitHub repository:
bash
git remote add origin <repository-url>
Replace <repository-url> with the URL of your GitHub repository. You can find this URL on your GitHub repository page by clicking on the green "Code" button.
9. Task 3: Making Changes
10. Create a File:

Inside the local folder, create a new file named hello.txt.
Open hello.txt and add the message "Hello, Git!".
11. Save the file.

12. Stage the changes:
bash
git add hello.txt

13. Commit the changes:
bash
git commit -m "Add hello.txt with a greeting"

14. Task 4: Pushing to GitHub
Push to GitHub:
Push the committed changes to GitHub:
bash
git push -u origin main
16. Task 5: Verification
-Verify on GitHub:
Visit your repository on GitHub and check that the hello.txt file is present and that your commit message is visible.
