# t1ps4-dc–disasm
Tool for decompiling The Last Of Us ps4

# Tutorial
To decompile a script first find a script file that starts with ss-\<name>.bin
- The program will look for following folder: **sid1/sidbase.bin** in the same directory of the executable so **make sure its there otherwise there will only be a partial resolution of the stringIds**
- In this example we\'re going to use ss-basic-door.bin
Open the terminal and run the following command:
```
.\t1ps4-dc–disasm.exe .\ss-basic-door.bin
```
The program will print on the terminal the script disassembled

# Notes
- The program will output a file called state-sids.txt. This file will have all the states name from the script that has been analyzed. This file gets generated because i didn't have time to run every single script against this program. Once you get enough entries please let me know and i will add them to the sidbase.bin. Once every file has been analyzed i\'ll remove the function.