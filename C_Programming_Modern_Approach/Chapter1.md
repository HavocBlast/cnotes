# Chapter 1: Introducing C


## History of C
C is rooted in UNIX

UNIX started from assembly -> B -> NB (New B) renamed to C

C was seen as stable around 1973

C kept changing and needed standardized

### Standardization
Standizing C began in 1983 under ANSI and completed in 1988
and approved in December 1989 as ANSI standard X3.159-1989

In 1990 is that approved by ISO as ISO/IEC 9899:1990 with this standarded
version being known as C89 or C90. Previous versions were referred to as
K&R C.

In 1999 significant changes occured and a new standard, ISO/IEC 9899:1999,

*NOTE* C is still being changed with the latest version C23 approved in 2024
but C11 and C17 are the most widely used

*NOTE* Linux is currently using GNU11 as the version of C for the kernel as
of 2018. This version doesn't use all of the C11 standard but allows the GNU
extensions while primarily using C99 features
    use the '-std=gnu11' flag when compling for linux kernel 
    *Need to verify this statement*

This book seems to focus on C89 but point out C99 features

### C-Based Languages
    - C++ includes all features of C but with classes and other OOP features
    - Java is based on C++
    - C# is a recent language derived from C++ and Java
    - Perl not has many C features in the language

Even though newer languages based off C are around it can be beneficial
to learn C to master the basic features that those languages inherited.

## Strengths and Weaknesses of C

### Strengths
- Efficiency - speed is the first thing that comes to mind with C. Used in
    areas that assembly would have be used in the past.
- Portability - since C is associated with UNIX from the early days, C is 
    able to run on machines ranging from PCs to supercomputers. C is so small
    that writing a C compiler is easier for different machines which adds to
    the portability.
- Power - large collection of data types and operators allows it to accomplish
    a good bit in a few lines of code.
- Flexibility - origninally created for systems programming, nothing limits the
    language to just systems programming. C is used in all manners and imposes
    very few restrictions.
- Standard Library - the std contains hundreds of functions so less need to
    reinvent the wheel.
- Integration with UNIX - C is powerful when combined with UNIX or UNIX-based
    systems like Linux with some tools in UNIX assuming user knows C.

### Weaknesses
- C programs can be error-prone - the flexibility of C also makes it
    error-prone where the compiler won't catch the error. An extra semicolon
    can cause an infinite loop.
- C programs can be difficult to understand - C is small, it does have features
    not found in all languages and can be combined that would make the program
    hard to read by anyone beside the original author. Programmers too good
    for their own good can write programs impossible to read.
- C programs can be dificult to modify - when designed without maintenance in
    mind, large programs written in C can be hard to change. Modern languages
    offer features like classes or packages to divide programs into more
    manageable pieces.

## Effective Use of C
- Learn how to avoid C pitfalls
- Use software tools to make programs more reliable - tools like lint,
    "bounds-checkers" and "leak-finders"
- Take advantage of existing code libraries
- Adopt a sensible set of coding conventions
- Avoid "tricks" and overly complex code
- Stick to the standard
