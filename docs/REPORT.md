1. git instaweb --start

    git instaweb --start --port 5432 

    git instaweb --browser chrome
![](img.png)
2.  git checkout ci   

    git rebase -i HEAD~11

    git rebase master   

    git checkout master

    git merge ci

    git branch -d ci
    ![](img_1.png)    
    ![](img_2.png)
    ![](img_3.png)
    ![](img_4.png)
3. git log --reflog

   git checkout 1003a0301ea01afe83c562665e829f8c7461c488 

   git branch old-master
   ![](img_5.png)
   ![](img_6.png)
   ![](img_7.png)
4. git log -L 32:prisma/seed.ts
   ![](img_8.png)
5. npm run test  

   git bisect start

   git bisect bad

   git bisect start

   git bisect good 024877a9

   git bisect bad     

   npm run test  

   git bisect good

   npm run test   

   git bisect bad
   ![](img_9.png)
   ![](img_10.png)
6. git filter-branch --force --index-filter 'git rm --cached --ignore-unmatch .env' --prune-empty --tag-name-filter cat -- --all
   ![](img_11.png)
   ![](img_12.png)
7. git checkout feature

   git filter-branch -f --env-filter 'GIT_AUTHOR_NAME=OvsiannikovaOlgaAndreevna GIT_AUTHOR_EMAIL=ovsysha@gmail.com GIT_COMMITTER_NAME=OvsiannikovaOlgaAndreevna GIT_COMMITTER_EMAIL=ovsysha@gmail.com'
   ![](img_13.png)
