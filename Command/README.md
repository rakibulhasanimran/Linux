The Linux command is a utility of the Linux operating system. All basic and advanced tasks can be done by executing commands. The commands are executed on the **Linux terminal**. The terminal is a command-line interface to interact with the system, which is similar to the command prompt in the Windows OS. Commands in Linux are **case-sensitive**.

Linux terminal is a user-friendly terminal as it provides various support options. To open the Linux terminal, press `CTRL + ALT + T` keys together, and execute a command by pressing the `ENTER` key.

In this topic, we will discuss some most frequently used Linux commands with their examples. These commands are very useful for a beginner and professional both. We have divided these commands into following sections so that you can easily identify their usage:

- Linux Directory Commands
- Linux File Commands
- Linux File Content Commands
- Linux User Commands
- Linux Filter Commands
- Linux Utility Commands
- Linux Networking Command

### Linux Directory Commands
**1. `pwd` Command:** The `pwd` command in Linux stands for "print working directory." It is used to display the current working directory, which is the directory in the file system where a user is currently located.

*Syntax:*
```bash
pwd
```

*Example:*
```bash
pwd
```

This command will print the full path of the current working directory to the terminal.

The `pwd` command is useful when you want to know your current location in the file system, especially if you are navigating between directories and need to confirm your present working directory.


**2. `mkdir` Command:** The `mkdir` command is used to create a new directory under any directory.  It stands for "make directory."

*Syntax:*
```bash
mkdir [options] <directory_name>
```

- `options`: Additional parameters to customize the behavior of the mkdir command.
- `<directory_name>`: The name of the directory to be created.

*Example:*
```bash
mkdir new_directory
```

In this example, the `mkdir` command is used to create a new directory named "new_directory" in the current working directory. You can replace "new_directory" with the desired name of the directory you want to create.

The `mkdir` command in Linux has a few options to customize its behavior. Here are the common options:

- `-m`, `--mode=MODE`: Set the file permission bits for the newly created directory. The mode is specified in octal representation. *For example:*
```bash
mkdir -m 755 new_directory
```
- `-p`, `--parents`: Create parent directories as needed. If a parent directory in the given path does not exist, it will be created. *For example:*
```bash
mkdir -p parent_directory/new_directory
```
- `--help`: Display help information about the mkdir command.
- `--version`: Display the version information of the mkdir command.

These options allow users to set permissions, create parent directories, and access information about the `mkdir` command. You can use them individually or combine them as needed.
    

**3. `rmdir` Command:** The `rmdir` command is used to delete a directory. It stands for "remove directory."

*Syntax:*
```bash
rmdir [options] <directory_name>
```

- `options`: Additional parameters to customize the behavior of the rmdir command.
- `<directory_name>`: The name of the directory to be removed.

*Example:*
```bash
rmdir empty_directory
```

In this example, the `rmdir` command is used to remove the directory named "empty_directory" from the current working directory. It's important to note that the directory must be empty for `rmdir` to successfully remove it.

The rmdir command in Linux is relatively straightforward and doesn't have many options. It is primarily used to remove empty directories. Here's the one common option:

- `--ignore-fail-on-non-empty`: Ignore failure when attempting to remove a non-empty directory. This option allows `rmdir` to proceed with the removal even if the specified directory is not empty. *For example:*
```bash
rmdir --ignore-fail-on-non-empty  non_empty_directory
```

> Please note that the `--ignore-fail-on-non-empty` option is not available in all versions of the `rmdir` command. Depending on your system, you may need to check the available options using the command `rmdir --help` or `man rmdir` for more detailed information.



**4. `ls` Command:** The `ls` command is used to display a list of content of a directory.

*Syntax:*
```bash
ls
```

The command can be enhanced by incorporating options for a more tailored display:

*Enhanced Syntax:*
```bash
ls <option>
```

In this syntax, `<option>` is a placeholder to be substituted with a specific option for customizing the behavior of the `ls` command. This flexibility allows users to customize the presentation of directory content by selecting specific options according to their preferences or requirements.

The available options of the `ls` command include:

- `-l`: Display detailed information about files and directories.
    
- `-a`: List all entries, including hidden files.
- `-h`: Provide human-readable file sizes.
- `-R`: Recursively list subdirectories.
- `-t`: Sort files by modification time.
- `-S`: Sort files by size.
- `-r`: Reverse the order of the sort.
- `-u`: Display files by access time.
- `-d`: List directories themselves, not their contents.
- `--color`: Colorize the output for better visual distinction.
- `-1`: Display each entry on a new line.

These options enable users to customize the appearance and details of the directory listing based on their specific requirements.

**5. cd Command:** The `cd` command is used to change the current directory.

*Syntax:*
```bash
cd <directory name>
```

### Linux File Commands

**1. `touch` Command:** The `touch` command is used to create empty files.

*Syntax:*
```bash
touch <file name>
```

We can create multiple empty files by executing it once.

*Syntax:*
```bash
touch <file1>  <file2> ....  
```

**2. `cat` Command:** The `cat` command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

*Syntax:*
```bash
cat [OPTION]... [FILE]..
```

To create a file, execute it as follows:

*Syntax:*
```bash
cat > <file name>  
// Enter file content  
```

Press "CTRL+ D" keys to save the file. To display the content of the file, execute it as follows:

*Syntax:*
```bash
cat <file name>  
```


**3. rm Command:** The `rm` command is used to remove a file.

*Syntax:*
```bash
rm <file name>  
```

**4. `cp` Command:** The `cp` command is used to copy a file or directory.

*Syntax:*
To copy in the same directory:
```bash
cp <existing file name> <new file name>
```

To copy in a different directory:
```bash

```


**5. `mv` Command:** The `mv` command is used to move a file or a directory form one location to another location.

*Syntax:*
```bash
mv <file name> <directory path>
```





### Linux File Content Commands
### Linux User Commands
### Linux Filter Commands
### Linux Utility Commands
### Linux Networking Command













