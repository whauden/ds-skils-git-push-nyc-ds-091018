
# The Command Line

When conducting data science (or programming in general), its helpful to get orientated with the command line. On mac computers, this is the terminal application. The command line serves as a low level interpreter through which you, the user, can send commands directly to the computer. As a computer user, you previously have probably sent commands to the computer through a graphical user interface (GUI) such as a web browser, text editor, photo editor, or any other of the myriad of computer programs now in existence. While the command line is initially daunting with its cryptic looking text, we will quickly see some of the many advantages it can have.

# Cloning Learn.co lessons to your local hard drive.

One of the many useful features of the command line will be using git to clone local copies of the curricullum hosted on learn.co. This will allow you to work offline and save changes as you work through exercises and start programming!
To start, **for mac users, open terminal**, **for Windows, open “Git Bash”**.

# pwd

The first command to try out is **pwd** which stands for **print working directory**. This will tell you where you currently are in the computer's directory structure. Try it out.

# cd

The next essential command is **cd** which stands for **change directory**. This allows you to navigate to different folders on your computer's hard drive. Typing cd by itself will automatically take you to your home directory. Typing cd and a folder name will take you to that folder. Typing cd .. will move you one folder up in the hierarchy. Play around and trying moving around folders for a minute or two.

# Tab completion

An extraordinarly useful feature when working on the command line is tab completion. This allows you to hit the tab button to autocomplete names once you have made a unique specification.  


For example, if you navigate to your root directory by running the command **cd**, you will probably have 2 folders within your root directory named "Downloads" and "Documents" (these are standard folder names created by default in most systems, although you may have renamed them, or your system may be different). With these, or longer folder names, it can sometimes become cumbersome to type the full folder name. instead, you can start typing the command and folder name such as **"cd Dow"** and then press **tab** to autocomplete. Like magic, the command line should complete the statement correctly to be **cd Downloads**. (Note: this will not work if you have another folder that begins with "Dow". Similarly, if you just typed **cd D** or **cd Do** followe by **tab**, the command line will not autocomplete, as the selection is not unique, because **D** or **Do** could both refer to either **Documents** or **Downloads**. Also note that these commands are case sensative, and folder capitalization much be matched exactly.

# ls

Continuing with navigating the computer's hard drive, it's useful to now how to **list files**. This is done with the **ls** command, short for list.

You can also pass optional parameters to ls such as **ls -a** which list **all files** (including hidden files), **ls -l** which will give a **long listing** of files (including file size and last edit times) or you can pass multiple parameters simultaneously such as **ls -al** to produce a detailed listing of all files.

# * the wildcard paramter

Also very useful is the wildcard paramter. For example, if you wanted to list all files in the current working directory that begin with a, you could type **ls a***. Here, the asterix (*) denotes anything is allowed following the a. Similarly, to list all pdf files in the current working directory we could type **ls *.pdf**, or to list all text files, we could type **ls .txt**.

# mkdir

Finally, as you continue to navigate the file directory from the command line it can be useful to be able to create new folders. To do this, use the **mkdir** command, which stands for **make directory**. Try it out with **mkdir NewFolderName**. Afterwards, use the **ls** command to see that there is indeed a new folder, and if you wish, move into the new folder using the **cd** command.

# Cloning github repos and Learn.co lessons

Now that you can navigate the file directory using the command line, you're ready to download some course materials from the web to your local environment.  

* Create a folder on your computer for your course materials and navigate into it. 
* Then create a subfolder titled "Day1" (or something similar) and navigate into that.

* Return to your web browser and navigate to the lesson you want to download.
* Click the github icon

<img src="Learn_Github_Logo.png">

You'll be redirected to the associated github repository like this.  
* **Click the fork button**, as shown in order to create a copy to your personal account which you can edit and update.
<img src="Github_Fork_Button.png">

After a moment of this:
<img src="Github_Forking_In_Progress.png" width=350>
You'll be redirected to your new personal copy of the repository:
<img src="Forked_Github_Page.png" width=700>
## Finally: 
* Press cmd+L to highlight the url bar and cmd+v to copy the url
* Return to terminal (you should be in your "Day1" folder)
* Type: **git clone** and paste your repo url (**cmd + v**)

### Voila!  
#### The repository and all of its contents will be downloaded locally to your computer!
