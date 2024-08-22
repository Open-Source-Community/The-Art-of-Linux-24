# Task 3 Solution

1. **Create a new directory named `project_files` in your home directory:**

    ```bash
    mkdir ~/project_files
    ```

2. **Inside `project_files`, create three directories: `reports`, `logs`, and `data`:**

    ```bash
    mkdir ~/project_files/reports ~/project_files/logs ~/project_files/data
    ```

3. **Navigate to the `reports` directory and create two files: `report1.md` and `report2.md`:**

    ```bash
    touch ~/project_files/reports/report1.md ~/project_files/reports/report2.md
    ```

4. **Navigate to the `logs` directory and create four files: `system.log`, `error.log`, `file1.pdf`, and `file2.pdf`:**

    ```bash
    touch ~/project_files/logs/system.log ~/project_files/logs/error.log ~/project_files/logs/file1.pdf ~/project_files/logs/file2.pdf
    ```

5. **In the `data` directory, create a text file named `data.csv` and another named `info.txt`:**

    ```bash
    touch ~/project_files/data/data.csv ~/project_files/data/info.txt
    ```

6. **Use the `nano` text editor to add some random content to `report1.md`, `system.log`, and `data.csv`:**

    ```bash
    nano ~/project_files/reports/report1.md
    nano ~/project_files/logs/system.log
    nano ~/project_files/data/data.csv
    ```

7. **Archive all files in the `logs` directory into a **tar archive** named `logs_backup.tar`:**

    ```bash
    tar -cvf ~/project_files/logs_backup.tar ~/project_files/logs/file1.pdf ~/project_files/logs/file2.pdf ~/project_files/logs/system.log  ~/project_files/logs/error.log
    ```
    OR

    ```bash
    cd ~/project_files/logs/
    tar -cvf logs_backup.tar *
    ```

8. **Move `logs_backup.tar` to the `project_files` directory:**

    ```bash
    mv ~/project_files/logs/logs_backup.tar ~/project_files/
    ```

9. **Extract the `logs_backup.tar` archive back into the `logs` directory:**

    ```bash
    tar -xf ~/project_files/logs_backup.tar -C ~/project_files/logs
    ```

10. **Find and list all files with the `.md` extension starting from the home directory `(~)` using the `find` command:**

    ```bash
    find ~ -name "*.md"
    ```

11. **Search for all files ending with `.log` in the `project_files` directory**

    ```bash
    find ~/project_files -name "*.log"
    ```

12. **Search for all files named `file1.pdf` in the `project_files` directory.**

    ```bash
    find ~/project_files -name "file1.pdf"
    ```

13. **Search for all files with the `.pdf` extension in the `project_files` directory, ignoring case.**

    ```bash
    find ~/project_files -iname "*.pdf"
    ```

14. **Search for all regular files (not directories) in the `logs` directory.**

    ```bash
    find ~/project_files/logs -type f
    ```

15. **Create a symbolic link for `data.csv` named `link_data.csv` in the `project_files` directory:**

    ```bash
    ln -s ~/project_files/data/data.csv ~/project_files/link_data.csv
    ```

16. **Modify `link_data.csv` and verify if the changes are reflected in `data.csv`:**

    ```bash
    nano ~/project_files/link_data.csv

    cat ~/project_files/data/data.csv
    ```

17. **Delete the symbolic link `link_data.csv`:**

    ```bash
    rm ~/project_files/link_data.csv
    ```

18. **Create a file named `summary.txt` in the `project_files` directory and redirect the output of `echo "Summary Start"` to it:**

    ```bash
    echo "Summary Start" > ~/project_files/summary.txt
    ```

19. **Append the current date and time to `summary.txt`:**

    ```bash
    date >> ~/project_files/summary.txt
    ```

20. **Use a pipeline to count the number of lines in `summary.txt` and display it, appending the result to `summary.txt` with the `tee` command:**

    ```bash
    wc -l ~/project_files/summary.txt | tee -a ~/project_files/summary.txt
    ```

21. **Count the number of words in `report1.md` and display it:**

    ```bash
    wc -w ~/project_files/reports/report1.md
    ```

22. **Count the number of characters in `system.log` and append the result to `summary.txt`:**

    ```bash
    wc -c ~/project_files/logs/system.log >> ~/project_files/summary.txt
    ```

23. **Count the total number of files and directories in `project_files` and append the result to `summary.txt`:**

    ```bash
    find ~/project_files | wc -l >> ~/project_files/summary.txt
    ```

24. **Display the contents of `summary.txt`:**

    ```bash
    cat ~/project_files/summary.txt
    ```
