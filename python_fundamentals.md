# Python fundamentals

## Array/list

## Modules

Always good to modularize your code.

**module1.py**

```python
def addNumbers(numberOne, numberTwo)
    return numberOne + numberTwo
```

**script.py**
```python
import module1

total = module1.addNumbers(1,2)
print total
```