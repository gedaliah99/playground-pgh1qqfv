# PYTHON: IF & IF/ELSE Statements on a Single-Line

In this tutorial, we will explore how to place "IF" and "IF/ELSE" statements on a single-line.

## The Standard Way

First, let's review how to do IF and IF/ELSE statemtents:
```python runnable
# The IF Statement:
a = 5

if a == 5:
    print("True")


# The IF/ELSE Statement:
a = 5

if a == 5:
    print("True")
else:
    print("False")
```
Try it for yourself.

## Single-Line Code

Now, let's condense them into single-line code snippets.
```python runnable
# The IF Statement:
a = 5

if a == 5:print("True")

# The IF/ELSE Statement:
a = 5

print("True" if a == 5 else "False")
```
Try it for yourself... you should get the same result.

Happy Coding,
@Code-Parser