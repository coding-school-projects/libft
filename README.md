# Libft - My First C Library 🧱

![Hive Helsinki](https://img.shields.io/badge/Hive-Helsinki-000000?style=for-the-badge)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![GitHub code size](https://img.shields.io/github/languages/code-size/yourusername/libft?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**Solo Project** | **Estimated Time**: 60 hours

## 📚 About The Project

Libft is the foundational C library project at Hive Helsinki, where we reimplement standard C functions and create additional utilities from scratch. This library becomes your coding companion throughout the curriculum.

**Key Features**:
- 43+ carefully crafted functions
- Full compliance with 42/Hive Norm
- Memory-safe implementations
- Bonus linked list utilities
- Rigorously tested against edge cases

## 🏁 Getting Started

## 🧾 Functions Implemented

### Part 1 — Libc Functions

- `ft_isalpha`
- `ft_isdigit`
- `ft_isalnum`
- `ft_isascii`
- `ft_isprint`
- `ft_strlen`
- `ft_memset`
- `ft_bzero`
- `ft_memcpy`
- `ft_memmove`
- `ft_strlcpy`
- `ft_strlcat`
- `ft_toupper`
- `ft_tolower`
- `ft_strchr`
- `ft_strrchr`
- `ft_strncmp`
- `ft_memchr`
- `ft_memcmp`
- `ft_strnstr`
- `ft_atoi`
- `ft_calloc`
- `ft_strdup`

### Part 2 — Additional Functions

- `ft_substr`
- `ft_strjoin`
- `ft_strtrim`
- `ft_split`
- `ft_itoa`
- `ft_strmapi`
- `ft_striteri`
- `ft_putchar_fd`
- `ft_putstr_fd`
- `ft_putendl_fd`
- `ft_putnbr_fd`

### Bonus Part — Linked List Functions

> These functions must be implemented only if `BONUS` is specified when compiling.

- `ft_lstnew` – creates a new list node
- `ft_lstadd_front` – adds a node to the front
- `ft_lstsize` – counts nodes in a list
- `ft_lstlast` – returns the last node
- `ft_lstadd_back` – adds a node to the end
- `ft_lstdelone` – deletes one node
- `ft_lstclear` – deletes and frees a list
- `ft_lstiter` – applies a function to each node
- `ft_lstmap` – applies a function to each node, creates a new list

### 🛠️ Installation & Setup

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/libft.git
cd libft

## ⚙️ How to Use

# Compile the library (mandatory part)
make

# Compile bonus part
make bonus

# Clean object files
make clean

# Clean all (including the .a library)
make fclean

# Recompile from scratch
make re
