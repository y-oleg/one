# one

git config --global user.email oleg_yaroshenko@epam.com

git config --global user.name "Oleg Yaroshenko"

git remote -v

//origin  git@github.com:y-oleg/one.git (fetch)

//origin  git@github.com:y-oleg/one.git (push)
  
git remote set-url origin git@github.com:y-oleg/one.git

git config pull.rebase true

git pull origin main

git add one/src/Main.java

git commit -m "Added Main"

git rebase --cotinue

git push origin HEAD:main