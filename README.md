# -FILE-HANDLING-UTILITY

COMPANY : CODTECH IT SOLUTIONS

NAME : SHESHANK

INTERN ID : CT04DG800

DOMAIN : JAVA PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

**Java Program for File Operations: Reading, Writing, and Modifying Text Files**
In this task, we will create a Java program that demonstrates how to read, write, and modify text files. File handling is a crucial aspect of programming, allowing applications to store and retrieve data persistently. This program will provide a utility for basic file operations, showcasing how to manage text files effectively in Java.

Overview of the Program
The program will consist of a single class, FileHandlingUtility, which will include methods for:

Writing to a file: Creating a new file or overwriting an existing file with specified content.
Reading from a file: Displaying the contents of a file line by line.
Modifying a file: Searching for specific text within the file and replacing it with new text.
Key Features
Writing to Files: The program will use BufferedWriter to write text to a file. This approach is efficient as it buffers the output, reducing the number of I/O operations. The method will handle exceptions gracefully, ensuring that any errors during the writing process are reported.

Reading Files: The program will utilize Files.readAllLines from the java.nio.file package to read the contents of a file into a list of strings. This method is straightforward and allows for easy iteration over the lines of the file. The contents will be printed to the console for user visibility.

Modifying Files: The modification method will read the file's contents, search for a specified target string, and replace it with a new string. The modified content will then be written back to the file. This method will ensure that the original structure of the file is preserved while making the necessary changes.
