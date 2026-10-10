# Lab 4 — Git & GitHub

## Question 1
The `--global` option saves my name and email in Git's global configuration, applying to all repositories for my user account. Without it, Git uses the local repository configuration when set inside a repository.

## Question 2
The `ls -a` command displays hidden files and folders, including `.git`. The `.git` directory stores repository data such as configuration, objects, references, and commit history.

## Question 3: 
You saw three untracked entries: .gitignore, README.md, and lab4/. These appeared after creating your project files, not during the initial empty-repository check.

## Question 4: 
Explain that .gitignore excludes matching files and directories, especially .venv/, __pycache__/, and *.pyc. Your actual project had no .venv/ listed.

## Question 5
The `.gitignore` file should be committed because it contains project-wide rules that other contributors can reuse.

## Question 6
After running `git add README.md`, the README moves from the untracked files section to the staging area, shown under "Changes to be committed".

## Question 7
Your first commit reported three files changed, with 60 insertions. That was the output you recorded for commit 38dc755.

## Question 8
The first seven characters of a commit hash are a short version of its unique identifier, making it easier to refer to a commit.

## Question 9
The usual workflow is to edit files, inspect the changes, stage them with `git add`, and save them with `git commit`.

## Question 10
GitHub automatically displays `README.md` on the repository's front page, giving visitors an overview of the project.

## Question 11
The `gh auth login` command authenticates GitHub CLI with my GitHub account so I can perform supported GitHub operations from the terminal.

## Question 12
GitHub recognizes `README.md` and renders its Markdown content on the repository front page.

## Question 13
Pushing uploads local commits to the remote repository. It does not ordinarily change the existing local commit history.

## Question 14
A private GitHub repository is accessible only to its owner and users who have been granted access. A local repository does not automatically create a hosted GitHub repository.
