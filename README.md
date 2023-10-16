# TpGit

1 ssh-keygen -t rsa -b 4096 -C chebil.moujtaba@gmail.com
2 .ssh/id_rsa.pub
3 cat ~/.ssh/id_rsa.pub
4 ssh -T git@github.com
5 git clone git@github.com:MojtabaChebil/TpGit.git
6 cd TpGit
7 touch index.html
8 git add index.html
9 git log
10 git add index.html
11 git commit -m "2éme commit : ajout de index.html"
12 git log
13 git push
14 git diff commit_id_1 commit_id_2
15 git diff 2éme commit  Premier commit
16 git branch mojtpdevops
17 git checkout mojtpdevops
18 git add .
19 git commit -m "Modification de mojtpdevops"
20 git push origin mojtpdevops
21 git checkout mojtpdevops
22 git commit -am "Modification dans mojtpdevops"
23 git checkout master
24 git checkout main
25 git checkout mojtpdevops
26 git checkout main
27 git add .
28 git push
29 git commit -am "Modification dans main"
30 git checkout mojtpdevops
31 git commit -am "Modification dans mojtpdevops"
32 git checkout main
33 git commit -am "Modification dans maain"
34 git merge mojtpdevops
35 git add .
36 git commit -m "Résolution du conflit"
37 git flow init
38 git flow feature start mojtpdevops
39 git flow feature start mojtpdevops
40 git flow init
41 git flow feature start mojtpdevops
42 git flow release start ma-version
43 git flow feature finish mojtpdevops
44 git flow hotfix start mon-correctif
