smallpt-cplusplus
==============

smallpt: Global Illumination in 99 lines of C++ 
(http://www.kevinbeason.com/smallpt/)

This is a simple 'port' of Kevin Beason's smallpt to make it run on Windows via Visual Studio 2012. Please visit Kevin's site for more information.  My purpose is to have a comparison point as I'm going to port the code over to C# and refactor for my own amusement...

I made a few small modifications which increased line count to 105, they are all noted with comments starting with // ***.  I've also supplied a compiled version of smallpt.exe for Windows.  Also, on Windows you may need an application to view the .PPM file output...

For handy timing use the following from PowerShell:
Measure-Command {.\smallpt.exe 5000}
