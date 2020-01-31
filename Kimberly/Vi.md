
# Basic Linux Commands

Here are a number of commands you may find helpful during your Linux journey while using the command line.

![Linux Penguin](../images/linux-penguin.png) 

## cd
The **cd** command allows you to traverse into a directory. This command is case sensitive and will need to be surrounded by quotes in cases of multi-word folder names. 

###### Example usage
`cd DirectoryName`

`cd “Directory with Space”`


## mkdir
The **mkdir** command creates a new folder or directory. 

###### Example usage
`mkdir DirectoryName`

`mkdir “Directory with Space”`


## cp 
The **cp** command allows for the copying of files via the command line. It takes two arguments: the first is the location of the file to be copied and the second is the the destination. 
 
###### Example usage
`cp myfile.txt /home/destionation/folder/path/mkdir`


## pwd
The **pwd** command helps you figure out which directory you are in. Typing it shows you your full path.

###### Example usage
`pwd`


## mv
The **mv** command  has two functions: first it allows you to move files through the command line and also it can be used to rename files.  

###### Example usage for moving a file
`mv file.txt destinationFolder`

###### Example usage for renaming a file
`mv oldname.txt newname.txt`


## rm
The **rm** command command allows you to delete files and directories. 

###### Example usage to delete just the folder
`rm -r `

###### Example usage to delete folder and directory
`rm `


## history
The **history** command command lists all the previously used commands you’ve used on the command line. You can repeat commands by typing ! and the number from the command line history.

###### Example usage
`history`


## Home directory and ~
The significance of the Home directory and ~ is that the tilde (~) represents your home directory and it’s the short cut to get back quickly to the home directory. For example, typing cd ~ in terminal will quickly and efficiently take you back to your home directory. 


## File paths in Linux

![Linux Directory Structure](../images/Linux-Directory-Structure.jpeg)

Further reading and more detailed information about the detailed strcture of the directory structure can be [found here!](https://www.tecmint.com/linux-directory-structure-and-important-files-paths-explained/)



## Tips and tricks
* **Using the tab key to complete file paths** The tab key can be used to fill up the terminal so that you don't have to type up the entire folder or directory. Start typing the beginning of a folder or file and then hit tab and terminal will fill in the rest! For example, typing "cd Beginni" and tab will fill in the folder name of "cd BeginningOfMyLongFolderName" to save you some time. 
* **Using up and down arrow for history** You don't need to retype the same commands in terminal over and over. Use the up and down arrows to traverse recently used commands you entered in terminal to use them again. This will save you a lot of time if you're repeating common tasks. 
