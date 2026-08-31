PART A 1
git checkout master
git add week2.md
git commit -m "tao week2.md"
git checkout -b week2

A2
git add week2.md
git commit -m "working 1"
git add week2.md
git commit -m "working 2"

A3
git add week2.md
git commit -m "lam part A3"
git checkout master

A4
git checkout -b week2b
git merge --no-ff week2
git branch -d week2

PART B 1
git checkout -b wip
git add wip.txt
git commit -m "tao file wip"
git checkout master
git merge week2b

B2
git branch --merged
git branch --no-merged

B3 
git branch -d week2b

B4
git branch -m wip work-in-progress
git push -u origin work-in-progress

PART C 1
git checkout work-in-progress
git add wip.txt
git commit -m "them text lam partc"

C2
git branch -vv

PART D1
git checkout master
git checkout -b experiment
git add file1.txt
git commit -m "them 1 file"
git add file2.txt
git commit -m "them file 2"

D2
git checkout master
git add file3.txt
git commit -m "them file 3"

D3 
git checkout experiment
git rebase master

D5
git checkout master
git merge experiment

D67
git add .
git commit -m "giai thich a3 va d4"
git push origin master
