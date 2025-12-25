# Learning git

this repository has been created to record things that I learn and find out about, through practices and reading proGit book and other sources.

## Getting Started

#### what is git:
it is a distributed version control system where we keep track of our work and changes over time.

#### repository:
tracked files that are indicating our source code.

#### untracked:
first when we create a repository, all files are untracked and need to be staged.

#### staged/indexed:
is the previous step from commit, this is the testing area.

#

```bash 
git log
```
displays commit history of a git repo, showing details such as:
- commit hash
- author
- date
- commit message

git commands are divided into two main category:
- porcelain which are high level commands such as (git-add git-commit...).
- plumbing, such as (git-cat-file git-hash-object git-commit-tree...).

##### ! git creates blob object for files and tree object for trees.



