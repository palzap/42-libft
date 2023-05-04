# libft

The libft project is a C library that you'll develop as part of your curriculum at 42 School. The goal of this project is to create a library of general-purpose functions that you can use in your future projects. These functions cover a variety of tasks, including memory management, string manipulation, and basic input/output operations.

## Functions
##### The following functions need to be recreated:

### Standard functions
* **isalpha**: checks if a given character is an alphabet (A-Z, a-z)
* **isdigit**: checks if a given character is a digit (0-9)
* **tolower**: converts a given uppercase alphabet to lowercase
* **toupper**: converts a given lowercase alphabet to uppercase
* **isalnum**: checks if a given character is either an alphabet or a digit
* **isascii**: checks if a given character is within the ASCII character set
* **strchr**: searches for a given character in a string and returns a pointer to the  first occurrence of that character
* **isprint**: checks if a given character is printable (i.e., can be displayed on the screen)
* **strrchr**: searches for a given character in a string and returns a pointer to the last occurrence of that character
* **strlen**: calculates the length of a given string
* **strncmp**: compares two strings up to a given number of characters and returns an integer value indicating their relationship
* **memset**: sets a block of memory to a given value
* **bzero**: sets a block of memory to zero
* **memchr**: searches for a given byte in a block of memory and returns a pointer to the first occurrence of that byte
* **memcpy**: copies a block of memory from one location to another
* **memcmp**: compares two blocks of memory and returns an integer value indicating their relationship
* **memmove**: copies a block of memory from one location to another, even if the source and destination blocks overlap
* **strnstr**: searches for a given substring in a string and returns a pointer to the first occurrence of that substring, up to a given length
* **strlcpy**: copies a string to a destination buffer, up to a given length
* **strlcat**: appends a string to a destination buffer, up to a given length
* **atoi**: converts a string to an integer value
* **calloc**: allocates memory for an array of elements and initializes the memory to zero
* **strdup**: duplicates a given string, allocating sufficient memory for the new string and copying the original string to the new memory location

### Additional functions
* **ft_substr**: allocates (with malloc) and returns a substring from the string 's'. The substring begins at index 'start' and is of maximum size 'len'.
* **ft_strjoin**: allocates (with malloc) and returns a new string, which is the result of the concatenation of 's1' and 's2'.
* **ft_strtrim**: allocates (with malloc) and returns a copy of 's1' with the characters specified in 'set' removed from the beginning and the end of the string.
* **ft_split**: allocates (with malloc) and returns an array of strings obtained by splitting 's' using the character 'c' as a delimiter. The array must end with a NULL pointer.
* **ft_itoa**: allocates (with malloc) and returns a string representing the integer received as an argument. Negative numbers must be handled.
* **ft_strmapi**: applies the function 'f' to each character of the string 's', and passing its index as first argument to create a new string (with malloc) resulting from successive applications of 'f'.
* **ft_striteri**: applies the function 'f' on each character of the string passed as argument, passing its index as first argument. Each character is passed by address to 'f' to be modified if necessary.
* **ft_putchar_fd**: outputs the character 'c' to the given file descriptor.
* **ft_putstr_fd**: outputs the string 's' to the given file descriptor.
* **ft_putendl_fd**: outputs the string 's' to the given file descriptor followed by a newline.
* **ft_putnbr_fd**: outputs the integer 'n' to the given file descriptor.

### Linked list functions
* **ft_lstnew**: allocates and returns a new node for a linked list, with the content initialized to the given parameter.
* **ft_lstadd_front**: adds a new node to the beginning of a linked list.
* **ft_lstsize**: counts the number of nodes in a linked list.
* **ft_lstlast**: returns a pointer to the last node of a linked list.
* **ft_lstadd_back**: adds a new node to the end of a linked list.
* **ft_lstdelone**: deletes and frees the memory of a single node from a linked list, using a function given as a parameter to delete the content.
* **ft_lstclear**: deletes and frees the memory of a linked list and all of its nodes, using a function given as a parameter to delete the content.
* **ft_lstiter**: iterates through a linked list and applies a function given as a parameter to the content of each node.
* **ft_lstmap**: iterates through a linked list and applies a function given as a parameter to the content of each node, creating a new linked list from the results. If a deletion function is given as a parameter, it is used to delete the content of any nodes that cannot be allocated.

## Evaluation
#### First submission
10/11/2022  
113%

#### Second submission
14/11/2022  
125%
