# TpGit

1 ssh-keygen -t rsa -b 4096 -C chebil.moujtaba@gmail.com
2 .ssh/id_rsa.pub
cat ~/.ssh/id_rsa.pub
 ssh -T git@github.com
 git clone git@github.com:MojtabaChebil/TpGit.git
cd TpGit
touch index.html
git add index.html
git log
git add index.html
git commit -m "2éme commit : ajout de index.html"
git log
git push
git diff commit_id_1 commit_id_2
git diff 2éme commit  Premier commit
git branch mojtpdevops
git checkout mojtpdevops
git add .
git commit -m "Modification de mojtpdevops"
git push origin mojtpdevops
git checkout mojtpdevops
git commit -am "Modification dans mojtpdevops"
git checkout master
git checkout main
git checkout mojtpdevops
git checkout main
git add .
git push
git commit -am "Modification dans main"
git checkout mojtpdevops
git commit -am "Modification dans mojtpdevops"
git checkout main
git commit -am "Modification dans maain"
git merge mojtpdevops
git add .
git commit -m "Résolution du conflit"
git flow init
git flow feature start mojtpdevops
git flow feature start mojtpdevops
git flow init
git flow feature start mojtpdevops
git flow release start ma-version
git flow feature finish mojtpdevops
git flow hotfix start mon-correctif
