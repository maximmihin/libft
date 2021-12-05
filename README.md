# Libft

## About

“Libft – your own first library” is an individual project at 42

The aim of this project is to code a C library regrouping usual functions that we’ll be allowed to use in all our other projects. At 42 we are not allowed to use standard C library function, we can use only function we coded ourself. So the longer term goal of this library is to grow with our own function.

For this library there are only 3 standard library function allowed are write() from <unistd.h>, malloc() and free() from <stdlib.h>. We are allowed also to use <string.h> for accessing size_t and NULL.

For detailed information, refer to the **subject of this project**



## Mandatory part

### Part 1 - Libc functions

| Function                                                                             | Prototype      | Description                           |
| -------------------------------------------------------------------------------------------- |----------------------- | --------------------------------------------- |
|[ft_isalpha](https://github.com/maximmihin/libft/blob/master/code/ft_isalpha.c)| `int	ft_isalpha(int ch)` | Alphabetic character test. |
|[ft_isdigit](https://github.com/maximmihin/libft/blob/master/code/ft_isdigit.c)| `int	ft_isdigit(int ch)` | Decimal-digit character test. |
|[ft_isalnum](https://github.com/maximmihin/libft/blob/master/code/ft_isalnum.c)| `int	ft_isalnum(int ch)` | Alphanumeric character test. |
|[ft_isascii](https://github.com/maximmihin/libft/blob/master/code/ft_isascii.c)| `int	ft_isascii(int ch)` | Test for ASCII character. |
|[ft_isprint](https://github.com/maximmihin/libft/blob/master/code/ft_isprint.c)| `int	ft_isprint(int ch)` | Printing character test (space character inclusive). |
|[ft_strlen](https://github.com/maximmihin/libft/blob/master/code/ft_strlen.c)  | `size_t	ft_strlen(const char *s)` | Find length of string. |
|[ft_memset](https://github.com/maximmihin/libft/blob/master/code/ft_memset.c)  | `void	*ft_memset(void *buf, int ch, size_t count)` | Write a byte to a byte string. |
|[ft_bzero](https://github.com/maximmihin/libft/blob/master/code/ft_bzero.c)    | `void	ft_bzero(void *buf, size_t count)` | Write zeroes to a byte string. |
|[ft_memcpy](https://github.com/maximmihin/libft/blob/master/code/ft_memcpy.c)  | `void	*ft_memcpy(void *dst, const void *src, size_t n)` | Copy memory area. |
|[ft_memmove](https://github.com/maximmihin/libft/blob/master/code/ft_memmove.c)| `void	*ft_memmove(void *dst, const void *src, size_t len)` | Copy byte string. |
|[ft_strlcpy](https://github.com/maximmihin/libft/blob/master/code/ft_strlcpy.c) | `size_t	ft_strlcpy(char *dst, const char *src, size_t dstsize)` | Size-bounded string copying. |
|[ft_strlcat](https://github.com/maximmihin/libft/blob/master/code/ft_strlcat.c) | `size_t	ft_strlcat(char *dst, const char *src, size_t dstsize)` | Size-bounded string concatenation. |
|[ft_toupper](https://github.com/maximmihin/libft/blob/master/code/ft_toupper.c) | `int	ft_toupper(int ch)` | Lower case to upper case letter conversion. |
|[ft_tolower](https://github.com/maximmihin/libft/blob/master/code/ft_tolower.c) | `int	ft_tolower(int ch)` | Upper case to lower case letter conversion. |
|[ft_strchr](https://github.com/maximmihin/libft/blob/master/code/ft_strchr.c)   | `char	*ft_strchr(const char *s, int c)` | Locate character in string (first occurrence). |
|[ft_strrchr](https://github.com/maximmihin/libft/blob/master/code/ft_strrchr.c) | `char	*ft_strrchr(const char *s, int c)` | Locate character in string (last occurence). |
|[ft_strncmp](https://github.com/maximmihin/libft/blob/master/code/ft_strncmp.c) | `int	ft_strncmp(const char *str1, const char *str2, size_t n)` | Compare strings (size-bounded). |
|[ft_memchr](https://github.com/maximmihin/libft/blob/master/code/ft_memchr.c)   | `void	*ft_memchr(const void *arr, int c, size_t n)` | Locate byte in byte string. |
|[ft_memcmp](https://github.com/maximmihin/libft/blob/master/code/ft_memcmp.c)   | `int	ft_memcmp(const void *buf1, const void *buf2, size_t count)` | Compare byte string. |
|[ft_strnstr](https://github.com/maximmihin/libft/blob/master/code/ft_strnstr.c) | `char	*ft_strnstr(const char *haystack, const char *needle, size_t len)` | Locate a substring in a string (size-bounded). |
|[ft_atoi](https://github.com/maximmihin/libft/blob/master/code/ft_atoi.c)       | `int	ft_atoi(const char *str)` | Convert ASCII string to integer. |
|[ft_calloc](https://github.com/maximmihin/libft/blob/master/code/ft_calloc.c)   |`void	*ft_calloc(size_t nitems, size_t size)`| Memory allocation. |
|[ft_strdup](https://github.com/maximmihin/libft/blob/master/code/ft_strdup.c)   | `char	*ft_strdup(const char *str)` | Save a copy of a string (with malloc). |



### Part 2 - Additional functions

| Function                                                                                    | Prototype | Description |
| -------------------------------------------------------------------------------------------------- |---------------|---------------|
|[ft_substr](https://github.com/maximmihin/libft/blob/master/code/ft_substr.c)        |`char	*ft_substr(char const *s, unsigned int start, size_t len)`| Extract substring from string. |
|[ft_strjoin](https://github.com/maximmihin/libft/blob/master/code/ft_strjoin.c)      |`char	*ft_strjoin(char const *s1, char const *s2)`| Concatenate two strings into a new string (with malloc). |
|[ft_strtrim](https://github.com/maximmihin/libft/blob/master/code/ft_strtrim.c)      |`char	*ft_strtrim(char const *s1, char const *set)`|Trim beginning and end of string with the specified characters.|
|[ft_split](https://github.com/maximmihin/libft/blob/master/code/ft_split.c)          |`char	**ft_split(char const *s, char c)`|Split string, with specified character as delimiter, into an array of strings.|
|[ft_itoa](https://github.com/maximmihin/libft/blob/master/code/ft_itoa.c)            |`char	*ft_itoa(int n)`|Convert integer to ASCII string.|
|[ft_strmapi](https://github.com/maximmihin/libft/blob/master/code/ft_strmapi.c)      |`char	*ft_strmapi(char const *s, char (*f)(unsigned int, char))`|Create new string from modifying string with specified function.|
|[ft_striteri](https://github.com/maximmihin/libft/blob/master/code/ft_striteri.c)    |`void	ft_striteri(char *s, void (*f)(unsigned int, char*))`|Apply function to content of all srting elements.|
|[ft_putchar_fd](https://github.com/maximmihin/libft/blob/master/code/ft_putchar_fd.c)|`void	ft_putchar_fd(char c, int fd)`|Output a character to given file.|
|[ft_putstr_fd](https://github.com/maximmihin/libft/blob/master/code/ft_putstr_fd.c)  |`void	ft_putstr_fd(char *s, int fd)`|Output string to given file.|
|[ft_putendl_fd](https://github.com/maximmihin/libft/blob/master/code/ft_putendl_fd.c)|`void	ft_putendl_fd(char *s, int fd)`|Output string to given file with newline.|
|[ft_putnbr_fd](https://github.com/maximmihin/libft/blob/master/code/ft_putnbr_fd.c)  |`void	ft_putnbr_fd(int n, int fd)`|Output integer to given file.|



## Bonus part

| Function                                                                                                           | Prototype | Description |
| ------------------------------------------------------------------------------------------------------------------------- |-------------- |---------------|
|[ft_lstnew](https://github.com/maximmihin/libft/blob/master/code/ft_lstnew.c)|`t_list	*ft_lstnew(void *content)`|Create new list.|
|[ft_lstadd_front](https://github.com/maximmihin/libft/blob/master/code/ft_lstadd_front.c)|`void	ft_lstadd_front(t_list **lst, t_list *new)`|Add new element at beginning of list.|
|[ft_lstsize](https://github.com/maximmihin/libft/blob/master/code/ft_lstsize.c)          |`int	ft_lstsize(t_list *lst)`| Count elements of a list. |
|[ft_lstlast](https://github.com/maximmihin/libft/blob/master/code/ft_lstlast.c)          |`t_list	*ft_lstlast(t_list *lst)`| Find last element of list. |
|[ft_lstadd_back](https://github.com/maximmihin/libft/blob/master/code/ft_lstadd_back.c)  |`void	ft_lstadd_back(t_list **lst, t_list *new)`|Add new element at end of list.|
|[ft_lstdelone](https://github.com/maximmihin/libft/blob/master/code/ft_lstdelone.c)      |`void	ft_lstdelone(t_list *lst, void (*del)(void *))`|Delete element from list.|
|[ft_lstclear](https://github.com/maximmihin/libft/blob/master/code/ft_lstclear.c)        |`void	ft_lstclear(t_list **lst, void (*del)(void *))`|Delete sequence of elements of list from a starting point.|
|[ft_lstiter](https://github.com/maximmihin/libft/blob/master/code/ft_lstiter.c)          |`void	ft_lstiter(t_list *lst, void (*f)(void *))`|Apply function to content of all list's elements.|
|[ft_lstmap](https://github.com/maximmihin/libft/blob/master/code/ft_lstmap.c)            |`t_list	*ft_lstmap(t_list *lst, void *(*f)(void *), void (*del)(void *))`|Apply function to content of all list's elements into new list.|



## Usage

`make` to compile mandatory functions.

`make bonus` to compile with bonuses.

`make clean` to remove *.o

`make fclean` to remove *.o and libft.a

`make re` rebuild mandatory functions.



## Test Tools Links

- [**Libftest** by jtoty](https://github.com/jtoty/Libftest)
- [**libft-unit-test** by alelievr](https://github.com/alelievr/libft-unit-test)
- [**libft-war-machine** by ska42](https://github.com/ska42/libft-war-machine)

