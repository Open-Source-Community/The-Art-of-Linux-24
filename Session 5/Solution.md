# Task 5 solution

1. `info.csv` includes records which contain names, emails and age. Extract all **emails**, **sort** them alphabetically, **remove duplicates** and save the output in the file `emails.txt`. (No need to display anything)

```bash
grep -o "[[:alnum:].]\+@[[:alnum:].]\+\.[[:alpha:]]\+" info.csv | sort | uniq > emails.txt
# alpha instead of alnum is fine
# forgetting the dot is not
# OR in this case, since the file is a csv
cut -d "," -f 2 info.csv | sort | uniq > emails.txt
```

2. Find **all** the processes on your system (using `ps`) and **sort** them by the `CMD` column. Write the previous output into `processes.txt`. (No need to display anything)

```bash
ps -e --sort=command > processes.txt
```
