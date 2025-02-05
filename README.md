# ft_printf

## 📌 Overview
**ft_printf** is a custom implementation of the standard C `printf` function. This project aims to deepen the understanding of **variadic functions**, **formatted output**, and **buffer management** in C. It supports many of the standard `printf` features, allowing formatted printing with various data types.

This is the second project of 42 common core and is designed as an **entry-level implementation**, reinforcing key concepts in **C programming, memory management, and I/O handling**.

## 🔥 Key Features
- Supports **multiple format specifiers**:
  - `%c` → Character
  - `%s` → String
  - `%p` → Pointer address
  - `%d` / `%i` → Integer (decimal)
  - `%u` → Unsigned integer
  - `%x` / `%X` → Hexadecimal (lowercase/uppercase)
  - `%%` → Prints a literal `%`
- **Handles variadic arguments** using `stdarg.h`
- **Manages output efficiently** with buffer optimization
- Written in **pure C** with no external libraries
- Designed following the **Norminette coding style**
