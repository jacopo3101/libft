# Libft

## Score
![project score](/assets/score.png)


The "libft" project is a fundamental exercise in C programming, requiring to create a custom C library containing essential functions. Divided into mandatory and bonus parts, the project fostering a deep understanding of foundational concepts like memory allocation and string manipulation. Adherence to coding standards, such as the Norm standard and proper memory management practices, is emphasized throughout the project.
The bonus part introduces tasks related to manipulating linked lists, further enhancing proficiency in data structures and algorithms.

## Mandatory function

| Function     | Description                                      |
|:--------------:|:------------------------------------------------:|
| `ft_isalpha`   | Checks if a character is an alphabetic character |
| `ft_isdigit`   | Checks if a character is a decimal digit          |
| `ft_isalnum`   | Checks if a character is alphanumeric             |
| `ft_isascii`   | Checks if a character is a 7-bit ASCII character |
| `ft_isprint`   | Checks if a character is printable                |
| `ft_strlen`    | Calculates the length of a string                 |
| `ft_memset`    | Fills memory with a constant byte                 |
| `ft_bzero`     | Sets a byte string to zero                        |
| `ft_memcpy`    | Copies memory area                                |
| `ft_memmove`   | Copies memory area, allowing overlapping          |
| `ft_strlcpy`   | Copies a string into a fixed-size buffer          |
| `ft_strlcat`   | Appends a string to the end of another            |
| `ft_toupper`   | Converts a lowercase letter to uppercase          |
| `ft_tolower`   | Converts an uppercase letter to lowercase         |
| `ft_strchr`    | Locates the first occurrence of a character       |
| `ft_strrchr`   | Locates the last occurrence of a character        |
| `ft_strncmp`   | Compares two strings                              |
| `ft_memchr`    | Locates the first occurrence of a character in a string |
| `ft_memcmp`    | Compares two blocks of memory                     |
| `ft_strnstr`   | Locates a substring                               |
| `ft_atoi`      | Converts a string to an integer                   |
| `ft_calloc`    | Allocates and clears memory                       |
| `ft_strdup`    | Duplicates a string                               |
| `ft_substr`    | Allocates and returns a substring from a string            |
| `ft_strjoin`   | Concatenates two strings to create a new string           |
| `ft_strtrim`   | Trims leading and trailing characters from a string        |
| `ft_split`     | Splits a string into an array of substrings               |
| `ft_itoa`      | Converts an integer to a string                            |
| `ft_strmapi`   | Applies a function to each character of a string           |
| `ft_striteri`  | Applies a function to each character of a string with its index |
| `ft_putchar_fd`| Outputs a character to a file descriptor                   |
| `ft_putstr_fd` | Outputs a string to a file descriptor                      |
| `ft_putendl_fd`| Outputs a string to a file descriptor followed by a newline|
| `ft_putnbr_fd` | Outputs an integer to a file descriptor                    |

## Bonus function

### List definition

```c
typedef struct s_list
{
    void *content;
    struct s_list *next;
} t_list;
```
| Function        | Description                                                  |
|:---------------:|:------------------------------------------------------------:|
| `ft_lstnew`     | Allocates and returns a new list node                        |
| `ft_lstadd_front`| Adds a new node to the beginning of a list                  |
| `ft_lstsize`    | Counts the number of nodes in a list                         |
| `ft_lstlast`    | Returns the last node of a list                              |
| `ft_lstadd_back`| Adds a new node to the end of a list                         |
| `ft_lstdelone`  | Deletes a single node from a list                            |
| `ft_lstclear`   | Deletes and frees all nodes in a list                        |
| `ft_lstiter`    | Iterates over a list and applies a function to each node     |
| `ft_lstmap`     | Iterates over a list, applies a function to each node, and creates a new list from the results |
