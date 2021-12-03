List is used to store collections of data.

The syntax is 

```
list1 = ["red" , "orange", "blue", "green"]
```

We can access elements with their index.
Index in a list starts from 0.

```
list1 = ["red" , "orange", "blue", "green"]
print (list1[1])
>>> orange
```
To delete an item in the list del keyword is used.
```
list1 = ["red" , "orange", "blue", "green"]
del list1[1]
print(list1)
>>> [red , blue , green]
```

# Inserting an element

To insert an element in the list, The index is added with the item which is supposed to be added.


```
list1 = ["red" , "orange", "blue", "green"]
list1.insert(4,"white")
print(list1)
```
Now the list becomes
```
>>> [red, orange, blue , green, white]
```
There is another method called append which adds an item at the end of the list.
```
list1.append("yellow")
```


# Swapping elements in a list

To swap elements in a list, the index of the elements are mentioned and are equated to the other index, where it needs to be swapped.

```
list1[0],list1[1] = list1[1],list1[0]

