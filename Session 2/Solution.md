# Task 2 solution

1. `git config --global user.name "name"`

2. `git config --global user.email "email"`

3. `git clone <url>`

4. `cd <repo-name>`

5. `mkdir task-2`

6. `cd task-2`

7. `touch greeting.txt`

8. `nano greeting.txt`

    - (OR `echo "Hello world" >> greeting.txt`)

    - (OR `echo "Hello world" > greeting.txt`)

9. `git add .` (OR `git add greeting.txt` OR `git add *.txt`)

10. `git commit -m "Added greeting"` 

    - (OR `git commit and write message using editor`)

11. `git branch intro && git checkout intro`

    - (OR `git checkout -b intro`)

    - (OR `git switch -c intro`)

12. `nano greeting.txt`

    - (OR `echo "I love Git" >> greeting.txt`)

13. `git add .` (OR `git add greeting.txt` OR `git add *.txt`)

14. `git commit -m "Added I love Git"`

    - (OR `git commit` and write `"Added I love Git"` using editor)

15. `git checkout main`

16. `git merge intro`

17. `git tag -a v1`

18. `git push -u origin main` (OR `git push`)