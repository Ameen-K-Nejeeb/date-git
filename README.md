🚀 Git & GitHub Essentials
A comprehensive cheat sheet for managing local repositories and collaborating on remote platforms like GitHub and GitLab.

🛠 Basic Workflow
The core commands to initialize and track your progress.

1. git init — Initialize a new local Git repository.

2. git add <file> — Stage a specific file.

3. git add . or git add --all — Stage all changes in the directory.

4. git commit -m "message" — Snapshot your changes with a descriptive message.

5. git status — View the state of your working directory and staging area.

6. git log — View the commit history for the current branch.

7.git log --all — View history for all branches.

🔒 Security Note: Git uses Checksums (SHA-1 hashes) to ensure data integrity. This prevents hackers or errors from altering your content, logs, or commits without detection.


🌿 Branching & Merging
Manage different features without breaking the main code.

Command,Description
git branch <name>,Create a new feature branch.
git checkout <name>,Switch to the specified branch.
git merge <name>,Join history from a feature branch into the current one.
git diff,"Compare changes between files, commits, or branches."
git stash,Temporarily shelves (hides) changes so you can work on something else.

💡 Merge Types:
1. Fast-Forward: The branch pointer just moves forward (no new commit).

2. Recursive: Combines two branches with a new "merge commit."

3. Conflict: Happens when changes overlap; requires manual fixing.


🌐 Remote Operations (GitHub/GitLab)
- Connect your local work to the cloud.

- Connect: git remote add origin <link>

- Upload: git push origin master

- List Remotes: git remote (Add -v to see the fetch/push URLs).


🤝 Open Source Collaboration
1. When working on open-source projects, use this workflow to stay updated:

2. Pull Updates: git pull origin (This is essentially fetch + merge).
3. 

4. Stay Current: git merge master (Bring master changes into your feature branch).

5. Finalize: git commit -m "master merged to feature"

5.Submit: git push origin feature


-> Gist = gist.github.com

=> Tool,Role,What it does for you 

   1.Git     = The History,Records every change you make on your laptop.
  
   2.Gist    = The Note,"Stores that one ""perfect"" SQL query you want to reuse."
  
   3.GitHub  = The Cloud,Keeps your code safe and allows others to see it.
  
   4.Actions = The Robot,Automatically moves your code from GitHub to AWS.
