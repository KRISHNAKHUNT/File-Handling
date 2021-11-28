# File-Handling
# file-handling extension wise :-
To arrange all files in defferent folder by extension like png,jpg,txt,ppt,etc..
We need to import the required modules.
So import os and shutil module these are inbuilt modules, so don't need to install them.
And you need to create a variable called path which takes input of the directory path that you want to organize.
And then create a variable called files.
Which consists of a list of lines.
Now write a for loop condition.
Using for loop we traverse through every file from files.
The we spilt the filename and extension of the file.
We only need an extension name so we remove the dot from the extension through slicing.
And then we need write to if statement.
If the extension directly already exits, then we move the file to that directory.
In else we make a new directory and then we move the file into it.
At the last lets run the program
After that you get your all separate file in their respective folder............
