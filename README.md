# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript
# NAME:Nandhana.R
# REG:NO:212223040124
# DEPT:CSE


# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab
![image](https://github.com/user-attachments/assets/28a8697c-d3c7-45dc-90ae-24ddee22bf01)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![image](https://github.com/user-attachments/assets/48d1bfc4-2059-45c6-b2f6-f991b87ac819)


![image](https://github.com/user-attachments/assets/5d070ffc-e10b-4055-95f8-9ebb7b3469ef)




## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

dir %userprofile%\Desktop\MyLab


![image](https://github.com/user-attachments/assets/8f78ffd6-2f49-40d2-ba15-7fe97a970d03)

## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents

![image](https://github.com/user-attachments/assets/6b8aabd6-eab8-4bb2-84b0-15d3f4cb2f17)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup

echo Backup completed successfully!





## OUTPUT



![image](https://github.com/user-attachments/assets/9d5e2506-52a7-42db-b640-69f5850dda1c)



# RESULT:
The commands/batch files are executed successfully.

