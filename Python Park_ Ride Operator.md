🎢 Python Park Ride operator

Python codeCtrl + Enter to run

1

```

```

Speed

### Test riders

Press Run to test your program with every rider in the queue.

### Console

## Choose a level

## Operator handbook

**= or ==?** One `=` assigns a value: `age = 15`. Two `==` compare two values: `if age == 15:`

**> or >=?** "18 and over" includes 18, so use `age >= 18`. `age > 18` turns away an 18-year-old.

### Comparison operators

| Operator | Meaning | Example that is True |
| --- | --- | --- |
| `==` | equal to | `5 == 5` |
| `!=` | not equal to | `5 != 3` |
| `<` | less than | `3 < 5` |
| `>` | greater than | `5 > 3` |
| `<=` | less than or equal to | `5 <= 5` |
| `>=` | greater than or equal to | `5 >= 5` |

A condition always evaluates to `True` or `False`.

### IF and ELSE

```
if height >= 120:
    print("RIDE")
else:
    print("STOP")
```

The colon `:` ends the if and else lines. The indented lines only run when that branch is chosen.

### FOR loop

```
for i in range(5):
    height = int(input())
    print(height)
```

`range(5)` repeats 5 times. `range(1, 7)` gives 1 to 6: start is included, stop is excluded.

### Data types

| Type | Python name | Example | Cast with |
| --- | --- | --- | --- |
| Integer | `int` | `15` | `int("15")` |
| Real | `float` | `4.5` | `float("4.5")` |
| String | `str` | `"VIP"` | `str(15)` |
| Boolean | `bool` | `True` or `False` | a condition, e.g. `height >= 120` |

`print(type(x))` shows the data type of `x`. `len(text)` gives the number of characters in a string.

### Input and casting

```
age = input("Age: ")         # a string, e.g. "15"
age = int(input("Age: "))    # cast to an integer: 15
```

`input()` always returns a string. Cast with `int()` or `float()` before comparing with a number or doing maths.

### How Python Park checks your code

Your code runs with the same rules and error messages as real Python 3. Prompts inside `input("...")` appear in the console but are not checked. If you use valid Python that the game does not cover yet (such as lists or while loops), it tells you so rather than calling it an error.