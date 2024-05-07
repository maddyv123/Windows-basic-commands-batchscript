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
%userprofile%\Desktop\MyLab
![image](https://github.com/Oviya24032K6/Windows-basic-commands-batchscript/assets/147139999/8e43b5af-ef4a-4361-b254-a72e5b2cb36e)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![image](https://github.com/Oviya24032K6/Windows-basic-commands-batchscript/assets/147139999/1b509cb4-3233-4f94-9a61-94fcc275a87f)
![image](https://github.com/Oviya24032K6/Windows-basic-commands-batchscript/assets/147139999/7a189b2c-62d6-4b8f-a1e5-ea2820decb30)




## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
 %userprofile%\Desktop\MyLab
 ![image](https://github.com/Oviya24032K6/Windows-basic-commands-batchscript/assets/147139999/48130912-27da-470c-888e-abb3c921f206)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![image](https://github.com/Oviya24032K6/Windows-basic-commands-batchscript/assets/147139999/8e267f0f-7213-40c7-b41a-ab914e7fdf26)
![image](https://github.com/Oviya24032K6/Windows-basic-commands-batchscript/assets/147139999/b021d964-885c-439f-afdd-00f8f740f0bb)




## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents 
![image](https://github.com/Oviya24032K6/Windows-basic-commands-batchscript/assets/147139999/13bbb763-cbf6-4a28-8952-d422cc23fe1f)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!







## OUTPUT
![image](https://github.com/Oviya24032K6/Windows-basic-commands-batchscript/assets/147139999/9f69d1f2-d258-4c0b-a96d-73e840262e65)






# RESULT:
The commands/batch files are executed successfully.
