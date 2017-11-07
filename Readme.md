
Load a font in windows session without the need to install it and without the need of having admin rights
=========================================================================================================

Just right click on the font file (.ttf) and then select Open With ..., browse to the fonts.exe application
and select it. 


It would open the font file and load it in the current login session.

Then the font will be available for all applications (note: some of them may need to be restarted in order to see the loaded font). 


After relogin, you might need to repeat the above in order to get the same font loaded again.

Compile
=======
You can compile that simple program with Tiny C Compiler [https://bellard.org/tcc/]


Just download the compiler and then execute

````
   tcc fonts.c
````

If everything goes OK, the output file will be an executable called fonts.exe
