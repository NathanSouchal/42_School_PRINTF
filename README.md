# ft_printf

`ft_printf` is a **reimplementation of the standard `printf` function** in C, developed as part of the 42 School curriculum. It replicates the behavior of `printf`, handling format specifiers, variadic arguments, and formatted output — without relying on the standard C library's internal formatting functions.

---

## Project Goal

The objective of `ft_printf` is to learn how variadic functions work in C and to deepen your understanding of memory management, string manipulation, and output formatting at a low level.

---

## Implemented Features

The following format specifiers are supported:

| Specifier | Description            |
|-----------|------------------------|
| `%c`      | Character              |
| `%s`      | String                 |
| `%p`      | Pointer address        |
| `%d` / `%i` | Signed decimal int   |
| `%u`      | Unsigned decimal int   |
| `%x` / `%X` | Hexadecimal (lower/upper) |
| `%%`      | Literal percent sign   |
