compilador: GCC (GNU Compiler Collection) en su versión 12.2.0, compilado por el proyecto MSYS2

Pasos que fui haciendo en el compilador y su resultado:

Franco@DESKTOP-PQSR3RQ MINGW64 ~ <br>
$ cd /c/Users/Franco/Desktop/Sintaxis/Tp0 

Franco@DESKTOP-PQSR3RQ MINGW64 /c/Users/Franco/Desktop/Sintaxis/Tp0 <br>
$ gcc -o hello.exe hello.c 

Franco@DESKTOP-PQSR3RQ MINGW64 /c/Users/Franco/Desktop/Sintaxis/Tp0 <br>
$ ./hello.exe <br>
Hello, world!

Franco@DESKTOP-PQSR3RQ MINGW64 /c/Users/Franco/Desktop/Sintaxis/Tp0 <br>
$ ./hello.exe > output.txt

Franco@DESKTOP-PQSR3RQ MINGW64 /c/Users/Franco/Desktop/Sintaxis/Tp0 <br>
$ cat output.txt <br>
Hello, world!
