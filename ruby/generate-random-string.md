---
name: Generate random string
language: ruby
---
To generate letter-only (`a-z`) string, of length `16` (note: max length can be 26) use

```ruby
('a'..'z').to_a.shuffle[0,16].join
```

---

To generate alphanumeric (`a-z`, `0-9`) string of length `16` (note: max length can be 36) use

```ruby
[*('a'..'z'),*('0'..'9')].shuffle[0,16].join
```

---

To generate alphanumeric (`a-z`, `A-Z`, `0-9`) string of length `16` (note: max length can be 62) use

```ruby
[*('a'..'z'),*('A'..'Z'),*('0'..'9')].shuffle[0,16].join
```
