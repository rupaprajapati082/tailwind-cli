🔹 Git User Setup

git config --global user.name "rupaprajapati082"
→ Sets your Git username globally.

git config --global user.email rupsprajapati823@gmail.com
→ Sets your Git email globally.

git config --list
→ Shows all Git configuration settings.

🔹 Remove Git User Details

git config --global --unset user.name
→ Deletes the global Git username.

git config --global --unset user.email
→ Deletes the global Git email.

🔹 Git Basic Commands

git add .
→ Adds all changed files to staging.

git commit -m "msg"
→ Saves changes with a message.

git push origin main
→ Sends code to the main branch on GitHub.

git push origin master
→ Sends code to the master branch on GitHub.

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
→ Allows running scripts on your system.

🔹 Tailwind CLI Install

npm install tailwindcss @tailwindcss/cli
→ Installs Tailwind CSS and CLI.

🔹 Node Modules Missing

npm i
→ Installs all project dependencies.

🔹 Run Project

npm run start
→ Runs the project.

🔹 Git Branch Commands

git branch
→ Shows all branches.

git branch branch_name
→ Creates a new branch.

git checkout branch_name
→ Switches to another branch.

🔹 New GitHub Repository Setup

echo "# tailwind-cli" >> README.md
→ Adds text to README file.

git init
→ Creates a new Git repository.

git add README.md
→ Stages README file.

git commit -m "first commit"
→ Saves the first commit.

git branch -M main
→ Renames branch to main.

git remote add origin URL
→ Connects local repo to GitHub.

git push -u origin main
→ Pushes code and sets default branch.