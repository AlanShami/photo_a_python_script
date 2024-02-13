# PHOTO Program

- A Python script that makes calls to different programs to process an image.

# Original (Default) image:

![](https://github.com/AlanShami/photo_a_python_script/blob/main/mickey-1.png)

<!-- Insert a gif  -->
![](https://github.com/AlanShami/photo_a_python_script/blob/main/Assignment%205%20-%20demo.gif)


## What does it have?
- It consists of a Python script, a C program, a Haskell program, a Prolog program, and TWO Matlab programs. 
- A colored detailed steps to tell the user what is happening under the hood. 
- All inputs and outputs are managed by the Python script. 
___
### What does it do?
- First, the script will check the system for the requirements before it proceeds ( C compiler, Haskell, Matlab, prolog compiler).
- The Python script first asks the user for an image to be processed, if no path is specified, a default image will be used.
- The first Matlab program reads the input image and converts it to binary to be used for the following programs.
- The C program applies a thresholding operation on the binary file that was outputted from the first Matlab program, to obtain a black-and-white image.
- The Haskell program inverts the colors of an image (binary) that was produced by the C program.
- The Prolog program reads the binary file that was produced by the first Matlab program and processes the file to create a rotated image out of it. 
- Finally, the second Matlab program gets all the produced files and takes that input from the python program to display the results. 

<!-- Insert a vid demo -->
--

### All Program Files and Codes:
- [wrappper.py](https://github.com/AlanShami/photo_a_python_script/blob/main/wrapper.py)
- [matlab1.m](https://github.com/AlanShami/photo_a_python_script/blob/main/matlab1.m)
- [matlab2.m](https://github.com/AlanShami/photo_a_python_script/blob/main/matlab2.m)
- [c_program.c](https://github.com/AlanShami/photo_a_python_script/blob/main/c_program.c)
- [haskell_program.hs](https://github.com/AlanShami/photo_a_python_script/blob/main/haskell_program.hs)
- [prolog_program.pl](https://github.com/AlanShami/photo_a_python_script/blob/main/prolog_program.pl)
