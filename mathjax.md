---
layout: mathjax
usemathjax: true
---

```ruby
def probability(total_options, selecting)
  factorial(total_options) / (factorial(selecting)*factorial(total_options - selecting))
end
def factorial(n)
  (1..n).reduce(1, :*)
end
```
{:.px-3}

<br>

```text
2/6 = 15 + 47 + 
2/5 = 10 + 47 + 39 
2/9 = 36 
2/7 = 21 
2/9 = 36
2/7 = 21
```

### Combination Formula

$$
\binom nk = \frac{n!}{k!(n-k)!}
$$

### Permutation Formula?