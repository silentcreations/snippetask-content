---
name: Delete remote
language: git
aliases:
- Remove remote
read_more:
- https://git-scm.com/docs/git-remote
---
Use

```bash
$ git remote -v
```

to list all the remotes

```bash
origin  https://github.com/OWNER/REPOSITORY.git (fetch)
origin  https://github.com/OWNER/REPOSITORY.git (push)
destination  https://github.com/FORKER/REPOSITORY.git (fetch)
destination  https://github.com/FORKER/REPOSITORY.git (push)
```

and then use

```bash
$ git remote rm destination
```

to remove `remote` with that name. Use previous command again to verify it's succesfully removed.

```bash
$ git remote -v
origin  https://github.com/OWNER/REPOSITORY.git (fetch)
origin  https://github.com/OWNER/REPOSITORY.git (push)
```
