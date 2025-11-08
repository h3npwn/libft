# 🧩 Libft

**Libft** is my custom C library built as part of the **42 curriculum**.  
It re-implements essential C standard library functions and introduces additional utilities for memory handling, string manipulation, and linked list management — all coded entirely from scratch.

---

## 🚀 Overview

The purpose of this project is to create a **personal C standard library** that can be reused in future 42 projects.  
Through `libft`, I gained a deeper understanding of **pointers**, **memory allocation**, and **low-level programming concepts** while developing clean, reusable, and modular code.

---

## ⚙️ Features

### 🧠 Mandatory Part
Re-implementation of standard C library functions:

#### 🧩 Memory
- `ft_memset`
- `ft_memcpy`
- `ft_memmove`
- `ft_bzero`
- `ft_calloc`

#### 🧵 Strings
- `ft_strlen`
- `ft_strdup`
- `ft_strjoin`
- `ft_strncmp`
- `ft_strchr`
- `ft_strrchr`

#### 🔤 Characters
- `ft_isalpha`
- `ft_isdigit`
- `ft_isalnum`
- `ft_isascii`
- `ft_isprint`
- `ft_toupper`
- `ft_tolower`

#### 🔄 Conversions
- `ft_atoi`
- `ft_itoa`

---

### 💥 Bonus Part
Implementation of **linked list utilities**:
- `ft_lstnew`
- `ft_lstadd_front`
- `ft_lstadd_back`
- `ft_lstsize`
- `ft_lstlast`
- `ft_lstdelone`
- `ft_lstclear`
- `ft_lstiter`
- `ft_lstmap`

---

## 🧰 Usage

Clone the repository and compile the library:

```bash
git clone https://github.com/<your-username>/libft.git
cd libft
make
