# dlox Language
My following through the incredible [*Crafting Interpreters*](https://craftinginterpreters.com/contents.html) book in the context of my UENF's "Compilers" subject. 

# Instructions

## Prerequisites
Java.

## Build
``` 
javac jlox/Lox.java -d ./build/
```
## Run 
### Complete
``` 
java -cp ./build/ jlox.Lox
```
### Partials
``` 
java -cp ./build/ jlox_scanner.Lox
```
``` 
java -cp ./build/ jlox_parser.Lox
```
``` 
java -cp ./build/ jlox_interpreter.Lox
```
# file structure
    ├── README.md                  <- The top-level README for developers using this project (also know as this file!)
    ├── build                      <- java .class compiled executables
    │   ├── jlox                   <- Most recent complete language build
    │   ├── jlox_interpreter       <- Built interpreter, returns evaluated expressions
    │   ├── jlox_parser            <- Built parser, returns prefixed expression   
    │   └── jlox_scanner           <- Built scanner, returns tokens  
    └── jlox                       <- language source files 
# Examples
## Lexical analyzer
## Synthetical analyzer