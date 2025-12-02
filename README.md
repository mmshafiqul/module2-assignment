# Module 2 Assignment Project

This project demonstrates the essential steps of using Git and GitHub, including repository setup, branching, pushing changes, and creating pull requests.
The following instructions outline the complete workflow used in this assignment.

Additional notes for feature-update branch.


## 1. Set Up a Local Git Repository
a. Create a new project folder
mkdir module2-assignment
cd module2-assignment

b. Initialize Git
git init

c. Create README.md
echo "# Module 2 Assignment Project" > README.md
edit it manually with a short project description.

d. Stage and commit
git add README.md
git commit -m "Initial commit: Added README with project description"

## 2. Create & Connect to a GitHub Repository
a. On GitHub
Create a New Repository
Name it: module2-assignment

b. Add remote and push
git branch -M main
git remote add origin git@github.com:mmshafiqul/module2-assignment.git
git push -u origin main

## 3. Create and Work on a New Branch
a. Create branch
git branch feature-update

b. Switch to the branch
git switch feature-update

c. Make changes
create a new file:
echo "Some useful notes." > notes.txt

d. Stage and commit
git add .
git commit -m "Added notes and updated README in feature-update branch"

## 4. Push the Branch & Create a Pull Request
a. Push the new branch
git push origin feature-update

b. Create a Pull Request on GitHub
Click Compare & pull request
Description:
Added additional notes and updated README.md in the feature-update branch.
Submit the Pull Request

## 5. Merge & Update Local Repository
a. Merge the PR on GitHub
Click Merge pull request
Confirm the merge

b. Update your local main branch
Switch to main:
git switch main

Pull the latest changes:
git pull


