VSC project, configured for multiple project in one directory. Instruction from Udemy Beginnig C++ Programming Course
https://www.udemy.com/course/beginning-c-plus-plus-programming/learn/lecture/27256020#reviews

Installing Compiler - mingw -w 64	
instruction: https://www.youtube.com/watch?v=Zcy981HhGw0		
download from: https://sourceforge.net/projects/mingw-w64/files/  
kroki: 
-MinGW-W64 GCC-8.1.0-> x86_64-win32-sjlj	
-wkleic do C:\Program Files\	
-dodac do zmiennych srodowiskowych ..\bin	
-cmd -> gcc --version

In VSC -> View -> Command Palette -> c/C++ Edit Configurations (UI)
Zestaw konfiguracji do edycji: windows-gcc-x64
Path - C:/Program Files/mingw64/bin/gcc.exe
Tryb funkcji intellisense - windows-gcc-x64
Standard jezyka: c17
Standard jezyka C++: gnu++17

Before Start or Debug choose main.cpp in one of the project directories!