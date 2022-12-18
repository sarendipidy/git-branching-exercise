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
