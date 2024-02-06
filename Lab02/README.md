# CPE 322 - Lab 02

The purpose of this lab was to learn about the command line commands.

## Results of Commands

* ```$ hostname```
  * Prints the system's host name\
![alt text](image.png)
* ```$ env```
  * Shows the environment variables the user has created
* ```$ ps```
  * Displays the active processes happening on the system
![alt text](image-1.png)
* ```$ pwd```
  * Displays the current working directory\
![alt text](image-2.png)
* ```$ git clone https://github.com/kevinwlu/iot.git```
  * Clones the repository from the GitHub url to the current working directory
![alt text](image-3.png)
* ```$ cd iot```
  * Changes the current working directory into the target (in this case it becomes the iot directory)
![alt text](image-4.png)
* ```$ ls```
  * Shows all files and directories within the current working directory
![alt text](image-5.png)
* ```$ cd```
  * Moves the current working directory back one. From ~/iot to ~
![alt text](image-6.png)
* ```$ df```
  * Displays the total space taken up on the drive as well as how much is left
![alt text](image-7.png)
* ```$ mkdir demo```
  * Creates new directory named 'demo' in the current working directory
* ```$ cd demo```
  * Changes the current working directory to the target (demo in this case)
![alt text](image-8.png)
* ```$ nano file```
  * Opens nano text editor that can create or change files
![alt text](image-9.png)
* ```$ cat file```
  * Renders content in the file just created using the nano terminal
![alt text](image-10.png)
* ```$ cp file file1```
  * Copies the content of 'file' into a new file titled 'file1'
* ```$ mv file file2```
  * Moves/renames the first file to the second file (file &rarr; file2 in this case)
* ```$ rm file2```
  * Removes file2 from the current directory
* ```$ clear```
  * Clears the current terminal window
* ```$ man uname```
  * Displays user manual for the uname command (I believe ```man``` is a UNIX command and does not work on windows, so I used ```uname --help```)
![alt text](image-11.png)
* ```$ uname -a```
  * Prints all information about the system
![alt text](image-12.png)
* ```$ ifconfig```
  * Displays the configuration of the network interface (This is a mac command, on windows I used ```$ ipconfig```)
* ```$ ping localhost```
  * Tests network requests to the local system and returns statistics on packets sent and received and approximate round trip times
![alt text](image-13.png)
* ```$ netstat```
  * Generates displays that show network status and protocol statistics on the current network
![alt text](image-14.png)
