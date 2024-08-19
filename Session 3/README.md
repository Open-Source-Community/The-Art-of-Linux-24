## Task 3 Submission Guidelines

1. Create a directory named task-3.

2. Inside the `task-3` directory, create a file named `solution.txt`.

3. In `solution.txt`, write the commands used to solve each step. Do not include the output of the command.

4. Do not leave blank lines between commands.

5. Upload the `task-3` directory to your tasks GitHub repository using Git on the CLI, **Tasks submitted through GitHub, using GUI will be rejected**.

6. Paste only the command used, don't paste the prompt alongside it

    
    [osc@osc ~]$ touch newFile # This is not accepted

    touch newFile # This is correct
    

7. Don't paste output of commands unless specified in the task

**Note:** 
Ensure that the directory and file names are in lowercase. Names such as task-3, task-3, task-3, Solution.txt, SOLUTION.TXT, or SoluTION.txt are not acceptable.

---


# Task 3

1. Create a new directory named `project_files` in your home directory.

2. Inside `project_files`, create three directories: `reports`, `logs`, and `data`.

3. Navigate to the `reports` directory and create two files: `report1.md` and `report2.md`.

4. Navigate to the `logs` directory and create two files: `system.log` , `error.log`, `file1.tmp` and `file2.tmp`.

5. In the `data` directory, create a text file named `data.csv` and another named `info.txt`.

6. Use the `nano` text editor to add some random content to `report1.md`, `system.log`, and `data.csv`.

7. Compress all files in the `logs` directory into a **tar archive** named `logs_backup.tar`.

8. Move `logs_backup.tar` to the `project_files` directory.

9. Find and list all files with the `.md` extension starting from the home directory `(~)`.

10. Search for all files ending with `.log` in the `project_files` directory.

11. Delete all files in the `logs` directory ending with `.tmp`.

12. Create a symbolic link for `data.csv` named `link_data.csv` in the `project_files` directory.

13. Modify `link_data.csv` and verify if the changes are reflected in `data.csv`.

14. Delete the symbolic link `link_data.csv`.

15. Create a file named `summary.txt` in the `project_files` directory and redirect the output of `echo "Summary Start"` to it.

16. Append the current date and time to `summary.txt`.

17. Use a pipeline to count the number of lines in `summary.txt` and display it, appending the result to `summary.txt` with the `tee` command.

18. Count the number of words in `report1.md` and display it.

19. Count the number of characters in `system.log` and append the result to `summary.txt`.

20. Count the total number of files and directories in `project_files` and append the result to `summary.txt`.

21. Display the contents of `summary.txt`.

***Good Luck!😊***
