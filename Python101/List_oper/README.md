# LISTS
# list.append()
append() is a list method that is used for adding an element to the end of the list. The original list will be modified. We can append any type of data in a list.
SYNTAX: list.append(data)

# list.clear()
clear() is used to remove all items from given list. Like append() the original list will be modified.
SYNTAX: list.clear()

# list.copy()
copy() is used to create a copy of the list. Unlike the above two this method doesn't modify the list. When called of printed it will return a new list with same element and you can modify it as you like.

# list.count()
count() counts occurrences of a specific element in the list and then returns the number of elements with the specified value.
In the method's parentheses a data is entered so that the method can find how many of that data are on the list

# list.extend()
You can say that extend() method is the big brother of append() method. While the append() method add a single element to the end of the list, the extend() method adds multiple elements (from an iterable) to the end of the list.
When we talk about "iterables" we are talking about lists, tuplet and the others.

# list.index()
This method is used to find the first occurrence of a value and returns it's index.
SYNTAX: list.index(element, start, end)
    element: value to be searched
    start: index to start searching, optional and on default it starts from 0
    end: index to stop searching, optional and on default goes through all the list