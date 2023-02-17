# Reading-file-in-python
We are going to study how you can read different files with different format using python
You can read a file in Python using the built-in open() function. Here is an example of how to read a file:
In the above code, replace 'filename.txt' with the name of the file you want to read. The second argument 'r' specifies that the file should be opened in read mode. The read() function reads the entire contents of the file into a string variable called contents. You can then use the contents of the file as needed. Finally, don't forget to close the file using the close() function to release the file resource.

Alternatively, you can use a with statement to open the file, which will automatically close the file when you are done with it:
