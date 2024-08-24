# Task 5 Submission Guidelines

1. Inside your tasks repo, create a directory named `task-5`.
2. Download the file `info.txt` from this directory and put it inside `task-5`. **Do not edit it**.
3. Create a file called `solution.txt`. Here, write only the **two** commands you will use to solve the task.
4. During the task, you will create two files: `emails.txt` and `processes.txt`. Make sure to submit them as well.
5. Your task-5 directory should look like that after finishing the task.

   ```bash
   task-5/
   │
   ├── info.csv
   |
   ├── emails.txt
   |
   ├── processes.txt
   |
   ├── solution.txt
   ```

---

# Task 5 Steps

1. `info.csv` includes records which contain names, emails and age. Extract all **emails**, **sort** them alphabetically, **remove duplicates** and save the output in the file `emails.txt`. (No need to display anything)

   _Hint 1: Email format is `someone@something.something`._

   _Hint 2: Use piping to achieve this in one command_.

2. Find **all** the processes on your system (using `ps`) and **sort** them by the `CMD` column. Write only the **PID and CMD** of the previous output into `processes.txt`. (No need to display anything)

   _Hint 1: Refer to `man ps` and search for `sort` to find a `ps` option to help you._

   _Hint 2: Use piping to achieve this in one command_.

### Good luck! 🐧
