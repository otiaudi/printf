Printf group project

he printf project is a collaboration between Silas Odero and Samuel Kinyua, actual students of Software Engineering at African Leadership academy(ALX).
where a function named "_printf" imitates the actual "printf" command located in the stdio.h library. It contains some of the basic features and functions found in the manual 3 of "printf".

_printf() is a function that performs formatted output conversion and print data. Its prototype is the following:

int _printf(const char *format, ...)
Where format contains the string that is printed. As _printf() is variadic function, it can receives n arguments that replace by n tags written inside the string.

The format tags prototype is the following:
## %%[flags][length]specifier[flags][length]specifier

#Tasks
 function that produces output according to a format handle c, s, %.

 Handle the following conversion specifiers d, i.

  the unsigned int argument is converted to binary
  Handle the following conversion specifiers:u, o, x, X
  Use a local buffer of 1024 chars in order to call write as little as possible.

  Handle the following custom conversion specifier:



  S : prints the string.
#Authors
Samuel Kinyua
Silas Odero
