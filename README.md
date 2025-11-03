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
Create a directory named "my-folder"
<img width="413" height="42" alt="image" src="https://github.com/user-attachments/assets/8ad6376d-b4ad-4b40-934d-59f0293ec845" />
## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="419" height="52" alt="image" src="https://github.com/user-attachments/assets/18267d9b-2ed7-4034-89c0-4ae242cb3ec2" />


## COMMAND AND OUTPUT

Create the file Rose.txt
<img width="580" height="87" alt="image" src="https://github.com/user-attachments/assets/33d90a1e-abbb-4360-b955-9bc508a6eed0" />

## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection
<img width="945" height="46" alt="image" src="https://github.com/user-attachments/assets/9df5ac0f-8e6b-42a9-bb51-a99aa08dc30d" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="781" height="429" alt="image" src="https://github.com/user-attachments/assets/def20943-e6b2-43bc-9c22-1924a760a7cd" />

## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="517" height="42" alt="image" src="https://github.com/user-attachments/assets/bfa98e93-9de8-4da2-b669-3a734a118be7" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="762" height="271" alt="image" src="https://github.com/user-attachments/assets/84674505-2b29-49b4-8b32-2132628f6451" />

## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="863" height="590" alt="image" src="https://github.com/user-attachments/assets/bce40070-e533-4e11-a0dd-15e1a5ce3d9d" />

## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt
<img width="601" height="175" alt="image" src="https://github.com/user-attachments/assets/b88ca5a1-8f17-49e2-a339-1ad13c60a1c8" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT
<img width="454" height="88" alt="image" src="https://github.com/user-attachments/assets/12661364-cf61-4c59-8ed3-de65180d5490" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT
<img width="693" height="190" alt="image" src="https://github.com/user-attachments/assets/51fa9ed9-7d92-4117-89f0-e228d2f17910" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT
<img width="557" height="177" alt="image" src="https://github.com/user-attachments/assets/7aa5c090-8cd5-4a3a-b5df-ef64e53b633c" />

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="466" height="78" alt="image" src="https://github.com/user-attachments/assets/1933503e-a0d6-4d21-9f94-f3aa34cddb27" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

## OUTPUT
<img width="540" height="412" alt="image" src="https://github.com/user-attachments/assets/a55989ed-fb98-4bdb-a6a9-9349ee7d43a5" />

# RESULT:
The commands/batch files are executed successfully.

