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


----
### 7 task
```
git filter-branch --commit-filter '
    if [ "$GIT_AUTHOR_EMAIL" = "bakasaru@list.ru" ];
    then
            GIT_AUTHOR_NAME="AnnemariaRe";
            GIT_AUTHOR_EMAIL="annemariarepenko@gmail.com";
            git commit-tree "$@";
    else
            git commit-tree "$@";
    fi' HEAD
```
![](/docs/img/7.png)

----
### 8 task
```
git config --global rerere.enabled true
git rerere diff
git merge feature

```
![](/docs/img/8_1.png)


----
### 9 task
```
git fsck --lost-found
```
![](/docs/img/9.png)


----
### 10 task
```
git gc
```
![](/docs/img/10.png)


----
### 11 task
```
git add /docs
git add /img
git commit -m "message"
```