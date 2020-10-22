# GIT Basic Commands
## _Here are a bunch of basic git commands._

* __git init__ creates a new local repository in the system.
    * _\$ git init_ \
    Creates local repo in the current working directory.
    * _\$ git init project\_path_ \
    Creates local repo in the specified project diretory.
* __\$ git clone__ is used to copy a repo form a remote repo.
    * _\$ git clone username@host:/path/to/repository_\
    To copy a remote repo.
    * _\$ git clone /path/to/repository_\
    To copy a local repo.
* __git add__ is used to add a file(files) to the staging area.
    * _\$ git add README.md_\
    To add the specific untracked file to staging area.
    * _\$ git add *.txt_\
    To add all untracked txt-files to the staging area.
    * _\$ git add ._\
    To add all untracked files to the staging area.
* __git rm__ used to untrack files from staging area.
    * _\$ git rm --cached \<filename.type\>_\
    Removes from the staging area.
* __git commit__ will create a snapshot of the changes and save it to the git directory.
    * _\$ git commit \-m \"commit message\"_\
    To commit the changes and to provide relevant commit message.
* __git config__ to set user specific configurations.
    * _\$ git config --global user.email example@exmail.com_\
    Sets the email for all the local repos.
    * _\$ git config --local user.email example2@exmail.com_\
    Sets the email for the specific repo only.
    * _\$ git config --global user.name Jon Snow_\
    Sets the name of commiter for all the local repos.
    * _git config --local user.name Tyrion Lannister_\
    Sets the name of the commiter for the specific repo only.
* __git status__ displays the untracked files if any. Also, displays the files that are ready to be committed.
* __git branch__ used to create/view branches.
    * _\$ git branch \<branch_name\>_\
    To create a new branch.
    * _\$ git branch_\
    To view all the branches in the repo.
* __git checkout__ to checkout to a specific branch.
    * _\$ git checkout \<branch_name\>_
* __git merge__ to merge two branches.
    * _\$ git merge \<branch1\> \<branch2\>_\
    Merges branch1 to branch2.
* __git remote__ to create/view remotes for the repo.
    * _\$ git remote -v_\
    To view all the remotes along with thier URL.
    * _\$ git remote add \<remote_name\> \<host-or-remoteURL\>_\
    To connect to a remote repo.
    * _\$ git remote rm \<remote_name\>_\
    To remove a remote repo.
* __git push__ pushes the local repo's specified branch to the remote.
    * _\$ git push \<remote\> \<branch\>_\
    pushes the specified branche to the specified remote.
* __git pull__ merges all the changes in the remote repo with the local repo.