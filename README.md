# Libft

An enhanced version of **Libft**, my custom C library for the 42 curriculum. It reimplements essential standard library functions and adds extra utilities for use across later 42 projects.

## Included

| Module | Description |
|--------|-------------|
| `libft` | Reimplementation of core C library functions, plus additional utilities. |
| `ft_printf` | Custom `printf` for formatted output. |
| `get_next_line` | Reads a file descriptor one line at a time. |

## Usage

```sh
make            # build libft.a
make clean      # remove object files
make fclean     # remove objects and libft.a
make re         # rebuild from scratch
```

Link it in your project:

```sh
cc main.c -L. -lft -o program
```