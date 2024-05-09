# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

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

![image](https://github.com/harshi1111/Windows-basic-commands-batchscript/assets/84671735/031e65c6-ae54-4a99-a8f7-f288889b7143)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![image](https://github.com/harshi1111/Windows-basic-commands-batchscript/assets/84671735/d8d29650-7dea-482e-9f3b-abf6ac1053f9)
![image](https://github.com/harshi1111/Windows-basic-commands-batchscript/assets/84671735/37dfff04-f86c-4b83-9644-49eb0c268b73)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![image](https://github.com/harshi1111/Windows-basic-commands-batchscript/assets/84671735/252bc6be-40ac-422b-8b94-36a07133e28c)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![image](https://github.com/harshi1111/Windows-basic-commands-batchscript/assets/84671735/960ad787-93c6-4cfd-9880-4ddd059ebec1)
![image](https://github.com/harshi1111/Windows-basic-commands-batchscript/assets/84671735/95bad687-ad3a-4018-888a-fec95b0f2a98)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents
![image](https://github.com/harshi1111/Windows-basic-commands-batchscript/assets/84671735/a521c63e-0776-492c-b1d2-49ca07551832)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!




## OUTPUT
![image](https://github.com/harshi1111/Windows-basic-commands-batchscript/assets/84671735/f15d3703-c8cf-492e-838f-d387c7b05787)

## RESULT:

The commands/batch files are executed successfully.






