## Scalar values

```python
# Numbers
2 + 4
7 * 5
int_val = 8
float_val = 4.3

int_val
int_val + 3
int_val * float_val

# Strings
"Hello " + 'World'

string_val = "dog"
"Watch the " + string_val + " run"

string_val * 10
```

## Functions

```python
abs(-3)
max(1, 2, 3)
min(1, 2, 3)
len('this is a string')

i = 5
"An int value: " + str(i)

animal = "mouse"
"Watch the {0} run".format(animal)
```

## Lists

```python
list1 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
list2 = range(20)
list3 = range(5, 12)
list4 = range(0, 14, 2)
list5 = ["goat", 6, "cow", 4.2]

list1
len(list1)
list1[2]
list1[-2]

list1[5]
list1[5] = 99
list1

list1.append(88)
list1.insert(3, 44)
list1.remove(6)
list1 *= 2
```


## Slices

**Syntax:** `list[start_index : end_index : step]`

```python
list2 = range(10)

len(list2)

list2[4]
list2[2:7]

list2[:5]
list2[5:]
list2[:]

list2[::1]
list2[::2]

list2[::-1]
list2[::-2]

list2[-1:-6:-1]
list2[-1:-6:-2]
list2[3:-3]
list2[-3:3:-1]

list2[2:5] = 15

# Sorting Lists
sorted(list2)
sorted(list2, reverse=True)


# List ssignments
a = range(5)
a
b = a
b
a[3] = 99
a
b

b = a[:]
a
b
a[0] = 33
a
b
```

## Strings

```python
str = "Hello World!"
len(str)
str.index("o")
str.count("l")
str.upper()
str.lower()
str.startswith("Hello")
str.endswith("Hello")


vals = str.split(" ")
len(vals)
vals[1] + " " + vals[0]
 

str[2:8]
str[2:8:2]
str[::-1]
str[8:2:-1]
str[8:2:-2]
```


## Loops

```python
vals = range(10)
for i in vals:
    print(i)

vals = range(10)
for i in vals:
    print("The val is " + str(i))
```

## Tuples

Tuples are very similar to lists, except they are immutable.

```python
tuple1 = (1, 2, 3, 4, 5)
tuple2 = (3.0, "cat")

# This is a no go
tuple1[1] = 4

# Unpacking 
val1, val2 = tuple2
val3, val4, val5 = tuple1[1:4]
```

## Dictionaries

```python
dict1 = {"a": "moose", "b": 2, "c": "fox"}

dict1
dict1["c"]
dict1["c"] = "rat"
dict1["c"]

dict2 = {}
for i in range(0, 10):
    dict2["val" + str(i)] = i
dict2
```
