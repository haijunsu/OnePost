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

Rember password
==============
git config --global credential.helper store

