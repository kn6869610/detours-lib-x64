# detours-lib-x64
How to compile Detours 3.0 Express on windows 8.1 x64 (VS2015)

Getting Detours library to work:
1. Download and install Detours library (https://www.microsoft.com/en-us/download/details.aspx?id=52586)
2. unzip Detours
3. Download my GitHub disasm.cpp. Overwrite the file Detours/src/disasm.cpp
4. run "VS2015 開發人員命令提示字元"
5. cd Detours/src/
6. nmake this src

note: set DETOURS_PROCESSOR=x86
