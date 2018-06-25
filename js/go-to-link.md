---
name: Go to link
language: js
aliases:
- Navigate to URL
read_more:
- https://developer.mozilla.org/en/window.location
---
For regular navigation to a page use

```window.location.href = 'https://www.example.com';```

or shorter equivalent of

```window.location = 'https://www.example.com';```

If you want to replace the current page, instead of adding a new entry to history stack, use the `replace`

```window.location.replace('https://www.example.com');```
