Piet
====

---

Piet assembler
--------------

    ./piet-assembler somefile.piet > out.pnm

Piet compiler
-------------

    ./piet-compiler somefile.script | piet-assembler > out.pnm

See http://www.toothycat.net/wiki/wiki.pl?MoonShadow/Piet for further documentation and samples.   
   
Kudos to [Hugh Satow](http://freespace.virgin.net/hugh.satow/midp/) for many assorted tweaks and bugfixes.

---

Piet interpreter
----------------

For convenience, a fork of Marc Majcher's Piet interpreter is included. 

    ./piet-assembler assembler-samples/fizzbuzz.piet > fizzbuzz.pnm && interpreter/piet fizzbuzz.png

See http://www.majcher.com/code/piet/Piet-Interpreter.html for documentation and updates.

----

License: Creative Commons Attribution-ShareAlike 4.0, http://creativecommons.org/licenses/by-sa/4.0/  
As attribution, please link back to this github repo, https://github.com/sl236/Piet
