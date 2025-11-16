# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
### Create a directory named "my-folder"
<img width="459" height="134" alt="image" src="https://github.com/user-attachments/assets/4d17e5a2-89aa-437a-9ab9-496caca6e97b" />


## COMMAND AND OUTPUT

### Remove the directory "my-folder"
<img width="485" height="173" alt="image" src="https://github.com/user-attachments/assets/1a90201a-ff7c-4e90-8f6f-de1ae3814878" />


## COMMAND AND OUTPUT


### Create the file Rose.txt
<img width="457" height="354" alt="image" src="https://github.com/user-attachments/assets/aa86d0ee-ccfa-4ae3-a9c2-8579b8468426" />


## COMMAND AND OUTPUT


### Create the file hello.txt using echo and redirection
<img width="628" height="229" alt="image" src="https://github.com/user-attachments/assets/5ff0eae6-7b65-4e94-8cc5-69c06a9bb0e0" />


## COMMAND AND OUTPUT

### Copy the file hello.txt into the file hello1.txt
<img width="561" height="101" alt="image" src="https://github.com/user-attachments/assets/08dfc302-6bb7-46e1-a16f-817acb09c9e4" />


## COMMAND AND OUTPUT

### Remove the file hello1.txt
<img width="420" height="121" alt="image" src="https://github.com/user-attachments/assets/4df639cc-d5b1-4736-9efb-907a60bd47a7" />




## COMMAND AND OUTPUT

### List out all the associated file extensions 
<img width="595" height="958" alt="image" src="https://github.com/user-attachments/assets/7d7aad0e-bfb3-48c8-bc6c-e9ebba0d3cd2" />






## COMMAND AND OUTPUT
### Compare the file hello.txt and rose.txt
<img width="493" height="252" alt="image" src="https://github.com/user-attachments/assets/4f7c91e8-30e8-411a-8721-7a839a831d00" />



## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="504" height="221" alt="image" src="https://github.com/user-attachments/assets/ca3eaa3d-6891-4d3a-833e-ead189abd916" />



### Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="665" height="283" alt="image" src="https://github.com/user-attachments/assets/d0e705a3-1fd0-4d0f-b1c4-d26b41aabd36" />





### Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="534" height="415" alt="image" src="https://github.com/user-attachments/assets/069b2262-1e12-499d-993d-1e4e25f5e208" />





### Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="507" height="291" alt="image" src="https://github.com/user-attachments/assets/e17de330-919c-4c4d-8942-1f55b694b27d" />



### Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="613" height="433" alt="image" src="https://github.com/user-attachments/assets/f7626b86-c07e-4301-b2fb-f953ae17661f" />




# RESULT:
The commands/batch files are executed successfully.

