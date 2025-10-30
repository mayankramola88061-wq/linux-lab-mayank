# Linux Lab Report

## Experiment 1: Introduction to Ubuntu Operating System

**Aim:**  
To understand the basic structure and components of the Ubuntu Linux operating system.

**Apparatus Required:**  
Ubuntu Operating System installed on a computer or virtual machine.

**Theory:**  
Ubuntu is a popular Linux-based operating system. It provides a terminal interface that allows users to interact with the system using commands.  
Understanding the desktop environment, terminal, and file system structure is essential before learning advanced Linux concepts.

**Procedure:**
1. Start the Ubuntu system.  
2. Explore the desktop and launcher icons.  
3. Open the terminal using **Ctrl + Alt + T**.  
4. Run the command `pwd` to check the current directory.  
5. Observe the directory structure under `/home/username/`.


**Result:**  
Successfully explored the Ubuntu interface and learned basic terminal navigation.

**Conclusion:**  
Gained basic understanding of the Ubuntu environment and its command-line interface# Linux Lab Report# Linux Lab Report
<img width="1470" height="956" alt="Screenshot 2025-10-07 at 3 15 50 PM" src="https://github.com/user-attachments/assets/a84de0a8-69fd-42ce-bdbd-de2a64806a2e" />

<img width="1470" height="956" alt="Screenshot 2025-10-07 at 3 24 13 PM" src="https://github.com/user-attachments/assets/b53aafee-8c10-45e0-b0cf-36f1469f50c6" />
<img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/a62cc353-4fa4-4d15-ad4a-846aa22431cb" />
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 EXPERIMENT 2: BASIC LINUX COMMANDS


Aim:
To study and execute basic Linux commands for file and directory management.

Apparatus Required:
Ubuntu Operating System

Theory:
Linux commands are used to interact with the system and perform operations such as listing files, creating directories, copying, moving, and removing files.
Understanding these commands helps in efficiently managing files and navigating the Linux filesystem.

Procedure:
	1.	Open the Terminal using Ctrl + Alt + T.
	2.	Use pwd to display the present working directory.
	3.	Use ls to list the files and directories.
	4.	Use mkdir test to create a directory named test.
	5.	Use cd test to move into the test directory.
	6.	Use touch sample.txt to create an empty file.
	7.	Use cp sample.txt copy.txt to copy the file.
	8.	Use mv copy.txt moved.txt to rename the copied file.
	9.	Use rm moved.txt to delete the file.
	10.	Use cd .. to return to the parent directory and rmdir test to remove the empty directory.

Result:
Successfully executed and verified the output of basic Linux commands for file and directory handling.
Conclusion:
Learned to manage files and directories using fundamental Linux commands.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/15397d37-f623-4920-8fa7-ae09cb172678" />

⸻

Experiment 3: File Permissions in Linux

Aim:
To understand and modify file permissions using chmod, chown, and groups commands in Linux.

Apparatus Required:
Ubuntu Linux operating system.

Theory:
In Linux, each file and directory has permissions that control who can read, write, or execute them.
These permissions are represented by three categories:
	•	User (u): Owner of the file
	•	Group (g): Users in the same group
	•	Others (o): Everyone else

Permissions can be changed using the chmod command, and ownership can be viewed or changed using chown.

Procedure:
	1.	Open the terminal using Ctrl + Alt + T.
	2.	Create a directory using mkdir perm_test.
	3.	Move into it using cd perm_test.
	4.	Create a file using touch demo.txt.
	5.	Check permissions using ls -l demo.txt.
	6.	Change permissions using chmod 600 demo.txt.
	7.	Add execute permission to the user using chmod u+x demo.txt.
	8.	Verify new permissions with ls -l demo.txt.
	9.	View group information using groups.
	10.	Return to the parent directory using cd .. and delete the directory using rm -r perm_test.

Output:
<img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/d9c8d2c5-e58f-4838-881d-0b267b5b7874" />

Result:
Successfully learned how to set, view, and modify file permissions and ownership in Linux.

Conclusion:
Gained understanding of Linux file permission system and how to manage access control using chmod and related commands.

⸻
Experiment 4: User and Group Management in Linux

Aim:
To learn how to create, manage, and delete users and groups in the Linux operating system.

Apparatus Required:
Ubuntu Linux operating system.

Theory:
Linux is a multi-user system, meaning multiple users can access it simultaneously.
User and group management is essential for maintaining security and organization.
	•	useradd / adduser — Create a new user.
	•	passwd — Set or change the password for a user.
	•	groupadd — Create a new group.
	•	usermod — Modify a user’s information.
	•	deluser / userdel — Delete a user.
	•	groups / id — Display user and group information.
<img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/bf66125c-0476-4616-ace7-7ba4b6c738bb" />
---------------------------------------------------------------------------------------------------------------------
Experiment 5: File Ownership and Permissions in Linux

Aim:
To study and modify file ownership and permissions in Linux.

Apparatus Required:
Ubuntu Linux Operating System

Theory:
In Linux, every file and directory has three types of permissions — read (r), write (w), and execute (x) — for three categories of users:
	•	Owner
	•	Group
	•	Others

The chmod, chown, and chgrp commands are used to modify file permissions and ownership.

