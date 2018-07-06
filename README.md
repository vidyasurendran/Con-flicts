Issue::
>>>>>>>>>>>>>>>>>>>>>>git pull origin master
fatal: refusing to merge unrelated histories


Solution::
>>>>>>>>>>>>>>>>>>>>>>git pull origin master --allow-unrelated-histories
 * branch            master     -> FETCH_HEAD
Auto-merging README.md
CONFLICT (add/add): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.


>>>>>>>>>>>>>>>>>>>>git remote -v
Lists all remote branches

>>>>>>>>>>>>>>>>>>>>git remote rm origin
Removing the remote branch origin


>>>>>>>>>>>>>>>>>>>>git remore rename origin destination
Renaming remote branch 'origin' to 'destination'

git push -u origin master


>>>>>>>>>>>>>>>>>>>>git branch
List all branches and highlight currenct working branch


>>>>>>>>>>>>>>>>>>>>git reset --hard


>>>>>>>>>>>>>>>>>>>>git push -u
Set the upstream config

>>>>>>>>>>>>>>>>>>>>git push -u origin master
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/test.git'
t'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

git rebase master

git mergetool
::::Ref : https://gist.github.com/karenyyng/f19ff75c60f18b4b8149