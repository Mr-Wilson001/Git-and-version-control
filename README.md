# Git-and-version-control

# OGUGOR CHIGOZIE (BE)

# ANSWERS 


## 1. Version control
version control is the process of tracking and managing changes to documents or code over time.

## 2. Differences between Git and Github
| s/n | Git  | Github |
|:-|:-|:-|
| 1.|Git is a software| github is a service|
| 2.| git is a version control system that lets you track and manage source code history.| github is a cloud-based hosting services that lets you manage git repositories. |
| 3.| git is a command-line tool. | github is a graphical user interface. |
| 4.| git is installed locally on the system.| github is hosted on the web. |
| 5.| git has no user management feature.| github has a built-in user management feature. |

## 3. Other github alternatives
* Gitlab
* Bitbucket
* Azure DevOps

## 4. Difference between 'git pull' and 'git fetch'
| Git pull | Git fetch|
|:-|:-|
|the git pull copies changes from a remote repository directly into your working directory. (eg. git pull = git fetch + merge) | Git fetch only copies changes into your local git repository.|

## 5. Git rebase
Git rebase basically merges commits from one branch to another. it is like a linear process of merging.

command : git rebase (target branch)

## 6. Cherry-pick
Cherry-pick is act of picking or choosing a commit from one branch and applying it to another branch.
for instance where you have more than one commit in a branch, Cherry-pick helps you to pick a paticular commit and apply it to another branch instead of selecting or merging the whole branch.

command : git cherry-pick (unique id of the commit). eg. git cherry-pick 8245f26
