# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**

<img width="329" height="476" alt="image" src="https://github.com/user-attachments/assets/21a2cd8a-493e-4939-bbd0-b890963b30fc" />

### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

<img width="306" height="62" alt="image" src="https://github.com/user-attachments/assets/425efc39-3137-4151-8123-06b8fc5e6f08" />

### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

<img width="311" height="82" alt="image" src="https://github.com/user-attachments/assets/d2c0bd46-5f9b-473f-9847-8b2ba3290f8b" />

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

<img width="339" height="90" alt="image" src="https://github.com/user-attachments/assets/3fc9ef31-f105-481c-b0ca-8b93f9289040" />

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

<img width="360" height="140" alt="image" src="https://github.com/user-attachments/assets/5abfd56b-60f5-45b7-a334-70fe2f4af532" />


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**

<img width="333" height="160" alt="image" src="https://github.com/user-attachments/assets/680eb465-5b5f-417a-85d7-290b8d827184" />

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

<img width="324" height="54" alt="image" src="https://github.com/user-attachments/assets/db75293a-5412-4728-b57c-85d3c9754030" />

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**

<img width="570" height="209" alt="image" src="https://github.com/user-attachments/assets/375d34ee-9366-4ebb-a7fc-c932af2c1a34" />


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

<img width="741" height="150" alt="image" src="https://github.com/user-attachments/assets/b056c921-f3cc-4997-941e-57757f6aad95" />


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

<img width="322" height="43" alt="image" src="https://github.com/user-attachments/assets/b80ee917-28f4-4114-851f-2dee50eae8d9" />


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

<img width="400" height="359" alt="image" src="https://github.com/user-attachments/assets/57892ce8-380c-42c5-a1d1-4dc1115126db" />


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**

<img width="325" height="210" alt="image" src="https://github.com/user-attachments/assets/e19fd556-0926-4439-9ae8-2b8328e5de5c" />


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

<img width="320" height="216" alt="image" src="https://github.com/user-attachments/assets/a1bfcd51-5ebd-4e91-bc00-bd58dfc67570" />


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**

<img width="605" height="64" alt="image" src="https://github.com/user-attachments/assets/5cbecde3-6887-4bd2-834d-563addb6c5dc" />


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

<img width="344" height="74" alt="image" src="https://github.com/user-attachments/assets/285bc57d-5f1d-4819-affa-d95511b9047f" />

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**

<img width="327" height="64" alt="image" src="https://github.com/user-attachments/assets/2240cd67-0b1b-4f9b-a212-59a97a396cca" />


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**

<img width="439" height="229" alt="image" src="https://github.com/user-attachments/assets/dfc6f03c-8be3-4c1e-b775-ddc9f44f15dd" />


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**

<img width="453" height="274" alt="image" src="https://github.com/user-attachments/assets/abacfd01-0c09-4d49-ba14-6eb95001ad1b" />


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**

<img width="458" height="183" alt="image" src="https://github.com/user-attachments/assets/bbfcffda-87ba-4044-b0ed-e24966b7ddd9" />

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

<img width="652" height="145" alt="image" src="https://github.com/user-attachments/assets/448d15bb-9ea1-4996-a40b-727e2b5c92e4" />


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

<img width="940" height="630" alt="image" src="https://github.com/user-attachments/assets/f69b702d-e6da-4d37-b412-3deeeeb65df5" />


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**

<img width="459" height="120" alt="image" src="https://github.com/user-attachments/assets/88474bb2-8e57-4349-8e51-ce1c8142ac5c" />


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

<img width="548" height="338" alt="image" src="https://github.com/user-attachments/assets/2fa8299f-659b-4188-8fb2-8acbff69921d" />


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**

<img width="562" height="151" alt="image" src="https://github.com/user-attachments/assets/f366b4ea-4b07-45e7-a3de-63720b8d56ee" />


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**

<img width="407" height="227" alt="image" src="https://github.com/user-attachments/assets/0359fb5b-633a-4953-9aa2-cab09f1a5f0b" />


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**

<img width="438" height="257" alt="image" src="https://github.com/user-attachments/assets/0f0ea54e-ef12-442f-a4fb-a376ee96469e" />


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

<img width="388" height="101" alt="image" src="https://github.com/user-attachments/assets/4ce9342c-a858-4ace-870b-9320f655277d" />


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

<img width="471" height="71" alt="image" src="https://github.com/user-attachments/assets/4f920a17-8ebc-4a11-a312-c0041425b7e3" />


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

<img width="754" height="392" alt="image" src="https://github.com/user-attachments/assets/a56785fc-d118-4a2f-97a3-a51509436d10" />


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**

<img width="408" height="180" alt="image" src="https://github.com/user-attachments/assets/c2a91d5b-b05e-44be-bdbd-49a04e6800ee" />


## Result

Oracle VirtualBox was installed successfully, Kali Linux was configured successfully, and basic Linux commands were executed successfully.
