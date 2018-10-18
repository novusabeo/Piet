Piet
====

---Tested on MacOS & Linux

Piet assembler
--------------

Navigate to directory and run

    ./piet-assembler somefile.piet > out.pnm

Piet compiler
-------------

Navigate to directory and run

    ./piet-compiler somefile.script | piet-assembler > out.pnm

See http://www.toothycat.net/wiki/wiki.pl?MoonShadow/Piet for further documentation and samples.   
   
Kudos to [Hugh Satow](http://freespace.virgin.net/hugh.satow/midp/) for many assorted tweaks and bugfixes.

Can also output .png usually but to be save outputting .pnm and then converting to .png

---

Piet interpreter
----------------

For convenience, a fork of Marc Majcher's Piet interpreter is included. 

    ./piet-assembler assembler-samples/fizzbuzz.piet > fizzbuzz.pnm && interpreter/piet fizzbuzz.png

See http://www.majcher.com/code/piet/Piet-Interpreter.html for documentation and updates.

----

License: Creative Commons Attribution-ShareAlike 4.0, http://creativecommons.org/licenses/by-sa/4.0/  
As attribution, please link back to this github repo, https://github.com/sl236/Piet
