# Day 4 -- Python Functions

## Objective

Learn to create reusable Python functions using `def`, parameters, and
`return`.

## Tools

-   Python
-   Jupyter Notebook

## Programs

### 1. Addition

``` python
def add(a, b):
    return a + b

print(add(10, 20))
```

### 2. Maximum

``` python
def maximum(a, b):
    if a > b:
        return a
    return b

print(maximum(50, 80))
```

### 3. Minimum

``` python
def minimum(a, b):
    if a < b:
        return a
    return b

print(minimum(50, 80))
```

### 4. Percentage

``` python
def percentage(obtained, total):
    return (obtained / total) * 100

print(percentage(450, 500))
```

### 5. Mean (Average)

``` python
def mean(numbers):
    return sum(numbers) / len(numbers)

marks = [80, 75, 90, 95, 85]
print(mean(marks))
```

## Parameter Example

``` python
def greet(name):
    return "Hello " + name

print(greet("Jessie"))
```

## Return Example

``` python
def square(n):
    return n * n

print(square(5))
```

## Interview Questions

1.  What is a function?
2.  Why are functions used?
3.  What is the `def` keyword?
4.  What is a parameter?
5.  What is an argument?
6.  What is `return`?

## Conclusion

Functions make code reusable, organized, and easy to maintain.
