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

<img width="432" height="42" alt="8a" src="https://github.com/user-attachments/assets/17b5f9f0-8c74-4777-9bc1-98641fc5d3f5" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="406" height="57" alt="8b" src="https://github.com/user-attachments/assets/562446f9-423c-45b3-b96b-a1c8e7dc44ec" />


## COMMAND AND OUTPUT


Create the file Rose.txt
<img width="648" height="160" alt="8c" src="https://github.com/user-attachments/assets/ec786241-dcc6-4267-9199-a372f5f94fd9" />

<img width="840" height="287" alt="8d" src="https://github.com/user-attachments/assets/f68e54a1-338e-42be-af6c-beb5065d9920" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
<img width="687" height="71" alt="8e" src="https://github.com/user-attachments/assets/b2b5f23f-04f8-465a-a61e-08827f9b34bc" />
<img width="733" height="161" alt="8f" src="https://github.com/user-attachments/assets/8c713955-c2c0-4c0a-8b99-d7689d70879f" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="675" height="88" alt="8g" src="https://github.com/user-attachments/assets/5f103b04-dd58-4158-9ade-707c4cf45f10" />


## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="461" height="77" alt="8h" src="https://github.com/user-attachments/assets/15d7f92c-36e9-4d09-8c15-f4515442e192" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="595" height="182" alt="8i" src="https://github.com/user-attachments/assets/41e46720-b961-4267-9187-a3b51966826f" />


## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="560" height="846" alt="8j" src="https://github.com/user-attachments/assets/f4faba10-d47c-45ec-b000-5fecbb7c8180" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
<img width="673" height="260" alt="8k" src="https://github.com/user-attachments/assets/768ff0ab-4169-470e-a3db-75e86cf6a48d" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".



## OUTPUT

<img width="490" height="166" alt="8l" src="https://github.com/user-attachments/assets/7853aab7-ba22-4eeb-92bc-c8c26c5724b3" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="761" height="337" alt="8m" src="https://github.com/user-attachments/assets/f9237aa0-f1f4-402c-9af7-d3772d25a9b8" />





Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="528" height="292" alt="8n" src="https://github.com/user-attachments/assets/ac79fdf1-86f4-4504-948f-567201ab7d65" />





Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="477" height="172" alt="8o" src="https://github.com/user-attachments/assets/7a2444c3-2254-4caa-affb-dcd90de4dfa7" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="672" height="543" alt="8p" src="https://github.com/user-attachments/assets/b59674d1-4db1-474e-9a87-870ce265c74e" />



# RESULT:
The commands/batch files are executed successfully.

