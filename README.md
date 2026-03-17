# linux_commands

1.pwd 
    pwd stands for Present Working Directory. It is a command used to display the current directory path where the user is working.

2.ls
    ls is a command used to list the files and directories in the current directory.

3.cd
    cd stands for Change Directory. It is used to move from one directory to another.

4.mkdir
    mkdir stands for Make Directory. It is used to create a new directory (folder).

5.rm -rf
    rm -rf is used to remove files and directories forcefully, including all contents inside a directory.

6.ps -ef
    ps -ef is used to display all running processes in the system.

7.top
    The top command is used to monitor system processes in real time. It shows information such as CPU usage, memory usage, process ID (PID), and running tasks. It continuously updates the list of active processes.

8.df -h
    The df -h command displays the available and used disk space of file systems. The -h option shows the output in a human-readable format (KB, MB, GB), making it easier to understand.

9.history
    The history command shows a list of all commands that have been executed in the terminal. It helps users quickly view, reuse, or repeat past commands.

10.uptime
    The uptime command displays how long the system has been running since the last boot. It also shows the current time, number of users, and system load averages.


1. Create a directory called `project-files`
mkdir project-files

Explanation:
Creates a new directory (folder) named project-files.

2. Navigate into the project-files directory
cd project-files

Explanation:
Moves into the project-files directory.

3. Create a file called notes.txt using vi
vi notes.txt

Explanation:
Opens the vi editor to create and edit the file notes.txt.

4. Display the contents of notes.txt
cat notes.txt

Explanation:
Displays the contents of the file in the terminal.

5. Copy notes.txt to backup.txt
cp notes.txt backup.txt

Explanation:
Creates a copy of notes.txt and names it backup.txt.

6. Show the first 100 lines of logs.txt
head -n 100 logs.txt

Explanation:
Displays the first 100 lines of the file.

7. Show the last 100 lines of logs.txt
tail -n 100 logs.txt

Explanation:
Displays the last 100 lines of the file.

8. Check the disk storage usage of the server
df -h

Explanation:
Shows disk usage in a human-readable format (KB, MB, GB).

9. Check the running processes in the system
ps -ef

Explanation:
Displays all running processes with full details.

10. Delete a file called temp.txt
rm temp.txt

Explanation:
Deletes the file temp.txt.

## 📌 SECTION 3 – Concept Questions

### 1. What is the difference between `>` and `>>` in Linux?

- `>` → Overwrites the file  
- `>>` → Appends to the file  

**Explanation:**  
The `>` operator replaces the existing content of a file, while `>>` adds new content to the end without deleting existing data.

---

### 2. What is the purpose of the `kill -9` command?

**Answer:**  
The `kill -9` command is used to forcefully terminate a process.

**Explanation:**  
It sends the SIGKILL signal to a process, which immediately stops it without allowing cleanup. It is used when a process does not respond to normal termination commands.

---

### 3. What is the difference between `rm` and `rmdir`?

- `rm` → Deletes files (and directories with options like `-r`)  
- `rmdir` → Deletes only empty directories  

**Explanation:**  
`rm` is more powerful and can remove files and non-empty directories, while `rmdir` works only if the directory is empty.

---

### 4. What information does the `netstat -tulpn` command provide?

**Answer:**  
It shows active network connections and listening ports.

**Explanation:**  
- `-t` → TCP connections  
- `-u` → UDP connections  
- `-l` → Listening ports  
- `-p` → Process ID (PID)  
- `-n` → Numerical addresses  

It helps identify which services are running on which ports.

---

### 5. What is the purpose of the `ping` command?

**Answer:**  
The `ping` command is used to check network connectivity between two systems.

**Explanation:**  
It sends packets to a target server and measures the response time, helping to verify if the host is reachable and how fast the connection is.

---

## ✅ Summary
- `>` overwrite, `>>` append  
- `kill -9` force stop process  
- `rm` remove files, `rmdir` empty folders  
- `netstat -tulpn` check ports & processes  
- `ping` test network connectivity  

## 📌 SECTION 4 – Scenario Based Questions

### 1. You want to check the current working directory. Which command will you use?
pwd

Explanation:
Displays the current working directory path.

2. You want to create a directory called devops inside the home directory. Write the command.
mkdir ~/devops

Explanation:
Creates a directory named devops inside the user's home directory.

3. You want to check which process is using high CPU in the system. Which command will help?
top

Explanation:
Displays running processes in real time along with CPU and memory usage.

4. You want to check whether your server can connect to google.com. Which command will you use?
ping google.com

Explanation:
Checks network connectivity and response time to google.com.

5. You want to view the last 50 lines of a log file called application.log. Write the command.
tail -n 50 application.log

Explanation:
Displays the last 50 lines of the specified log file.