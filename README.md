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

![image](https://github.com/Sunilkumar074/Windows-basic-commands-batchscript/assets/152241049/3347e4c5-3e56-4b1d-ae26-2bd0f77971fe)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![image](https://github.com/Sunilkumar074/Windows-basic-commands-batchscript/assets/152241049/d3a0152e-42fa-4e71-8626-8a8b296b0717)
![image](https://github.com/Sunilkumar074/Windows-basic-commands-batchscript/assets/152241049/3737d2cf-72ad-4d0e-8e28-16c76446af5f)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![image](https://github.com/Sunilkumar074/Windows-basic-commands-batchscript/assets/152241049/be831370-5891-4c72-818f-3ba7fdb52a04)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![image](https://github.com/Sunilkumar074/Windows-basic-commands-batchscript/assets/152241049/b2ddd1e0-3fc5-441a-99aa-48217e52ebaf)
![image](https://github.com/Sunilkumar074/Windows-basic-commands-batchscript/assets/152241049/5d454e25-fa13-4b78-b329-eeb6edf71b7e)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents
![image](https://github.com/Sunilkumar074/Windows-basic-commands-batchscript/assets/152241049/e564fe3d-e1b6-4e58-bb4f-62204e5a9e77)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!




## OUTPUT
![image](https://github.com/Jeevithaelumalai/Windows-basic-commands-batchscript/assets/118708245/c9ec83f6-a056-4184-8124-df0c065cc7e9)

## RESULT:

The commands/batch files are executed successfully.




