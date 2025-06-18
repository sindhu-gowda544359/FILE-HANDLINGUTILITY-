# FILE-HANDLINGUTILITY-

COMPANY NAME: CODTECH IT SOLUTION

NAME:SINDHU CN

INTERN ID:CT04DG1118

DOMAIN:JAVA PROGRAMMING

BATCH DURATION:4 WEEKS

MENTOR NAME:NELLA SANTHOSH KUMAR

This Java program demonstrates basic file operations such as writing, reading, and modifying (appending) text files. It is written entirely using core Java, making it simple and platform-independent. The program uses a console-based menu to allow the user to choose between three main operations: write new content to a file (overwrite mode), read existing content from a file, and append new content to an existing file. It operates on a default file named demo.txt and continues running until the user selects the exit option. This structure makes it an excellent example of how file handling is implemented in Java for beginners and intermediate programmers.

The program uses standard Java classes such as FileWriter, File, and Scanner from the java.io and java.util packages. The FileWriter class is used for both writing and appending data to the file. When the user selects the write option, the file is opened in overwrite mode, and any previous content is erased. When the append option is selected, the file is opened in append mode, and the new content is added at the end. The Scanner class is used to read the file line by line and display its contents on the screen. If the file does not exist when a read operation is attempted, the program catches the FileNotFoundException and displays an error message.

The user interface is implemented using a simple while loop and switch statement, making the program interactive and easy to use. After displaying the menu, the program waits for the user to enter a choice. Based on the input, the appropriate method is called to handle that operation. The user is prompted to enter the content for writing or appending, and the program performs the action and confirms success with a message. Proper error handling is done using try-catch blocks to ensure that the program does not crash due to I/O errors or missing files.

To run this program, users need the Java Development Kit (JDK) installed on their system. It can be executed in any text editor with terminal access or in an Integrated Development Environment (IDE) like Visual Studio Code, IntelliJ IDEA, or Eclipse. These tools provide features like code suggestions, error detection, and easy debugging. Additionally, the program can be run from the command line using the javac command to compile and java to execute. The file used (demo.txt) is created automatically if it does not exist, or used as-is if it’s already present.

