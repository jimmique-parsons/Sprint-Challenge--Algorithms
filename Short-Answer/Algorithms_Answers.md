#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

```python
a)  # This is O(1)
    a = 0
    # This loop will run O(n) times
    while (a < n * n * n)
      # a is incremented by n**2 each loop
      # multiplication, addition and assignment is O(1)
      a = a + n * n
    # Total time complexity is O(1 + n + 1) --> O(n)
```

```
b)  sum = 0
    for i in range(n):
      j = 1
      while j < n:
        j *= 2
        sum += 1
```

```
c)  def bunnyEars(bunnies):
      if bunnies == 0:
        return 0

      return 2 + bunnyEars(bunnies-1)
```
## Exercise II


