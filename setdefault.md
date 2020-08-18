# Setdefault

what they are:
method setdefault() is similar to get(), but will set dict[key]=default if key is not already in dict.

when you would use them:
This method returns the key value available in the dictionary and if given key is not available then it will return provided default value.


how to code them

```python
freq_dict[num] = freq_dict.setdefault(num, 0) + 1
```
