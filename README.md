# demo_projects

Git Setup steps
===============
1) download and install git on PC.
2) generate SSH key for PC
- Open git bash. 
- follow instructions https://help.github.com/articles/generating-an-ssh-key/
3) Copy SSH key to git a/c.

Git repository access
=====================
- git clone <repo. path>
- git checkout <branch name or tag name>
- git fetch // update local info about repository for latest changes
- gitk : to view the repo. in UI 
- git gui > repository > Visualize all branch history to see all branches info./tree
- check in method:
  - git add . -A
  - git commit -m "message"  // till here everything is local only
  - git push origin <local_branch_name>:<remote_branch_name>

simple example:- 
- git clone https://github.com/embeddedsystem101/demo_projects.git
- git checkout review -b review_local   // optional -b to checkout in any local branch
- after modifications
- git add . -A
- git commit -m "demo push"
- git push origin review_local:review
