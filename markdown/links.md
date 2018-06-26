---
name: Links
language: markdown
read_more:
- https://daringfireball.net/projects/markdown/syntax#link
---
Regular link

```markdown
[Inline link](https://www.google.com)
```

Link with a title

```markdown
[Inline link with title](https://www.google.com "Google's Homepage")
```

Reference-style link where the actual website is defined at the bottom of the document instead of inline

```markdown
[Reference-style link][some text or just a number]
.
.
.
[some text or just a number]: https://www.mozilla.org
```

URLs and URLs in angle brackets will automatically get turned into links

```markdown
http://www.example.com or <http://www.example.com>
```
