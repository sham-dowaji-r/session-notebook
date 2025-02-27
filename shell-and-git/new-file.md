1. Go inside your project folder using the terminal.
cd path/to/your/project

2. Initialize a new Git repository in the project folder.
git init

3. Create a new file to store session notes.
touch shell-and-git/session1.md

4. Check the status of the repository to see untracked files.
git status

5. Stage the new file to be tracked by Git.
git add shell-and-git/session1.md
# Or to add all files at once:
git add .

6. Commit the changes with a meaningful message.
git commit -m "Add session1.md with initial notes"

7. Create a new remote repository on GitHub.
# Go to GitHub and create a new repository (don't add a README or license).

8. Link the local repository to the remote GitHub repository.
git remote add origin git@github.com:your-username/repository-name.git

9. Push the local commits to GitHub.
git push -u origin main

10. Verify the changes on GitHub by checking the repository page.
# Visit your repository page on GitHub.

11. Continue working and commit new changes frequently.
git add .
git commit -m "Update session notes"
git push origin main
