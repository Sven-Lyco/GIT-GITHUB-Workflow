# Workflow for new projects
## FIRST GIT WORKLOW

- `cd <fodlername>` :  Navigate to where you want to make a new folder
- `take <foldername>` : create a new folder and navigate in it (take is a combi of "mkdir" and "cd")
- `mkdir <foldername>`: create new folders you need  
- `touch <filename>` : create new files you need
- `touch README.md`: create a README.md to describe your project
- `git init` : initiate git in your first created folder, when all files and folders are created
- `touch .gitignore` : create a .gitignore file
- `ls -la` : look for hidden files, you dont want to uplaod to Giit / Github
- `echo '.DS_Store' >> .gitignore`: write filenames in `.gitignore`
- `git add .` : Add everything to the Stage
- `git commit -m "Initial commit"` : Initial commit 

## FIRST GITHUB-WORKFLOW

- Add Reporsitory on GITHUB
	- reporsitory-name = local-folder-name
	- Next Page: Quicksetup
	- choose SSH
	- copy and paste link for push in Terminal: `git remote add origin git@github.com:USERNAME/REPORSITORY.git`
		- Enter

## SECOND GIT WORKLOW
- `git push`: push the local reporsitory to remote
	- you will get a message like this: `git push --set-upstream origin main`
	- copy, paste, enter

- Now check if the repository is on Github, by refreshing the page of the repository

- `git branch readme` : edit README.md and create a new branch
- `git branch` : # check branch
- `git switch readme` : switch to readme-branch
- `ls -la` : check if your README.md is here
- `code README.md` : Open and Edit your README.md in VS Code (remember this language is Markdown)
	- save your README.md
- `git status`: check changes
- `git add README.md`: add README.md to Stage
- `git commit -m "Edit README.md"` : commit README.md
- `git push` : push to Github

## SECOND GITHUB-WORKFLOW
- go in to the repository 
	- compare & pull request
	-	leave a comment and create pull request
-  **IF** your Code was reviewed and is okay, than Merge the pull request
	- confirm merge
	- delete branch

## SECOND GIT WORKLOW
- `git switch main` : switch to main-branch
- `git pull` : pull your Github-Repository with your local
- `git branch` : check your branches
- `git branch -d readme` : delete feature branch
- `git branch` : Check branch again
