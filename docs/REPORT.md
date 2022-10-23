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


