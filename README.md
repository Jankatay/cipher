# cipher
Try out encoding and decoding with different algorithms. Designed to be as easily contributed as possible using C, rust, haskell, or python. Just knowing or wanting to learn one of these is enough to get started.

# usage
From the cli 
```
./cipher --help             // lists algorithms
./cipher --algorithm --help // show a specific algorithm's usage
```
**example:**
```
./cipher --template-caesar --help
...
./cipher --template-caesar --encode "hello, world"
./cipher --template-caesar --decode "ifmmp, xpsmu"
```
You can also use it as a library. cipher.c is simply a frontend, in fact. 

# installation
Ensure you can run python code fine on your machine to run this program.

Currently only building from source is supported.  
Dependencies
- python3
- make (gmake on bsd)
- ghc
- rust
- g++
Use the script "dependencies.sh" to see if you are missing any executable.

# Contributing
Start by adding your name to credits.md, then read contributing.md 
Documentation is stored in doc/
