# My Git Prompt
> A good site for beginners: [learn Git Branching](https://learngitbranching.js.org/?locale=ru_RU)
>> ***In order to review the examples, go to the site at the beginning of the page***

command name | its designation | example
:--- | --- | --- 
Git commit | creating a commit (may have ancestors), Saves changes to the commit |  **NAN** 
Git branch *branchnames* | creates a branch with the specified name | git branch training - **creates a branch with the name traning**
Git checkout -b *branchnames* | creating a branch and instantly switching to it ( reduces the number of commands ) | git checkout -b training - **creates a branch with the name traning and switch to it**
Git merge | merging branches | git merge training - **merge main with traning** 
Git rebase | also merging branches , but cleaner ( does everything in one line ) | git rebase training - **merge main with traning** 
Git checkout *hashcommit* | separates the head to the commit hash | **NAN**
Git log | finds the hash of the commit | **NAN**
Git checkout main^ | moves the head one commit back | **NAN**
Git checkout HEAD~num | goes back to the number of ancestors as specified | **git checkout HEAD~4** 
Git branch -f main HEAD~num | forcibly attaches a branch to a commit | **NAN**
Git reset HEAD~num | undoes the changes by moving the link back (works on local branches) | **NAN**
Git revert HEAD | contains changes completely opposite to those that were in the commit (works on remote branches) | **NAN**
Git cherry-pick *commit* *commit* | copies the comments that we have selected without merging | **NAN**
Git rebase --i HEAD~*num* | takes the specified commits ( opens a window ) in which you edit the specified commits | **NAN**
Git commit *--amend* | makes changes | **NAN**
Git tag *name* *hash* | creates a tag on the specified commit | git tag v1 *hash* 
Git describe *ref* | shows how far the current state is from the tag | **NAN**
Git clone | creates a local copy of the remote repository | **NAN**
Git fetch | retrieves data from a remote repository | **NAN**
Git pull | simplifies downloading and merging | **NAN**
Git fakeTeamwork | creates multiple commits ( empty ) | **NAN**
Git push | adds your developments to the remote repository | **NAN**
Git pull --rebase | solves a problem when a newer commit was added to a remote project | **NAN**
Git branch -u o/main foo | instructs a branch to track a remote branch | **NAN**
Git push origin main | forcibly pushes the specified branches | **NAN**
Git push origin foo:main | push from one ( specified ) branch to another ( specified ) | **NAN**
git remote (-v) | shows which repositories we are connected to | **NAN**
git push --force | rewrites history (used after rebase) | **NAN**


> [go back to the start](https://github.com/ZemaPapenko33/internship)<br>

