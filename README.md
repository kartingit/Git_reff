## Git Commands For Referance

`git init                                     `   *`To initilization`*<br>
`git add . or git add filename                `   *`To add files/contents to statging area`* <br>
`git status                                   `   *`To check status`* <br>
`git commit -m "comment"                      `   *`To commit`* <br>
<br>
`git restore filename                         `   *`If files modified that can be restored to privious state`* <br>
`git restore --staged filename                `   *`If files "staged" that can be unstaged/restored to privious state`* <br> 
`git rm --cached filename                     `   *`To unstage`* <br>
<br>
`git config -l                                `   *`To check configuration`* <br> 
`git config user.name name`<br>
`git config user.name name(@)somwhere(.)com`<br>
<br>
`git log                                       `   *`To check logs of commits of repo`*<br>
`git log --oneline                             `   *`It will display logs in single line`* <br>
`git log --name-only                           `   *`It will display logs along with "files" on which changes has occured`* <br>
<br>
`git checkout -b name                          `   *`Create and switch to "name" branch`* <br>
`git checkout name                             `   *`Switch to "name" branch`*<br>
`git branch                                    `   *`To list branches`*<br>
`git branch -a                                 `   *`To list branches of Local as well as Remote`* <br>
`git branch name                               `   *`It will create "name" branch`*<br>
<br>
`git merge name                                `    *`To merge "name" branch`*<br>
*`Merge uses strategies to merge branch ex. fastforward / no fastforward`* <br> 
*`lookout for merge conflicts`* <br>
<br>
`git remote add groot https://github.com/kartingit/Git_reff.git `  *`To add remote repo on local in the name of "groot"`* <br>
`git remote -v                                                  `  *`To list remote repo`* <br> 
`git push groot main                                            `  *`To push contents/commits to remote repo on main branch`* <br>
`git clone https://github.com/kartingit/Git_reff.git <br>       `  *`To clone`* <br>
<br>
`// Pull request //                            `  *`This can be done only on Portal [Remote/WebGUI] /To contribute/ To merge`* <br>
`// fork //                                    `  *`[Remote/WebGUI] forking others repo`* <br>
<br>
`// git pull = git fetch + git merge //`<br>
<br>
`git pull https://github.com/kartingit/Git_reff.git` <br>
`git fetch https://github.com/kartingit/Git_reff.git` <br>
`git merge groot/main`<br>
<br>
`git rebase name                                ` *`Rebase onto the name branch /similar to merge but you dont see merge commit`*<br> 
`git rebase -i HEAD~4                           ` *`It will show the last 4 commits and provide various options for modifying them`*<br>
<br>
`git cherry-pick "commit hash"                  ` *`To pick desired commit(hash) from one branch to another`*<br>


 
 
