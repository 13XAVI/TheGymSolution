# Bundle 1
Exerscise 1
```bash
git init
git branch -b master main
git add . , git commit -m"adding changes"
git remote add origin https://github.com/13XAVI/TheGymSolution.git
git push origin main
git checkout -b dev
git checkout -b test
git checkout dev
git branch -d test
```

Exercise2
```bash
git stash save "Saving home.html to remote"
git stash save "Saving about.html  to remote"
git stash save "Saving team.html to remote"
git stash list
git stash pop 'stash@{1}'
git stash apply 'stash@{1}'
git stash pop 'stash@{0}'
git reset --hard HEAD
```
# Bundle 2

Exercises 1
```bash
git checkout ft/bundle-2
Add Some Change in service.html
git add.
git commit -m "Add Some change in service.html"
git pull -u origin main
Request the reviewer Kevine
merge the request
```

Exercise 2
```bash
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
```

# Bundle 3

Exercises 1
```bash
git checkout -b ft/team-page
git add .
git commit " New changes"
git checkout main
git checkout -b ft/contact-page
git checkout ft/team-page
git git cherry-pick git cherry-pick 529edf3ee91d514de0f921299509787cb776fea5
git add . ,git commit ,git push
git checkout -b ft/faq-page
git add ,git commit ,git push
git git revert a5eff46291bcd9b2fe07021d48f2fdb75771928e
git push
```