---
name: Iterate in chunks
language: ruby
aliases:
- Iterate in slices
read_more:
- https://ruby-doc.org/core-1.8.6/Enumerable.html#method-i-each_slice
---
To iterate in chunks/slices use the `each_slice` method with a parameter indicating the size of each slice.

```ruby
require 'enumerator'
users.each_slice(10) do |a|
  # Do something with `a`
end
```