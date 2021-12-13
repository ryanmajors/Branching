## Git Cheat Sheet

Added in main branch.
Reference for using Git in team projects.
Summary of Git Commands
### Basic Commands

* `git init` - Initialize local Git repository
* `git add .` - Add all files in and under current directory to index, staging
them for commit
* `git commit -m "Message"` - commit changes to local repo with commit message
"Message"

### Information Commands
* `git status` - Display current status of local working directory/repository
* `git log` - List commit history
* `git log -- oneline` - List commit history, compact format
* `git config -l` - List local Git configuration settings

### Branching Commands
* `git branch` - List local git branches
* `git branch newBranch` - Create local branch `newBranch`
* `git checkout newBranch` - Check out local branch `newBranch`
* `git branch -M otherBranch` - Rename current branch to `otherBranch`

### Remote Commands
* `git remote add origin remoteUrl` - Add alias "origin" for remote repository
Url "remoteUrl"
* `git push origin main` - Push locally-committed changes to `main` branch on
remote repository
* `git push -u origin main` - Same, setting "origin main" as default for
subsequent `git push`
