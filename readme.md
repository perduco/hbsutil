Usage

1. Copy all exe and dlls to a local folder.  Open a command prompt and change directory to this folder.

2. Type CHQ.PAF.Console.exe from the command line and the app will show its command-line usage.

3. As an example, to merge a data file called test1.json with a handlebar template file called test1.hbs and output it as a html file called test1.html:

./CHQ.PAF.Console.exe /function:CompileHandlebarTemplate /data:.\test1.json /template:.\test1.hbs /output:.\test1.html

A .\ is used here to identify the file path as relative to where the current directory is.  Absolute full paths can also be used instead.