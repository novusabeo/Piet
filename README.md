![alt text](https://ipfs.io/ipns/QmXbs5uUu3PudTED339yVBpJD66oL99beTid6SH6dhZHLZ/Images/pietb.png)

"Hello World!" in Piet

Image/Program Credit to Thomas Schoch http://www.retas.de/thomas/computer/programs/useless/piet/explain.html

Piet
====

---Tested on MacOS & Linux

Piet assembler
--------------

Navigate to directory and run

    ./piet-assembler somefile.piet > out.pnm

Piet compiler
-------------

Navigate to main directory and run

    ./piet-compiler compiler-examples/somefile.script | piet-assembler > out.pnm

See http://www.toothycat.net/wiki/wiki.pl?MoonShadow/Piet for further documentation and samples.   
   
Kudos to [Hugh Satow](http://freespace.virgin.net/hugh.satow/midp/) for many assorted tweaks and bugfixes.

Can also output .png usually but to be save outputting .pnm and then converting to .png

For some reason -- possibly due to how Windows handles scripts, the scripts in compiler-examples may not work in MacOS or Linux. For this, run this on each in the compiler-examples directory

    cat file_name.script | tr -d '\r' > file_name.script.new
    
Then change the "file_name.script.new back to just .script and ./piet-compiler compiler-examples/somefile.script | piet-assembler > out.pnm should work in the main Piet directory.

---

Piet interpreter
----------------

For convenience, a fork of Marc Majcher's Piet interpreter is included. 

    ./piet-assembler assembler-samples/fizzbuzz.piet > fizzbuzz.pnm && interpreter/piet fizzbuzz.png

See http://www.majcher.com/code/piet/Piet-Interpreter.html for documentation and updates.

----

License: Creative Commons Attribution-ShareAlike 4.0, http://creativecommons.org/licenses/by-sa/4.0/  
As attribution, please link back to this github repo, https://github.com/sl236/Piet
