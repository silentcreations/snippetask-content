---
name: Add .gitignore
language: git
---
Commit all pending changes, then run this command:

    git rm -r --cached .

This removes everything from the index, then just run:

    git add .

Commit it:

    git commit -m ".gitignore is now working"


  [1]: https://stackoverflow.com/questions/1139762/gitignore-file-not-ignoring
