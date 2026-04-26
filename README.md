# FFBeast modding
Repository with tools and guide for modifying the FFBeast software.

The provided python ghidra script labels for ghidra made using ai since its 15k lines of code. It may contain mistakes.

I am not the author and i am not associated with FFBeast

I am also not responsible for any damage to hardware caused by bad code

# Requirements

- FFBeast firmware
- Ghidra
- Having some ghidra knowledge
# How to

Getting the code:
1) Download the python script
2) Create a new ghidra project
3) Go to File > Import file and find your .hex file
4) Select Intel Hex format and language ARM Cortex 32 little default
5) Go to window > Script manager
6) Select create new script > jython
7) Remove its contents and paste the contents of the provided python script
8) Run the script
9) For easier navigation using a code editor go to File > Export program Format "c/c++"
10) Open in a code editor
How to edit:
I reccomend finding what you want to edit in a code editor and then go to the function in ghidra using Navigation > Go to
