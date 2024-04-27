# Windows-basic-commands-batchscript

# Ex08-Windows-basic-commands-batchscript

## AIM :

To execute Windows basic commands and batch scripting

## DESIGN STEPS :

### Step 1 :

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2 :

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.

### Step 3 :

Execute the necessary commands/batch file for the desired output. 

```
DEVELOPED BY :JANARTHANAN B
REG NO : 212223100014
```
## WINDOWS COMMANDS :
## Exercise 1: Basic Directory and File Operations

Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT :

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab

![image](https://github.com/jokerjana/Windows-basic-commands-batchscript/assets/147173630/ddeda514-18a0-4fec-aa68-5d3f707815e5)

## COMMAND AND OUTPUT :

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![image](https://github.com/jokerjana/Windows-basic-commands-batchscript/assets/147173630/877072a1-ec29-4433-84f5-7d1c6d586e74)
![image](https://github.com/jokerjana/Windows-basic-commands-batchscript/assets/147173630/71b89d70-c16f-4669-95e5-24998d3a5b2f)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![image](https://github.com/jokerjana/Windows-basic-commands-batchscript/assets/147173630/e07a33ec-4d56-41ac-9eaa-da8c7ead06b7)

## COMMAND AND OUTPUT :

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![image](https://github.com/jokerjana/Windows-basic-commands-batchscript/assets/147173630/c222a29f-5f02-444f-89cd-c1b18870890f)
![image](https://github.com/jokerjana/Windows-basic-commands-batchscript/assets/147173630/930c5849-a6a4-4ded-b624-c38f044792a4)


## COMMAND AND OUTPUT :

mv Myfile.txt %userprofile%\Documents
![image](https://github.com/jokerjana/Windows-basic-commands-batchscript/assets/147173630/02ac9220-9a66-4994-b772-079da8812daf)

## Exercise 2: Advanced Batch Scripting

Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!

## OUTPUT :
![image](https://github.com/jokerjana/Windows-basic-commands-batchscript/assets/147173630/8f7f928c-d2d8-4aaa-93f1-d0d5d8e2422d)

## RESULT :
The commands/batch files are executed successfully.
