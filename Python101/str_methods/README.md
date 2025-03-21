# STRING METHODS 
# str.lower() Method
The "str.lower()" method is a built-in Python string method used to convert all characters in a string to lowercase. This method does not take any parameters. The method returns a new string where all uppercase characters in the original string are converted to lowercase.
The method scans each character in the string. If the character is uppercase, it converts it to its lowercase equivalent.Non-alphabetic characters remain unchanged.
N.B. The original string is not modified. Instead, a new string is returned with all characters converted to lowercase.

# str.upper() Method
The str.upper() method converts all lowercase characters in a string to uppercase. Just like str.lower() it does not modify the original string; instead, it returns a new string with all characters in uppercase. Also this method does not take any parameters. 
It returns a new string where all lowercase characters are converted to uppercase. Non-alphabetic characters and the one's which are already an uppercase remain unchanged.
N.B. Like the previous one the original string is not modified. Instead, a new string is returned with all characters converted to uppercase.

# str.capitalize()
The capitalize() method in Python is a string method that returns a copy of the original string with the first character capitalized and the rest of the characters in lowercase. If the string is empty or the first character is already capitalized, the method will return the string as is.

# isupper()
The isupper() method in Python is used to check if all the alphabetic characters in a string are uppercase. If all letters are uppercase, it returns True, otherwise, it returns False. The method only checks alphabetic characters; numbers and symbols do not affect the result.
If the string contains at least one lowercase letter, it returns False.

# islower()
The islower() method in Python is a string method that checks whether all characters (letters) in the string are lowercase. If all the characters are lowercase, it returns True; otherwise, it returns False. Non-alphabetic characters (like numbers, symbols, or whitespace) are ignored and do not affect the result.
like isupper() this method does not take any parameters.

# str.swapcase()
The swapcase() method is a string method that returns a new string where all the uppercase letters are converted to lowercase, and all the lowercase letters are converted to uppercase. Non-alphabetic characters (like numbers, symbols, or whitespace) remain unchanged.
Again this method does not take any parameters.It returns a new string with the case of each character swapped.

# str.title()
The str.title() method in Python is a string method that returns a new string where the first character of each word is capitalized (title case), and the rest of the characters in each word are lowercase. Words are considered to be sequences of characters separated by whitespace.
You might have noticed that this method is used to modify the capitalization of strings like the capitalize method, but they behave differently. While capitilize method capitalizes only the first character of the "string", the title method first character of each "word".

# str.find()
The find() method is a string method that searches for the first occurrence of a substring within the string. If the substring is found, it returns the index of the first character of the substring. If the substring is not found, it returns -1.
SYNTAX: string.find(substring, start, end)
    substring: The substring to search for in the string.
    start (optional): The starting index within the string where the search begins. Default is 0.
    end (optional): The ending index within the string where the search ends. Default is the end of the string.

# str.index()
The index() method in Python is a string method that searches for the first occurrence of a substring within the string. If the substring is found, it returns the index of the first character of the substring. If the substring is not found, it raises a ValueError.
SYNTAX: string.index(substring, start, end)
    substring: The substring to search for in the string.
    start (optional): The starting index within the string where the search begins. Default is 0.
    end (optional): The ending index within the string where the search ends. Default is the end of the string.

# str.count()
The count() method in Python is a string method that returns the number of non-overlapping occurrences of a substring within the string. If the substring is not found, it returns 0.
SYNTAX: string.count(substring, start, end)
    substring: The substring to count occurrences of in the string.
    start (optional): The starting index within the string where the search begins. Default is 0.
    end (optional): The ending index within the string where the search ends. Default is the end of the string.

# str.replace()
The replace() method in Python is a string method that returns a new string where all occurrences of a specified substring are replaced with another substring.
SYNTAX: string.replace(old, new, count)
    old: The substring to be replaced.
    new: The substring to replace the old substring.
    count (optional): The maximum number of occurrences to replace. If not specified, all occurrences are replaced.

# str.startswith()
The startswith() method in Python is a string method that checks whether the string starts with a specified substring. It returns True if the string starts with the substring, otherwise False.
SYNTAX: string.startswith(prefix, start, end)
    prefix: The substring to check at the beginning of the string.
    start (optional): The starting index within the string where the check begins. Default is 0.
    end (optional): The ending index within the string where the check ends. Default is the end of the string.

# str.endswith()
The endswith() method in Python is a string method that checks whether the string ends with a specified substring. It returns True if the string ends with the substring, otherwise False.
SYNTAX: string.endswith(suffix, start, end)
    suffix: The substring to check at the end of the string.
    start (optional): The starting index within the string where the check begins. Default is 0.
    end (optional): The ending index within the string where the check ends. Default is the end of the string.