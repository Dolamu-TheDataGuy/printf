## Collaboratory Project to Implement printf() in C.

<img src = "alx.png">


This is a project that showcases the implementation of the printf function in C programming language.

## C Language
The C programming language is a procedural programming language. It was initially developed by Dennis Ritchie as a system programming language to write operating system. The main features of C language include low-level access to memory, simple set of keywords, and clean style, these features make C language suitable for system programming like operating system or compiler development.


## printf function
<p>The printf function is the name of one of the main C output functions, and stands for "print formatted". printf format strings are complementary to scanf format strings, which provide formatted input (lexing aka. parsing). In both cases these provide simple functionality and fixed format compared to more sophisticated and flexible template engines or lexers/parsers, but are sufficient for many purposes.</p>





Many languages other than C copy the printf format string syntax closely or exactly in their own I/O functions.



Write a function that produces output according to a format.

- Prototype: int _printf(const char *format, ...);
- Returns: the number of characters printed (excluding the null byte used to end output to strings)
- write output to stdout, the standard output stream
- format is a character string. The format string is composed of zero or more directives. 
- See man 3 printf for more detail. You need to handle the following conversion specifiers:
	c
	s
	%
- You don’t have to reproduce the buffer handling of the C library printf function
- You don’t have to handle the flag characters
- You don’t have to handle field width
- You don’t have to handle precision
- You don’t have to handle the length modifiers
