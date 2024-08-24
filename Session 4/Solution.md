# Task 4 Solution

1. **Create a new user named `newuser`.**

    ```bash
    sudo useradd newuser
    ```

2. **Create a new group named `newgroup`.**

    ```bash
    sudo groupadd newgroup
    ```

3. **Add `newuser` to `newgroup`.**

    ```bash
    sudo usermod -aG newgroup newuser
    ```

4. **Check the groups that `newuser` belongs to.**

    ```bash
    groups newuser
    ```

5. **Create a directory named `task_dir` in your home directory**

    ```bash
    mkdir ~/task_dir
    ```

6. **Change directory to `task_dir` and create a new file named `sample.txt`.**

    ```bash
    cd ~/task_dir
    touch sample.txt
    ```

7. **Change the permissions of `sample.txt`:**
    * Owner: read and write permissions
    * Group: read permissions
    * Others: no permissions

    ```bash
    chmod 640 sample.txt    
    ```
    OR

    ```bash
    chmod o=rw,g=r,o= sample.txt
    ```

8. **Change the ownership of `sample.txt` to `newuser`.**

    ```bash
    sudo chown newuser sample.txt
    ```

9. **Change the group ownership of `sample.txt` to `newgroup`.**

    ```bash
    sudo chgrp newgroup sample.txt
    ```
    OR
    ```bash
    sudo chown :newgroup sample.txt
    ```
    OR
    ```bash
    sudo chown newuser:newgroup sample.txt
    ```

10. **Delete the `newgroup` group.**

    ```bash
    sudo groupdel newgroup
    ```

11. **Delete the `newuser` account and its home directory.**

    ```bash
    sudo userdel -r newuser
    ```

12. **Update the package list on your system.**

    ```bash
    sudo apt update
    ```

13. **Install the `lolcat` package.**

    ```bash
    sudo apt install lolcat
    ```

14. **Print `"I Love OSC"` by piping the output to `lolcat`.**

    ```bash
    echo "I Love OSC" | lolcat
    ```

15. **Remove the `lolcat` package.**

    ```bash
    sudo apt remove lolcat
    ```