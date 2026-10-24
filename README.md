*This project has been created as part of the 42 curriculum by [relyaman]*

# libft

## Description

**libft** is the first project of the 42 curriculum. Its goal is to build your own C library by re-coding a set of standard C library functions.

**Overview:**
- Re-implementation of standard `libc` functions (`strlen`, `memcpy`, `atoi`, `strchr`, ...), without using the originals.
- Additional functions for strings, memory, characters and file descriptors (`ft_substr`, `ft_strjoin`, `ft_split`, `ft_itoa`, `ft_putstr_fd`, ...).
- Bonus part: linked list functions (`ft_lstnew`, `ft_lstadd_back`, `ft_lstmap`, ...).
- Written in C, following the 42 Norm, and compiled into a static library: `libft.a`.

## Instructions

### Compilation

```bash
git clone 
cd libft
make          # builds libft.a
make bonus    # adds the linked list functions
```

Other Makefile rules:

```bash
make clean    # removes object files
make fclean   # removes object files and libft.a
make re       # fclean + make
```

### Usage

Include the header in your code:

```c
#include "libft.h"
```
### Example

```c
#include "libft.h"

int main(void)
{
    ft_putstr_fd("Hello, libft!\n", 1);
    return (0);
}
```

## Resources

### References
- [man pages](https://man7.org/linux/man-pages/) — reference for every libc function re-coded
- [GNU C Library Manual](https://www.gnu.org/software/libc/manual/)
- [GNU Make Manual](https://www.gnu.org/software/make/manual/)
- *The C Programming Language* — Brian W. Kernighan & Dennis M. Ritchie
- 42 Norm (the coding standard provided by the curriculum)

### Use of AI
AI (Claude) was used for the following tasks:
- Explaining concepts (static libraries, `ar`, Makefile rules, linked lists)
- Generating the structure of this README
- [Other tasks, e.g. help understanding edge cases, test ideas]

All the code was written, tested and understood by the project authors.
