---
name: Add .gitignore
language: git
---
Commit all pending changes, then run the following to remove everything from the index

```bash
git rm -r --cached .
```

Then you can regularly add everything again

```bash
git add .`
```

and commit it 🙌

```bash
git commit -m ".gitignore is now working"
```
