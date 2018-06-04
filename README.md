# file-generator.py
A simple python script that generates empty files of desired extension.

I came up with this script when I had to create text files for a list of topics. The fastest way to make such files would be to list out each topic in a single file, and have a script create the empty txt files for me.

### How to use
1. __Run the python script without any arguments__ to generate multiple files of the same name and extension:
    A '$' character must be present in the filename, which will be replaced by the instance number of the file. ie. 4           copies of *"file$.txt"* will produce *file0.txt, file1.txt, file2.txt, file3.txt*

2. __Run the python script with the file that contains a newline seperated list of files you want to generate__:
    The script will read every line contained in the file passed as argument, and create files. _NOTE: The file extension must be        specified for all file names in the list._ The acceptable file names depend upon the operating system you're running.
