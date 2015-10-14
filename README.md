OnePost
=======

Post message on multiple social medias such as Wibo, Facebook.


Fork A Repo
==========

Source: https://help.github.com/articles/fork-a-repo/
<br/>
1. On GitHub, navigate to the target repository.
<br/>
2. In the top-right corner of the page, click <b>Fork</b>.
<br/>
3. git clone https://github.com/YOUR-USERNAME/REPO_NAME.git
<br/>
4. git remote -v
<br/>
5. git remote add upstream https://github.com/TARGET_USERNAME/REPO_NAME.git
<br/>


Sync fork
========

git fetch upstream
<br/>
git checkout master
<br/>
git merge upstream/master

Branch
======

<pre>
Create the branch on your local machine and switch in this branch :
$ git checkout -b [name_of_your_new_branch]

Push the branch on github :
$ git push origin [name_of_your_new_branch]

You can see all branches created by using:
$ git branch

Add a new remote for your branch :
$ git remote add [name_of_your_remote] 

Push changes from your commit into your branch :
$ git push origin [name_of_your_remote]

Update your branch when the original branch from official repository has been updated :
$ git fetch [name_of_your_remote]

Then you need to apply to merge changes, if your branch is derivated from develop you need to do :
$ git merge [name_of_your_remote]/develop

Delete a branch on your local filesystem :
$ git branch -d [name_of_your_new_branch]

To force the deletion of local branch on your filesystem :
$ git branch -D [name_of_your_new_branch]

Delete the branch on github :
$ git push origin :[name_of_your_new_branch]
</pre>

Rember password
==============
git config --global credential.helper store
<br/>
Source: http://wiki.epfl.ch/help-git-en/can-i-store-my-password-for-the-command-line
