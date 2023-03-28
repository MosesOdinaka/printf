# printf()
The printf project is a collaboration between Awe Caleb and Moses Iriele, actual students of Software Engineering at ALX (cohort 12) , is a function named "_printf" imitates the actual "printf" command located in the stdio.h library. It contains some of the basic features and functions found in the manual 3 of "printf".

_printf() is a function that performs formatted output conversion and print data. Its prototype is the following:

int _printf(const char *format, ...)
Where format contains the string that is printed. As _printf() is variadic function, it can receives n arguments that replace by n tags written inside the string.

The format tags prototype is the following:

%[flags][length]specifier
If the program runs successfully, the return value is the amount of chars printed.


