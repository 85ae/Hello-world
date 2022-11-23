# Hello-world

## Introduction

Hello-world is a compilation of "hello world" projects in some different languages.

## Languages

The following languages are inclued:
 - C
 - C++
 - HTML
 - XHTML
 - Java
 - JavaScript
 - MarkDown
 - Python
 - Shell (Bash)
 - Batch (Windows only)
 - PHP

## Building

To build, run the following commands:
```
{C} -o helloworld-c.{EXT} helloworld.c
{CPP} -o helloworld-cpp.{EXT} helloworld.cpp
javac helloworld.java
php helloworld.php > helloworld-php.html
```
Replace `{C}` / `{CPP}` by your C / C++ compiler (gcc, clang, cl...) and `{EXT}` by executable extension (`exe` for Windows, `out` for Linux and `app` for MacOS).

### **Example:** on Linux with gcc / g++
```
gcc -o helloworld-c.out helloworld.c
g++ -o helloworld-cpp.out helloworld.cpp
javac helloworld.java
php helloworld.php > helloworld-php.html
```

## Running

Here's a list of how to execute the helloworld programs:
 - C: just type `./helloworld-c.{EXT}` in a terminal
 - C++: run `./helloworld-cpp.{EXT}` in a terminal
 - (X)HTML: open it in your internet browser
 - Java: type `java HelloWorld` in a terminal
 - JavaScript: type `node helloworld.js` or just `helloworld.js` in Linux (needs Node.js)
 - MarkDown: open it in a MarkDown editor such as [StackEdit](https://stackedit.io/) or [Dillinger](https://dillinger.io/) and convert it to HTML
 - Python: type `python helloworld.py` or `helloworld.py`
 - Shell: run `helloworld.sh`
 - Batch: double-click on `helloworld.bat`
 - PHP: open `helloworld-php.html` in a browser

## License

This project is licensed under the [GNU <abbr title="General Public License">GPL</abbr> v3.0](LICENSE).
