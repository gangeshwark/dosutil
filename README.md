DOS UTILITY
=======

This utility provides the maintenance of files and directories. In the directory services the following operations are performed.
Directory services:
  1.	Make directory
  2.	Change directory
  3.	Delete Directory
  4.	List Directory

File services:
=======
  1.  Compress File
  2.	Decompress File
  3.	Get File Attributes
  4.	Set File Attributes
  5.	Encrypting File
  6.	Decrypting File
  7.	Type File
  8.	Delete File

Concepts involved:
=======
  1.	OOP based Project.
  2.	Header files to declare the global functions and to include them in the Program.
  3.	Used VDU mapping to make the program faster and efficient. 

About the project
=======
In this project the main menu is divided into two services: first one is the directory services and the second one is the file services. The item from the main menu can be selected by pressing either the enter key or the hotkey which is represented by the bold character.
This project uses the library dos.h which defines various constants and gives declarations needed for DOS and 8086-specific calls. The union REGS available in the dos.h header file is used to pass information to and from the functions int86() and intdos(). 
