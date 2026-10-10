# Lab 4 — Git & GitHub

## Question 1
The `--global` option saves my name and email in Git's global configuration, applying to all repositories for my user account. Without it, Git uses the local repository configuration when set inside a repository.

## Question 2
The `ls -a` command displays hidden files and folders, including `.git`. The `.git` directory stores repository data such as configuration, objects, references, and commit history.

## Question 3
The number of untracked files depends on the contents of my project. I should record the number shown by `git status` before staging files.

## Question 4
The `.gitignore` file tells Git to ignore matching files, such as `.venv/`, `__pycache__/`, `*.pyc`, and `.DS_Store`, so they are not accidentally added to the repository.

## Question 5
The `.gitignore` file should be committed because it contains project-wide rules that other contributors can reuse.

## Question 6
After running `git add README.md`, the README moves from the untracked files section to the staging area, shown under "Changes to be committed".

## Question 7
The commit command saves the staged changes in Git history. The terminal displays a commit hash and a summary of the files changed.

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
