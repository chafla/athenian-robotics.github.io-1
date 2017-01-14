## Scalar values

```python
int_val = 8
float_val = 4.3
string_val = "dog"

int_val
int_val + 3
int_val * float_val
"Watch the " + string_val + " run"
"Watch the {0} run".format(string_val)
"An int value: " + str(int_val)
```

## Lists

```python
list1 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
list2 = range(10)
list3 = range(5, 10)
list4 = range(0, 10, 2)
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

```python
list2 = range(20)
list2[:]
list2[:5]
list2[5:]
list2[::1]
list2[::2]
list2[::-1]
list2[::-2]
```

## Tuples

```python
tuple1 = (1, 2, 3, 4, 5)
tuple2 = (3.0, "cat")

val1, val2 = tuple2
val3, val4, val5 = tuple1[1:4]
```

## Dictionaries

```python
dict1 = {"a": "moose", "b": 2, "c": "fox"}

dict1["c"]
dict1["c"] = "rat"
dict1["c"]

dict2 = {}
for i in range(0, 10):
    dict2["val" + str(i)] = i
dict2
```
