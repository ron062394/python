# Python Part 2

## **List**
Creating and Modifying Lists
``` python
my_list = ["Python", "Java", "C++"]
print("Original list:", my_list)
```

Adding an item to the end
``` python
list_data = [1,2,3,4,5]
print(list_data)
list_data.append(10)
print(list_data)
```

Inserting an item at a specific position
``` python
list_data.insert(3,4.5)
list_data
```

Removing an item by value
``` python
list_data = [1,2,3,4,5,5,5]
list_data.remove(5)
print(list_data
```

Removing an item by index
``` python
list_data = [1,2,3,4,5]
del list_data[0]
print(list_data)
```
``` python
list_data = [1,2,3,4,5]
digit=list_data.pop(1)
print(digit)
print(list_data)
```



List slicing
``` python
list_data = [1,2,3,4,5]
list_data[3:]

```


Extending a List with Another List
``` python
list_a = [1,2,3]
list_b = ["a","b",True]
# list_b.extend(list_a)
# print(list_b)
list_a + list_b
```


Reversing a List
``` python
list_b.reverse()
print(list_b)
```

Sorting a List
``` python
list_data = [3,4,1,8,9,10,8]
list_data.sort(reverse=True)
print(list_data)
```


``` python
list_data = ["z","a","c"]
list_data.sort()
print(list_data)
```


Copying a List
``` python
list_a = [1,2,3,4,5]
list_b = [2,4,6,8,10]
list_c = list_b.copy()
print(list_a)
print(list_b)
print(list_c)
```


Clearing a List
``` python
list_c.clear()
print(list_c)
```


## **Tuple**
Creating a tuple
``` python
tuple_data = (1,2,3,4,5)
print(tuple_data)
tuple_data = (1,2) * 3
print(type(tuple_data))
print(tuple_data)
```

Accessing elements
``` python
tuple_data = (1,2,3,4,5)
print(tuple_data[2])
```


Tuple Immutability
``` python
tuple_data = (1,2,3,4,5)
tuple_data[0]=11
print(tuple_data)
```

## **Dictionary**
Creating a dictionary and accessing values
``` python
dict_data = {"name": "Kevin", "age":31, "address":"Bataan"}
print(type(dict_data))
print(dict_data["age"])
```


Removing a key-value pair
Using get() method to access values
``` python
print(dict_data.get("address"))
```


Removing a key-value pair
``` python
del dict_data["age"]
print(dict_data)
```


Dictionary keys
``` python
print(dict_data.keys())
```


Dictionary values
``` python
dict_data.values()
```


Dictionary items (key-value pairs)
``` python
dict_data.items()
```



