# git-commands

#General git clone process

Git clone ssh(url)
For example we cloned hostdata repository, navigate to hostdata repository and do checkout
git checkout -b feature/tkantipudi
Git branch -a      ( to see all current branches )
Git status   (to see any modification or changes)
Then, save the changes in local editor
Then git status again to see modified files
Git diff      (to see changes)
Git branch --all
Git add .
git commit -m "[DDA-3663] Updated users.yaml file to add new account"
git push -u origin feature/tkantipudi

Git log      (to see previous commits)
To see any particular commit from git log, use
Git show commitID![image]


#git squash commands

If I have two different commits for one repo and want to have only one commit message

Git status
Git stash
Git pull
Git status
git rebase -i HEAD~2
Git status
Git branch
git push origin +feature/clean-temp-folder-in-windows
git commit --amend -m "[DDA-1470] added variable for temp clean task and updated shaw windows version"
git push origin +feature/clean-temp-folder-in-windows
![image](https://user-images.githubusercontent.com/56853496/134558322-5687a9fc-dbad-4488-ab79-5192522e8bc4.png)

