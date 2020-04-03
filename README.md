TestGithub


How do we compile and run a c program??

Step 1: Head over to Code::Blocks download page and look out for executable Codeblocks mingw setup. MinGW is a GCC compiler which is bundled with Code::Blocks. Also, it is the easiest way to get GCC on Windows and will save you from all the hardship required to compile C program.


Step 2: Once the download has finished, run the executable file and install it on your PC. Also note the directory where you have installed Code::Blocks. By default, it’ll get installed in Program Files(x86).


Installation task is done.
let’s see how to setup GCC Compiler in Windows.

Step 1: Head over to This PC (My Computer) -> Enter your System Drive (For me, it’s C Drive) -> Program Files(x86) -> CodeBlocks -> MinGW -> bin -> Copy the drive address.


Step 2: Now, we’ll set the path of GCC. Once again, head over to This PC -> Properties -> Advanced System Settings -> Environment Variables -> In System Variables, look out for Path, tap on it and click Edit -> New -> Paste the copied Drive address -> Ok.

 The path variable has been set. Let’s see how to Compile and Run C Program in Windows.
 
 3. Compile and Run C Program in Windows:
 
Step 1: Open Notepad and write a test C program of your choice. Save the program with an extension of .c.

For instance, if you have decided to name your program as Test, save it as Test.c.


Step 2: Launch Command Prompt and point it where your program has been saved. Okay, I’ll let you know how to do this.

Step 3: Once you are done with Step 2, type gcc -o test test.c on Command Prompt Windows and hit Enter. In general, it’s like gcc -o NameOfYourProgram NameOfYourProgram.c

This is how we gonna Compile C program in Windows 10. If there are any errors, it’ll show up there on Command Prompt window.

Step 4: Now, head over to the folder where all your Programs lie. You’ll see the executable of your new compiled program. Double click on it and this how you gonna Run C Program in Windows.
