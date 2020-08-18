# Dictionary key

what they are:
Python dictionary method keys() returns a list of all the available keys in the dictionary.

when you would use them:
You would use them when trying to see all the available keys in a dictionary

* iterating directly over the dictionary saves some memory.
* if you need a copy of the keys, such as when you'll change the dict in the loop.

how to code them

```python
dict = {'Name': 'Zara', 'Age': 7}
print "Value : %s" %  dict.keys()
Value : ['Age', 'Name']
```
