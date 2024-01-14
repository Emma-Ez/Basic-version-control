# Basic-version-control

## **Version Control**

Version control is a system that track changes to codebase over time, thereby allowing developers to:
- Revert back to previous version/versions easily.
- Collaborate effectively without overwriting each others changes.
- Track progress and changes.
- Explore different ideas safely.

## **The difference between Git and Github**

While **Git** is a version control system that run locally on computer to track changes to codes and equally manage different versions of files, **Github** on the other hand is a cloud-based plartform for hosting Git repositories. 

## **3 other Github alternative**

1. Gitlab
2. Bitbucket
3. AWS CodeCommit

## **The difference between git fetch and git pull**

Both commands are used to retrieve changes from remote repository. However, ***git fetch*** does not automatically merge the changes into the current branch. ***git pull*** combines *git merge* and *git fetch* into a single command.

## **Git rebase**

This command is used to streamline a commit history by moving a sequence of commits into a new base commit.
- **Command:** *git rebase <base branch>*

## **Git Cherry-pick**
 Git cherry-pick is used to pluck specific cimmits from one branch and apply them to another  branch, just like picking cherries from a cherry tree'
 - **Command:** *git cherry-pick <commit-hash>*