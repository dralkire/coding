## Stuff you can do with strings (part 1)



1. Find the length with `len(str)`.
```python
length = len("yes!")
print(length)
```
```
4
```

2. Make a big multi-line string using triple single-quotes `''' '''`.
```python
print('''H
  E
    L
      L
        O''')
```
```
H
  E
    L
      L
        O
```

3. Create vertical space with `"\n"`.
```python
print("H\n\n\nELLO")
```
```
H


ELLO
```

4. Hold place to put a string later with `"{}"`.
```python
joke = 'A {} is a device for finding furniture in the dark.'
```
And put a string in place by using the *method* `str.format(str)`.
```python
bodypart1 = 'Knee'
bodypart2 = 'Shin'
print(joke.format(bodypart1))
print(joke.format(bodypart2))
```
```
A Knee is a device for finding furniture in the dark.
A Shin is a device for finding furniture in the dark.
```

5. You can **add** strings--it *concatenates* them.
```python
firstname = "James"
lastname = "Bond"
fullname = firstname + " " + lastname
print(fullname)
```
6. You can **multiply** a string by an **integer**.
```python
print("tight " * 3)
```
```
tight tight tight
```
```python
print("rock "*4 + "scissors")
```
```
rock rock rock rock scissors
```

7. Print confusing characters for Python by using backslash `\` before them.
```python
print(' \' ')
print(' \\ ')
print(" \" ")
```
```
 ' 
 \ 
 " 
```
