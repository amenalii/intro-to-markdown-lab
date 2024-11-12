# How to create a file using the Terminal
![Terminal](https://img.gadgethacks.com/img/45/37/63570236453954/0/13-terminal-commands-every-mac-user-should-know.1280x600.jpg)


## 1.  Opening the Terminal
* To open the terminal on a Mac you need to press `Command` + `Space` to open **Spotlight**.
* Then type in **Terminal** in the search bar. 

## 2.  Locating where we are in the Terminal
The terminal normally opens in the home folder; however, if you are unsure typing in `pwd`should tell you where you are located. 

## 3.  Navigating to a Folder
 Now you must decide if you need to create a file in a new folder or if it needs to be created in an existing folder.

#### To create a file in a new Folder:
* Type `mkdir +  directory name`

#### To create a file in an existing Folder:
* To find an existing folder type `ls` and press **Enter**. This should show you a list of all the files and folders that currently exist
* Now if you type `cd + folder name`, the terminal should take you to the folder you are trying to navigate to. 
* A quick `pwd` should help you confirm which folder you are in. 

> TIP: Folders are reffered to as **directories** in the Terminal. 

## 4.  Creating a File
Now that you are in the ***directory*** that you need to be in; the **touch** command is used to create a file. Typing `touch` + `filename.txt` will create your file. 

##### Example:
```shell
touch Stars.txt
````


For more information on the Terminal, cheeck out the [MACPOW](https://macpaw.com/how-to/use-terminal-on-mac) blog.