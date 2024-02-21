# 42Madrid [**libft**](subjects/libft_subject_en.pdf) proyect implementation
This is the first proyect in 42Madrid School. You have to create a library reproducing some existing functions, so you can exploit their functionality in future proyects, since allowed existing functions in 42Madrid proyects are limited.

![C](https://img.shields.io/badge/C-a?style=for-the-badge&logo=C&color=grey)

## Usage:

1. Clone the repository:

		git clone https:://github.com/riveroo19/42my_libft.git

2. Go inside the proyect directory and type `make`:

		cd 42my_libft; make

3. (Optional) Remove object files:

		make clean

4. Take `libft.a` file to one of your proyects and include the libft header on your files:

```C
#include "path/to/libft.h"

/*
	code
*/
```
5. Compile using `libft.a`:

		gcc <.c files> -L. -lft -o <program>
		./<program>

## Make options:

- `all`: compiles the library
- `re`: recompiles the library
- `clean`: removes all object files
- `fclean`: removes `libft.a`and object files

## Bonus:
This will make your library having some other useful functions.

- `make bonus`: compiles the library including bonus funcions

## Disclaimer
> At [42School](https://en.wikipedia.org/wiki/42_(school)), almost every project must be written in accordance to the [Norm](subjects/42norm.pdf), the school's coding standard. As a result, the implementation of certain parts may appear strange and for sure had room for improvement.
