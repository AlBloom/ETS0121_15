# Dictionary
In Python, there "dict." which refers to methods and attributes available for dictionaries (the dict class). if we type dict. ,there will be list of built-in methods that can be used with dictionaries.
# dict.fromkeys()
The method creates a new dictionary with specified keys and an optional default value for all keys. Meaning this method will create new dictonary(doesn't modify the original one) and assign the same value to all the keys.
NB. This method is a class method and as such it will be called on the dict class itself, not on dictionary instances
SYNTAX: dict.fromkeys(iterable, [value])
    iterable: string, list, tuple, etc. used as keys for the new dictionary
    value (optional): default value for all keys (defaults to None)

# dict.get()
This method's main objective is to return the value of a specified key. It the same functionality of calling the key in "dict[key]" manner but unlike "dict[key]" (which raises KeyError if the key is missing), get() gracefully returns None or a custom default.
SYNTAX: dict.get(key, default=None)
    key: key to look up in the dictionary.
    default: (Optional) The value to return if the key doesn’t exist (defaults to None).

# dict.items()
This method is used to return a list containing a tuple for each key value pair. It has a feature which returns a dynamic dict_items object (updates if the dictionary changes). It is moslty used to loop through both keys and values simultaneously.

# dict.keys()
This method is used when we want only the keys in the dictionary. It returns a view object of all keys in the dictionary. This method also has a feature which returns a dynamic dict_keys object (updates if the dictionary changes).

# dict.values()
This method is the oppostie of the key() method in which that this one eeturns a list of all the values in the dictionary. We also has the returning feature which is a dynamic dict_values object (updates if the dictionary changes).

# dict.clear()
This method is straight forward in way that it removes all elements of a key-value pairs from the dictionary. It modifies the dictionary in to an empty one.

# dict.copy()
This one is the same as the one in the list methods. This method creates a shallow copy of the dictionary (i.e. new object, same values). When called it will return a copy of the original dictionary.