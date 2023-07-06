1. Clone down the main branch to your local machine (there are other alternatives like cloud, codespaces, codesanbox, etc we do not care where).

Open the terminal or command-line interface on your computer.

Navigate to the directory where you want to clone the repository. For example, if you want to clone the repository into a directory named "my-project", you can use the following command:
-cd my-project

```bash
git clone https://github.com/Ibadan-Techies/badtechies.git
cd badtechies
// see the package.json for how to run the code
```
Run this command to install all dependencies:
-npm install
Run this command to run on your local environment:
-npm run dev
1. Create a branch with your name followed by what you are implementing.
   - use descriptive text like 'bug' or 'feature' in the branch name. For example sekx-bug-XXXx.
Run the following command on your terminal to add changes
-git status 
-git add . (to add new changes)
-git status (to confirm if changes have been added)
2. Make commits to your branch (preferably on every successful working code completion).
   - again use a descriptive text describing what you've done.
Run the following command on your terminal to commit
-git commit -m "your text"
3. When you've finished with your fix or feature, bug, or whatever:
   ```bash
     git pull --rebase origin main
   ```
   - fix any merge conflicts before pushing to origin
4. Your pull request will be reviewed by another maintainer. The point of code reviews is to help keep the codebase clean and of high quality and, equally as important, to help you grow as a programmer. If your code reviewer requests you make a change you don't understand, ask them why.
   - Fix any issues raised by your code reviewer, and push your fixes as a single new commit.
   - Once the pull request has been reviewed, it will be merged by another member of the team. Do not merge your commits 👿.
