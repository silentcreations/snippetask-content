---
name: Add .gitignore
language: git
---
Commit all pending changes, then run the following to remove everything from the index

```bash
git rm -r --cached .
```

Then add everything again

```bash
git add .`
```

and commit it (to remove/add any additional files because of changes within `.gitignore` rules)

```bash
git commit -m ".gitignore is now working"
```
