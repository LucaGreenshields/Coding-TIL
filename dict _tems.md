# Dictionary items

what they are:
Items returns an iterable accessing a tuple of the key value pairs in the dictionary.

when you would use them:
When you want act on each of the key-value pairs in the dictionary.

how to code them:

```python
dict = {'England': 'Boris', 'Scotland': 'Nicola'}
for data_tuple in dict.items
	print( f"{data_tuple[0]} PM {data_tuple[1]}")
```
