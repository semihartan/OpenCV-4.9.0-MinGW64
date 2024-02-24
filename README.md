# Prebuilt OpenCV-4.9.0 Binaries for C++ Developement on MinGW64
This repository contains the prebuilt binaries of OpenCV-4.9.0 for C++ development on MingW64.

### How to Install
This is my preferred way to install these files. You can adjust it to your like but the crucial ones are **bolded**. 
1. Download the repository or clone it.
2. Create a folder named `OpenCV` (or you can use the name of the repo, `OpenCV-4.9.0-MinGW64`) and copy all the files inside the repo to it.
3. Put `OpenCV` to wherever you like.
4. **Add the path `{Path to OpenCV}\x64\mingw\bin` to your PATH environment variable.** This is required for the OS to locate the binary DLL files when you execute your program.
I suggest you to install MinGW64 using [MSYS2](https://www.msys2.org/).
### Notice
You **cannot** link against the binary files provided by this repo in your Microsoft C++ workflow. Binary files produced by MinGW64 C++ compiler use a different name mangling scheme than that Microsoft uses internally. 
