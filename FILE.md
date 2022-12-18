# Git branching exercise

# master branch

[CREATE FILE.md]<br>
1 git add FILE.md<br>
2 git commit -m "Commit 0"<br>

6 git log<br>
7 git checkout -b bug-fix 32227c1b6336b3ac4e7b1c572be676a9a309aedb

## bug-fix branch

[EDIT FILE.md]<br>
8 git commit -am "Commit 3"<br>

[EDIT FILE.md]<br>
9 git commit -am "Commit 4"<br>

14 git log<br>
15 git checkout -b bug-fix-experimental fdf35f761e6fc804838fea1d99aaa6d222653056<br>

## bug-fix-experimental

[EDIT FILE.md]<br>
16 git commit -am "Commit 7"<br>
