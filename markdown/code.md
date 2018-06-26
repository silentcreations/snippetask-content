---
name: Code
language: markdown
read_more:
- https://daringfireball.net/projects/markdown/syntax#code
---
Inline code has back-ticks around it.

```markdown
Inline `code` has `back-ticks` around it.
```

Blocks of code are either fenced by lines with three back-ticks ``` which is the preferred version (see below), or are indented with four spaces.

````markdown
```
var s = "Code block";
alert(s);
```
````

If you would like to use 3rd party library like [Prism](https://prismjs.com) or [highlight.js](https://highlightjs.org) for syntax highlighting, you must use the three back-ticks variant followed by a language name.

````markdown
```python
s = "Python syntax highlighting"
print s
```
````
