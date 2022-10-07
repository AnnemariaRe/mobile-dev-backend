### 1 task
![](/docs/img/1.png)


----
### 2 task
```
git cherry -v master 
git rebase -i HEAD~2
git rebase master
git merge ci
git branch -d ci
```
![](/docs/img/2.png)


----
### 3 task
```
git log –reflog
git branch old-master 18eabfefb2ba8d1f5a87817ac36edb3b86e1335c
```
![](/docs/img/3.png)


----
### 4 task
```
git blame prisma/seed.ts
```
![](/docs/img/4.png)


----
### 5 task
```
git bisect start
npm run test
git bisect good/bad
```
![](/docs/img/5.png)


----
### 6 task
```
git filter-branch --index-filter 'git rm --cached .env --ignore-unmatch' --prune-empty --tag-name-filter cat -- --all
```
![](/docs/img/6.png)