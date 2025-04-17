# Libft

## 🧠 About

**Libft** is the first individual project at Hive Helsinki. It lays the foundation for C programming by implementing a custom standard library. Through this project, students recreate several essential functions from the C standard library as well as a few additional utility functions. It emphasizes understanding memory management, pointers, and robust coding practices.

## 🏗️ Project Structure

The library includes:

### Part 1 - Libc Functions

Re-implementations of common libc functions such as:
- `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
- `ft_strlen`, `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`
- `ft_strlcpy`, `ft_strlcat`, `ft_toupper`, `ft_tolower`, `ft_strchr`, `ft_strrchr`
- `ft_strncmp`, `ft_memchr`, `ft_memcmp`, `ft_strnstr`, `ft_atoi`
- `ft_calloc`, `ft_strdup`

### Part 2 - Additional Functions

Additional helper functions including:
- `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`
- `ft_itoa`, `ft_strmapi`, `ft_striteri`
- `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### Bonus - Linked List Utilities

Functions to manipulate singly linked lists:
- `ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`
- `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`
- `ft_lstiter`, `ft_lstmap`

## 📁 File Organization

- `libft.h`: Header file containing all function prototypes and necessary includes.
- `*.c`: Source files for each function.
- `Makefile`: Build system to compile the library into `libft.a`.

## 🧪 How to Use

### Clone the Repository
```bash
git clone https://github.com/yourusername/libft.git
cd libft
