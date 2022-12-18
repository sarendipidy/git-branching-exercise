# Git branching exercise

# master branch

[CREATE FILE.md]<br>
1 git add FILE.md<br>
2 git commit -m "Commit 0"<br>

3 git add FILE.md<br>
4 git commit -m "Commit 1"<br>

[EDIT FILE.md]<br>
5 git commit -am "Commit 2"<br>

6 git log<br>
7 git checkout -b bug-fix 32227c1b6336b3ac4e7b1c572be676a9a309aedb

## bug-fix branch

[EDIT FILE.md]<br>
8 git commit -am "Commit 3"<br>

[EDIT FILE.md]<br>
9 git commit -am "Commit 4"<br>

10 git merge master<br>
 [EDIT FILE.md]<br>
11 git add FILE.md<br>
12 git commit -m "Commit 5"<br>

[EDIT FILE.md]<br>
13 git commit -am "Commit 6"<br>

14 git log<br>
15 git checkout -b bug-fix-experimental fdf35f761e6fc804838fea1d99aaa6d222653056<br>

## bug-fix-experimental

[EDIT FILE.md]<br>
16 git commit -am "Commit 7"<br>

[EDIT FILE.md]<br>
17 git commit -am "Commit 8"<br>

[EDIT FILE.md]<br>
18 git commit -am "Commit 9"<br>

## bug-fix-experimental branch

19 git checkout master<br>

## master branch
[EDIT FILE.md]<br>
20 git commit -am "Commit 10"<br>


## master branch

21 git checkout bug-fix<br>


## bug-fix branch

22 git merge bug-fix-experimental<br>
[EDIT FILE.md]<br>
23 git add FILE.md<br>
24 git commit -m "Commit 11"<br>

[EDIT FILE.md]<br>
25 git commit -am "Commit 12"<br>


26 git checkout master<br>

## master branch
27 git merge bug-fix<br>
[EDIT FILE.md]<br>
28 git add FILE.md<br>
29 git commit -m "Commit 13"<br>
