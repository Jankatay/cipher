# cipher
Try out encoding and decoding with different algorithms. Designed to be as easily contributed as possible in C, rust, haskell, or python.

# usage
Cli
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
You can also use it as a library. main.c is just a cli frontend in fact. 

# installation
Some algorithms use python so ensure you have an interpreter downloaded and setup.

# Contributing
Start by adding your name to credits.md, then read contributing.md 
Documentation is stored in doc/
