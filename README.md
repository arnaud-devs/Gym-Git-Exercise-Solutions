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
### Exercise 2
```bash
146  git checkout main
147  git checkout -b ft/service-redesign
148  git add services.html
149  git commit -m "Update services page title and content"
150  git push
151  git push -set-upstream origin ft/service-redesign
152  git push --set-upstream origin ft/service-redesign
153  git checkout main
154  git add .
155  git commit -m "Updating services on main branch"
156  git push
157  git checkout ft/service-redesign
158  git diff
159  git checkout main
160  git diff
161  git checkout ft/service-redesign
162  git diff
163  git diff main ..ft/service-redesign
164  git checkout main
165  git merge ft/service-redesign
166  git commit -m "feat: resolving conflit issues in service"
167  git push
```
## Bundle 3
### Exercise 1
```bash
168  git checkout -b ft/team-page
169  git add team.html
170  git commit -m "feat: add team page with member information"
171  git push --set-upstream origin ft/team-page
172  git checkout -b ft/contact-page
173  git checkout ft/team-page
174  git log
175  git checkout ft/contact-page
176  git cherry-pick 79a8d7c35f6e74636739b4ef6b30fc2c3064d3f9
177  git log
178  git add contact.html
179  git commit -m "feat: add contact page with basic HTML structure"
180  git push --set-upstream origin ft/contact-page
181  git checkout -b ft/fq-page
182  git add faq.html
183  git commit -m "feat: add FAQ page with basic HTML structure"
184  git branch -M ft/faq-page
185  git push --set-upstream origin ft/faq-page
186  git revert 79a8d7c35f6e74636739b4ef6b30fc2c3064d3f9
187  git status
188  git add .
189  git push
```