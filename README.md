# Libft 

## Introduction

Libft (Library of Functions)

In this project, you will be creating a library of functions, the file structure for this project is the following:

### .c Files 
Where all of your functions will be written in. 

### .h (Header)
Your header file is useful for 2 things:
- First, instead of doing for example `#include <unistd.h>` in all of your .c files, you just write it once in your header and all of your .c files will read it from your header file. 
- Secondly, let's say one of your .c files uses another function from another .c file, well instead of writting that function above, just write `#include "libft.h"` and it will find it in your header file. 

Make sure you add `#include "libft.h"` in all of your .c files.

### Makefile 
Makefile is where you will create a file to compile your projects. Remember how in the piscine, you created an **int main** and **gcc** to compile the projects, well with a Makefile, you don't have to do that anymore, you just type `make` once you have created your Makefile. 

# Great Resource for Libft

https://www.asidesigned.com/project-libft.html 

# Libft Functions

### Functions from `<ctype.h>`

- [`ft_isalpha`](ft_isalpha.c)	- checks  for  an  alphabetic  character.
- [`ft_isdigit`](ft_isdigit.c)	- checks for a digit (0 through 9).
- [`ft_isalnum`](ft_isalnum.c)	- checks for an alphanumeric character.
- [`ft_isascii`](ft_isascii.c)	- checks whether c fits into the ASCII character set.
- [`ft_isprint`](ft_isprint.c)	- checks for any printable character.
- [`ft_toupper`](ft_toupper.c)	- convert char to uppercase.
- [`ft_tolower`](ft_tolower.c)	- convert char to lowercase.

### Functions from `<string.h>`

- [`ft_memset`](ft_memset.c)	- fill memory with a constant byte.
- [`ft_strlen`](ft_strlen.c)	- calculate the length of a string.
- [`ft_bzero`](ft_bzero.c)	- zero a byte string.
- [`ft_memcpy`](ft_memcpy.c)	- copy memory area.
- [`ft_memmove`](ft_memmove.c)	- copy memory area.
- [`ft_strlcpy`](ft_strlcpy.c)	- copy string to an specific size.
- [`ft_strlcat`](ft_strlcat.c)	- concatenate string to an specific size.
- [`ft_strchr`](ft_strchr.c)	- locate character in string.
- [`ft_strrchr`](ft_strrchr.c)	- locate character in string.
- [`ft_strncmp`](ft_strncmp.c)	- compare two strings.
- [`ft_memchr`](ft_memchr.c)	- scan memory for a character.
- [`ft_memcmp`](ft_memcmp.c)	- compare memory areas.
- [`ft_strnstr`](ft_strnstr.c)	- locate a substring in a string.
- [`ft_strdup`](ft_strdup.c)	- creates a dupplicate for the string passed as parameter.

### Functions from `<stdlib.h>`
- [`ft_atoi`](ft_atoi.c)	- convert a string to an integer.
- [`ft_calloc`](ft_calloc.c)	- allocates memory and sets its bytes' values to 0.

### Non-standard functions
- [`ft_substr`](ft_substr.c)	- returns a substring from a string.
- [`ft_strjoin`](ft_strjoin.c)	- concatenates two strings.
- [`ft_strtrim`](ft_strtrim.c)	- trims the beginning and end of string with specific set of chars.
- [`ft_split`](ft_split.c)	- splits a string using a char as parameter.
- [`ft_itoa`](ft_itoa.c)	- converts a number into a string.
- [`ft_strmapi`](ft_strmapi.c)	- applies a function to each character of a string.
- [`ft_striteri`](ft_striteri.c)	- applies a function to each character of a string.
- [`ft_putchar_fd`](ft_putchar_fd.c)	- output a char to a file descriptor.
- [`ft_putstr_fd`](ft_putstr_fd.c)	- output a string to a file descriptor.
- [`ft_putendl_fd`](ft_putendl_fd.c)	- output a string to a file descriptor, followed by a new line.
- [`ft_putnbr_fd`](ft_putnbr_fd.c)	- output a number to a file descriptor.

![image](https://user-images.githubusercontent.com/58959408/150704272-0d7b454d-2872-4695-aade-e5bc9c3b79aa.jpg)
