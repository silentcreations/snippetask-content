---
name: Truncate text
language: bootstrap
read_more:
- https://getbootstrap.com/docs/4.0/utilities/text/#text-wrapping-and-overflow
aliases:
- Ellipsize text
---
If you have content which is too long for particular container, you can truncate it - trim it and add `...` at the end. Just add `.text-truncate` class to truncate the text within.

Do note that for it to work `display` must be either `display: inline-block` (with `max-width` defined)

```html
<span class="d-inline-block text-truncate" style="max-width: 150px;">
  Praeterea iter est quasdam res quas ex communi.
</span>
```

or `display: block` (eg. within `col-2` div)

```html
<div class="row">
  <div class="col-2 text-truncate">
    Praeterea iter est quasdam res quas ex communi.
  </div>
</div>
```
