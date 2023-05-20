# Bundle 1
Exerscise 1
git init
git branch -b master main
git add . , git commit -m"adding changes"
git remote add origin https://github.com/13XAVI/TheGymSolution.git
git push origin main
git checkout -b dev
git checkout -b test
git checkout dev
git branch -d test

Exercise2
git stash save "Saving home.html to remote"
git stash save "Saving about.html  to remote"
git stash save "Saving team.html to remote"
git stash list
git stash pop 'stash@{1}'
git stash apply 'stash@{1}'
git stash pop 'stash@{0}'
git reset --hard HEAD

# Bundle 2

Exercises 1
git checkout ft/bundle-2
Add Some Change in service.html
git add.
git commit -m "Add Some change in service.html"
git pull -u origin main
Request the reviewer Kevine
merge the request

Exercise 2
git checkout main
git pull 
git checkout -b ft/service-redesign
git add .
git add service.html
git commit -m "Add some change "
git push 
git push --set-upstream origin ft/service-redesign
git checkout main
git add service.html
git commit -m "Add some change "
git push origin main
git checkout ft/service-redesign
git diff main
git merge main
git add .
git commit
git push