# fstools
Apple's fsx and fstorture programs. They are very good at finding issues with various system calls and in particular overlapping reads/writes.

Based from work of Bill Zissimopoulos, https://bitbucket.org/billziss/secfs.test

Prerequisites:
* Visual Studio (prepared in VS 2015)
* Windows 10 SDK 

To run:
* Build the fsx.exe x64 with VS
* cd src\fsx
* .\fsx.exe -N 5000 C:\test
