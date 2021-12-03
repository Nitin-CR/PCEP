Dictionaries store data in key-value pairs
That is each key has a value
It does not allow duplication

```
sdict = {
"First Name" : "Sachin",
"Last Name" : "Tendular",
"DOB" : "1973 april 24"
}
```

To access an item in a dictionary. We can access it with its key name

```
a = sdict["DOB"]
print(a)
>>> 1973 april 24
```

To update a key-value in a dictionary, update command is used
```
sdict["year"] = 1974 april 24
```

To delete a key in the dictinoary
```
del sdict['DOB']
```
Now the DOB key gets deleted

# Tuple
* Tuple allows duplicate values.
* They are ordered and unchangeable.
```
stup=("sachin", "tendulkar", "rajini", "kanth")
```

Items present can be accessed with thier index.

```
print(stup[1])
>>> tendulkar
```

Just like lists and dictionaries tuples can be sliced and updated.
