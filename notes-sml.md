```
replace speed
  replace duration
    in speed * duration
with 120
  with 4
```

Interesting, I can see it now! This way of showing the abstraction: replace 
`speed`, replace `duration` in `speed * duration`, with `120`, with `4`... 
this can be represented with lambdas. I see it now: "replace" is actually a lambda. So, replacing 
`speed` can be seen as, let's say, `lambda x`, and replacing `duration` as 
`lambda y`. Then `speed * duration` becomes `x * y`. And finally, outside 
of the entire lambda expression, we provide values or arguments: `120` 
and `4`.

$$
(\lambda x.\lambda y. x \cdot y) \, 120 \, 4
$$

```
(lambda x (lambda y (x * y))) 120 4
```

Or with SML:
```ml
(fn x => fn y => x * y) 120 4
```





