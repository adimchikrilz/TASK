# ASSIGNMENT OF GIT AND VERSION CONTROL
1. **Explain Version Control**
   -
   
   Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time.hey are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.
   Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.
2. **Explain difference between git and github**
   - 

   Git is a popular version control system. it is used for:
   - Tracking code changes
   - Tracking who made the changes
   - Coding collaborations

   while Github is a code hosting platform for version control and collaboration. it lets you and others work together on projects from anywhere. 
3. **List 3 other Github alternatives**
   -
    - OneDev
    - BitBucket
    - Gogs
4. **Explain the difference between 'git fetch' and 'git pull'**
   -
   The diffference is that you use **Git fetch** when you want to download updates without affecting your current work environment, allowing for a more controlled approach to integrating changes. The command retrieves new data from a remote repository, including branches and tags, and updates the local remote-tracking branches. However, it does not change your working directory or merge any changes into your current branch. This allows you to review your changes before integrating/commiting them into your work. while we use **Git pull** for a quicker method to update your local branch with remote changes, keeping in mind that this may lead to merge conflicts if there are discrepancies between branches.This command is essentially a combination of git fetch followed by git merge. It fetches the latest changes from the remote repository and automatically merges them into your current branch. This means that after a git pull, your working directory is updated with the latest changes from the remote branch.
5. **Explain in simple terms git rebase and the command for it**
   -
   Git rebase is a command used in Git to change the base of your current branch to a different commit. In simpler terms, it allows you to take the changes you made in your branch and apply them on top of another branch, effectively rewriting the commit history. and the command for it is: `*git rebase <base_branch>*`
6. **Explain in simple terms git cherry-pick and the command for it**
   -

   Git cherry-pick is a command that allows you to select a specific commit from one branch and apply it to another branch. This is useful when you want to incorporate changes from a commit without merging the entire branch. and the command for it is: `git cherry-pick <commit-hash>` but before you write the command you have to first of all switch to the target branch (the branch you wish to cherrypick from) and to do that you have to type in: `git checkout <target-branch>`

