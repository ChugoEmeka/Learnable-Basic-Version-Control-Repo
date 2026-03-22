# Learnable-Basic-Version-Control-Repo
This repo is for practicing basic version control.

# Basic Version Control -

## Explain version control:
Version control is a system that helps developers track changes in their code over time. It allows you to go back to previous versions, collaborate with others, and manage different versions of a project efficiently.

## Explain difference between git and github:
Git is a version control system - GitHub is a cloud platform.
Git works locally on your machine - Github works online.
Git tracks changes in code - Github hosts and manages repositories.

## List 3 other github alternatives:
1. GitLab  
2. Bitbucket  
3. SourceForge  

## Explain the difference between git fetch and git pull:
- ***git fetch***: Downloads changes from a remote repository but does NOT merge them into your current branch.
- ***git pull***: Downloads changes AND automatically merges them into your current branch.

## Explain in simple terms git rebase and the command for it:
Git rebase is used to move or combine a sequence of commits to a new base commit. It helps to keep a clean project history.
### Command:
```bash
git rebase main .
```

## Explain in simple terms git cherry-pick and the command for it:
Git cherry-pick allows you to pick a specific commit from one branch and apply it to another branch.
### Command:
git cherry-pick <commit-hash>