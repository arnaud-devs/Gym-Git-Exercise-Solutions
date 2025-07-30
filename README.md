# TheGym Exercise

## Bundle 1

### Exercise 1

```bash
135  git branch -M main
136  git add README.md
137  git commit -m "adding readme.md file"
138  git push --set-upstream origin main
139  git status
140  git push
```

### Exercise 2
```bash
126  git stash push -u -m "deleting about.html"
127  git stash push -u -m "Deleting team page"
128  git stash list
129  git stash pop stash@{1}
130  git stash list
131  git stash pop stash@{1}
132  git add home.html
133  git stash pop
134  git reset --hard
```

## Bundle 2

### Exercise 1
```bash
141  git checkout -b ft/bundle-2
142  git add services.html
143  git commit -m "Add services.html page"
144  git push --set-upstream origin ft/bundle-2
```