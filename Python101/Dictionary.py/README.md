# Dictionary
In Python, there "dict." which refers to methods and attributes available for dictionaries (the dict class). if we type dict. ,there will be list of built-in methods that can be used with dictionaries.
# dict.fromkeys()
The method creates a new dictionary with specified keys and an optional default value for all keys. Meaning this method will create new dictonary(doesn't modify the original one) and assign the same value to all the keys.
NB. This method is a class method and as such it will be called on the dict class itself, not on dictionary instances
SYNTAX: dict.fromkeys(iterable, [value])
    iterable: string, list, tuple, etc. used as keys for the new dictionary
    value (optional): default value for all keys (defaults to None)