# g0-compiler
Compiler for g0, an instructional subset of Godiva. Made for CS445: Compiler Design class.

Includes:
    Lexer - Using:
        flex v2.5.37
        gcc (GCC) 4.8.5 20150623 (Red Hat 4.8.5-28)


Edge Case Details:

Swap expressions:
    I am not supporting "z = ( x :=: y )" assignments.. It just doesnt make any sense.
    I am only going to allow statements such as "x :=: y;" or without the semicolon.