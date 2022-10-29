# Chicken Egg Problem

Which came first, the chicken or the egg?

> ["🐔", "🥚"] or ["🥚", "🐔"] ?

## Experiment

### Python

```python
sorted(["🥚", "🐔"])                                                                                                              
# ['🐔', '🥚']
```

### JavaScript

```javascript
["🥚", "🐔"].sort()
// [ '🐔', '🥚' ]
```

### Ruby

```ruby
["🥚", "🐔"].sort()
# ["🐔", "🥚"]
```

### Go

```go
arr := []string{"🥚", "🐔"}
sort.Strings(arr)
// [🐔 🥚]
```

### PHP

```php
$arr = ["🥚", "🐔"];
sort($arr);
// Array
// (
//     [0] => 🐔
//     [1] => 🥚
// )
```

### Julia

```julia
sort(["🥚", "🐔"])
# ["🐔", "🥚"]
```

## Result

In conclusion, the chicken came first, then the egg!

> ["🐔", "🥚"]

## Reference

- [JavaScript Chicken or Egg Sort](https://daily-dev-tips.com/posts/vanilla-javascript-chicken-or-egg/)
