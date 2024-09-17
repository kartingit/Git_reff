# Git Commands For Referance

git init                          ===> initilization
git add. or git add "filename"    ===> To add files/contents to statging area
git status                        ===> To status
git commit -m "comment"           ===> To commit 

git restore filename              ===> If files modified that can be restored to privious state
git restore --staged filename     ===> If files "staged" that can be unstaged/restored to privious state
git rm --cached filename          ===> To unstage

git config -l                     ===> which comes handy 
git config user.name name
git config user.name name@somwhere.com

git log                           ===> To check logs of commits of repo 
git log --oneline                 ===> It will display logs in single line
git log --name-only               ===> It will display logs along with "files" on which changes has occured

git checkout -b name              ===> Create and switch to "name" branch
git checkout name                 ===> Switch to "name" branch
git branch                        ===> To list
git branch -a                     ===> To list branches of Local aswell Remote
git branch name                   ===> It will create "name" branch

git merge name                    ===> To merge name branch
-- Merge uses startigies to merge branch ex. fastforward / no fastforward 
-- lookout for merge conflicts

git remote add groot https://github.com/kartingit/Git_reff.git  
                                  ===> To add remote repo on local in the name of "groot"
git remote -v                     ===> To list remote repo 
git push groot main               ===> To push contents/commits to remote repo on main branch 
git clone https://github.com/kartingit/Git_reff.git  
                                  ===> To clone

// Pull request //                ===> This one can be done only on Portal [Remote/WebGUI] /To contribute/To merge
// fork //                        ===> [Remote/WebGUI] forking others repo 
 
// git pull = git fetch + git merge //

git pull https://github.com/kartingit/Git_reff.git
git fetch https://github.com/kartingit/Git_reff.git
git merge groot/main                    

git rebase name                  ===> Rebase onto the name branch /similar to merge but you dont see merge commit 
git rebase -i HEAD~4             ===> It will show the last 4 commits and provide various options for modifying them

git cherry-pick commit hash      ===> To pick desired commit from one branch to another


 
 
