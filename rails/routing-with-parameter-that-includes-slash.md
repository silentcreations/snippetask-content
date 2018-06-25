---
name: Routing with parameter that includes slash
language: rails
read_more:
- http://guides.rubyonrails.org/routing.html#segment-constraints
---
Use the `:constraints => {:path => /.*/}` constraint to include the parameter with a `/` (slash)

```ruby
get 'users/:path', to: 'users#new', :constraints => {:path => /.*/}
```
