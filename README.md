# CSCI 5828 - Spring 2024
## Homework 3
## Emily Parker

Commit 1

Commit 2

Commit 3

Commit 4

Commit 5 - merge conflict resolution

Commit 6

Commit 7

Commit 8

Commit 9

Commit 10

Commit 11

Commit 12

Commit 13

Commit 14

## Commands

### Commit 0
git init emily_parker_hw_3_csci_5828
cd .\emily_parker_hw_3_csci_5828\

git add README.md 
git commit -m "commit 0"
git remote add origin https://github.com/EmilyParker24/emily_parker_hw_3_csci_5828.git
git branch -M main
git push -u origin main
git checkout -b bug-fix

### Commit 1
`git checkout main`<br>
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 1"`<br>
`git push`

### Commit 2
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 2"`<br>
`git push`

### Commit 3 
`git checkout bug-fix`<br>
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 3"`<br>
`git push --set-upstream origin bug-fix`

### Commit 4
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 4"`<br>
`git push`<br>
`git checkout -b bug-fix-experimental`

### Commit 5
`git checkout bug-fix`<br>
`git merge main`<br>
`*merge conflict*`<br>
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "merge conflict resolution"`<br>
`git push`

### Commit 6
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 6"`<br>
`git push`

### Commit 7
`git checkout bug-fix-experimental`<br>
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 7"`<br>
`git push --set-upstream origin bug-fix-experimental`

### Commit 8
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 8"`<br>
`git push`

### Commit 9
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 9"`<br>
`git push`

### Commit 10
`git checkout main`<br>
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 10"`<br>
`git push`

### Commit 11
`git checkout bug-fix`<br>
`git merge bug-fix-experimental`<br>
`*merge conflict*`<br>
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 11"`<br>
`git push`

### Commit 12
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 12"`<br>
`git push`

### Commit 13
`git checkout main`<br>
`git merge bug-fix`<br>
`*merge conflict*`<br>
`[Edit README.md]`<br>
`git add .\README.md`<br>
`git commit -m "commit 13"`<br>
`git push`

### Commit 14
`[Edit README.md]`<br>
`[Add image]`<br>
`git add commit-graph.png README.md`<br>
`git commit -m "commit 14"`<br>
`git push`
