# Asynchronous Programming in Python

Write a Python script to sort files asynchronously
Create a Python script that reads all files in a user-specified source folder and organizes them into subfolders within the output folder based on their file extensions. The script should perform the sorting asynchronously for better efficiency when handling a large number of files.

### Technical Task Description

1.  Import the necessary asynchronous libraries.
2.  Create an `ArgumentParser` object to handle command-line arguments.
3.  Add required arguments to specify the source and target folders.
4.  Initialize asynchronous paths for the source and output directories.
5.  Write an asynchronous function, `read_folder`, to recursively read all files in the source folder and its subfolders.
6.  Write an asynchronous function, `copy_file`, to copy each file into the appropriate subfolder in the target directory based on its file extension.
7.  Set up error logging.
8.  Run the `read_folder` function within the main execution block.

### Acceptance Criteria

1.  The script successfully performs asynchronous reading and copying of files.
2.  Files are correctly sorted into subfolders based on their extensions.
3.  The program properly processes command-line arguments.
4.  All errors are logged.
5.  The code is readable and adheres to PEP 8 standards.
