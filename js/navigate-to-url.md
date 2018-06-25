---
name: Navigate to URL
language: js
aliases:
- Go to link
read_more:
- https://developer.mozilla.org/en-US/docs/Web/API/Window/location
---
For regular navigation to a page use

```javascript
window.location.href = 'https://www.example.com';`
```

or shorter equivalent of

```javascript
window.location = 'https://www.example.com';
```

If you want to replace the current page, instead of adding a new entry to history stack, use the `replace`

```javascript
window.location.replace('https://www.example.com');
```
