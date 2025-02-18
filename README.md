# Libft
The purpose of this project is to re-code some libc functions, as well as other common utility functions to be reused in the subsequent 42 projects.
Since in most 42 projects we can't use any of the standard C library functions, the goal of this first project is to replicate some of the usual functions ourselves, as well as some additional functions.
We have to build a library that we will be able to use in our future projects.

The subject can be found <a href="https://cdn.intra.42.fr/pdf/pdf/149349/en.subject.pdf">here</a>

## Libc Functions

| No  | Name                                                                              | Description                                                                   |
| :-: | :-------------------------------------------------------------------------------- | :---------------------------------------------------------------------------- |
| 1   | [ft_memset](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_memset.c)   | Set memory to a given value.                                                  |
| 2   | [ft_bzero](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_bzero.c)     | Set the first part of an object to null bytes (filling it with zeroes).       |
| 3   | [ft_memcpy](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_memcpy.c)   | Copy bytes from one buffer to another.                                        |
| 4   | [ft_memmove](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_memmove.c) | Copy bytes from one buffer to another, handling overlapping memory correctly. |
| 5   | [ft_memchr](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_memchr.c)   | Find the first occurrence of a character in a buffer.                         |
| 6   | [ft_memcmp](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_memcmp.c)   | Compare the bytes in two buffers.                                             |
| 7   | [ft_strlen](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_strlen.c)   | Get the length of a string.                                                   |
| 8   | [ft_strlcpy](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_strlcpy.c) | Size-bounded string copy.                                                     |
| 9   | [ft_strlcat](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_strlcat.c) | Size-bounded string concatenation.                                            |
| 10  | [ft_strchr](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_strchr.c)   | Find the first occurrence of a character in a string.                         |
| 11  | [ft_strrchr](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_strrchr.c) | Find the last occurrence of a character in a string.                          |
| 12  | [ft_strnstr](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_strnstr.c) | Locate a substring in a string.                                               |
| 13  | [ft_strncmp](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_strncmp.c) | Compare two strings, up to a given length.                                    |
| 14  | [ft_atoi](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_atoi.c)       | Convert ASCII string to integer.                                              |
| 15  | [ft_isalpha](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_isalpha.c) | Test a character to see if it's alphabetic.                                   |
| 16  | [ft_isdigit](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_isdigit.c) | Test a character to see if it's a decimal digit.                              |
| 17  | [ft_isalnum](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_isalnum.c) | Test a character to see if it's alphanumeric.                                 |
| 18  | [ft_isascii](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_isascii.c) | Test a character to see if it's a 7-bit ASCII character.                      |
| 19  | [ft_isprint](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_isprint.c) | Test a character to see if it's any printable character, including a space.   |
| 20  | [ft_toupper](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_toupper.c) | Convert a character to uppercase.                                             |
| 21  | [ft_tolower](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_tolower.c) | Convert a character to lowercase.                                             |
| 22  | [ft_calloc](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_calloc.c)   | Allocate space for an array and initializes it to 0.                          |
| 23  | [ft_strdup](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_strdup.c)   | Create a duplicate of a string, using malloc.                                 |

  The functions calloc and malloc return a void pointer, that had no associated data type with it. A void pointer can hold address of any type and can be typecasted to any type.  

## Additional Functions

| No  | Name                                                                              | Description                                                                   |
| :-: | :------------------------------------------------------------------------------   | :---------------------------------------------------------------------------- |
| 1 | [ft_substr](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_substr.c)     | Get a substring from string.                                                  |
| 2 | [ft_strjoin](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_strjoin.c)   | Concatenate two strings into a new string, using calloc.                      |
| 3 | [ft_strtrim](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_strtrim.c)   | Trim beginning and end of string with the specified substring.                |
| 4 | [ft_split](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_split.c)       | Split string, with specified character as delimiter, into an array of strings.|
| 5 | [ft_itoa](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_itoa.c)         | Convert integer to ASCII string.                                              |
| 6 | [ft_strmapi](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_strmapi.c)   | Create new string from a string modified with a specified function.           |
| 7 | [ft_striteri](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_striteri.c) | Modify a string with a given function.                                        |
| 8 | [ft_putchar_fd](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_putchar_fd.c) | Output a character to given file.                                         |
| 9 | [ft_putstr_fd](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_putstr_fd.c)   | Output string to given file.                                              |
| 10| [ft_putendl_fd](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_putendl_fd.c) | Output string to given file with newline.                                 |
| 11| [ft_putnbr_fd](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_putnbr_fd.c)   | Output integer to given file.                                             |

## Bonus Functions

| No  | Name                                                                                        | Description                                                        |
| :-: | :------------------------------------------------------------------------------------------ | :----------------------------------------------------------------- |
| 1   | [ft_lstnew](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_lstnew.c)             | Create new list.                                                   |
| 2   | [ft_lstadd_front](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_lstadd_front.c) | Add new element at beginning of list.                              |
| 3   | [ft_lstsize](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_lstsize.c)           | Count elements of a list.                                          |
| 4   | [ft_lstlast](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_lstlast.c)           | Find last element of list.                                         |
| 5   | [ft_lstadd_back](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_lstadd_back.c)   | Add new element at end of list.                                    |
| 6   | [ft_lstdelone](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_lstdelone.c)       | Delete element from list.                                          |
| 7   | [ft_lstclear](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_lstclear.c)         | Delete sequence of elements of list from a starting point.         |
| 8   | [ft_lstiter](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_lstiter.c)           | Apply function to content of all list's elements.                  |
| 9   | [ft_lstmap](https://github.com/CatAraujoo/42_Libft/blob/main/Libft/ft_lstmap.c)             | Apply function to content of all list's elements into new list.    |
