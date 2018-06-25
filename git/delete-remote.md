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
$ git remote rm destination
```

to remove a `remote` with name `destination`.

To find out what is the name of the `remote`, use the `git remote -v` to list all the remotes.

```bash
$ git remote -v
origin  https://github.com/silentcreations/snippetask-content.git (fetch)
origin  https://github.com/silentcreations/snippetask-content.git (push)
destination  https://heroku.com/silentcreations/snippetask-content.git (fetch)
destination  https://heroku.com/silentcreations/snippetask-content.git (push)
```
