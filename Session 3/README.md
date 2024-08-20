## Task 3 Submission Guidelines

1. Create a directory named task-3.

2. Inside the `task-3` directory, create a file named `solution.txt`.

3. In `solution.txt`, write the commands used to solve each step. **Do not include the output of the command.**

4. Do not leave blank lines between commands.

5. Upload the `task-3` directory to your tasks GitHub repository using Git on the CLI, **Tasks submitted through GitHub, using GUI will be rejected**.

6. Paste only the command used, don't paste the prompt alongside it

    
    [osc@osc ~]$ touch newFile # This is not accepted

    touch newFile # This is correct
    

7. Don't paste output of commands unless specified in the task

**Note:** 

- Ensure that the directory and file names are in **lowercase**. Names such as TASK-3, Task-3, task_3, Solution.txt, SOLUTION.TXT, or SoluTION.txt are not acceptable.

---


# Task 3

1. Create a new directory named `project_files` in your home directory.

2. Inside `project_files`, create three directories: `reports`, `logs`, and `data`.

3. Navigate to the `reports` directory and create two files: `report1.md` and `report2.md`.

4. Navigate to the `logs` directory and create four files: `system.log`, `error.log`, `file1.pdf`, and `file2.pdf`.

5. In the `data` directory, create a text file named `data.csv` and another named `info.txt`.

6. Use the `nano` text editor to add some random content to `report1.md`, `system.log`, and `data.csv`.

7. Archive all files in the `logs` directory into a **tar archive** named `logs_backup.tar`.

8. Move `logs_backup.tar` to the `project_files` directory.

9. Extract the `logs_backup.tar` archive back into the `logs` directory.

10. Find and list all files with the `.md` extension starting from the home directory `(~)`.

11. Search for all files ending with `.log` in the `project_files` directory.

12. Search for all files named `file1.pdf` in the `project_files` directory.

13. Search for all files with the `.pdf` extension in the `project_files` directory, regardless of case.

14. Search for all regular files (not directories) in the `logs` directory.

15. Create a symbolic link for `data.csv` named `link_data.csv` in the `project_files` directory.

16. Modify `link_data.csv` and verify if the changes are reflected in `data.csv`.

17. Delete the symbolic link `link_data.csv`.

18. Create a file named `summary.txt` in the `project_files` directory and redirect the output of `echo "Summary Start"` to it.

19. Append the current date and time to `summary.txt`.

20. Use a pipeline to count the number of lines in `summary.txt` and display it, appending the result to `summary.txt` with the `tee` command.

21. Count the number of words in `report1.md` and display it.

22. Count the number of characters in `system.log` and append the result to `summary.txt`.

23. Count the total number of files and directories in `project_files` and append the result to `summary.txt`.

24. Display the contents of `summary.txt`.

***Good Luck!😊***