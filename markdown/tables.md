---
name: Tables
language: markdown
read_more:
- https://github.github.com/gfm/#tables-extension-
---
Tables aren't part of the core Markdown specification, but they are part of [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) also called GFM, and [Markdown Here](https://markdown-here.com/) supports them as well.

Use at least 3 dashes `-` to separate each header cell from the rest. Whitespace and outer pipes `|` are optional and are commonly used to make the Markdown itself more readable.

```markdown
| Column 1 | Column 2 | Column 3 |
| -------- |----------| ---------|
| This     | is       | nice     |
| How      | about    | this?    |
| The      | last     | row      |
```

To align columns use `:`. To center-align use `:` on both sides, to right-align use `:` on the right side only.

```markdown
| Left     | Center   | Right    |
| -------- |:--------:| --------:|
| This     | is       | nice     |
| How      | about    | this?    |
| The      | last     | row      |
```
