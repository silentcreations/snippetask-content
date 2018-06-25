---
name: Delete remote
language: git
aliases:
- Remove remote
---
Use `git remote -v` to list all the remotes

```git
$ git remote -v
# View current remotes
origin  https://github.com/OWNER/REPOSITORY.git (fetch)
origin  https://github.com/OWNER/REPOSITORY.git (push)
destination  https://github.com/FORKER/REPOSITORY.git (fetch)
destination  https://github.com/FORKER/REPOSITORY.git (push)
```

and then use `git remote rm destination` to remove all with that name

```git
$ git remote rm destination
# Remove remote
$ git remote -v
# Verify it's gone
origin  https://github.com/OWNER/REPOSITORY.git (fetch)
origin  https://github.com/OWNER/REPOSITORY.git (push)
```
