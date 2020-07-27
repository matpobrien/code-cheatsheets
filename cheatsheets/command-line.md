# Command Line

## Filepaths

| Command        | Meaning                                                        |
| -------------- | -------------------------------------------------------------- |
| `.`            | Current Working Directory.                                     |
| `..`           | Parent Directory.                                              |
| `~`            | User Home directory.                                           |
| `img/logo.png` | Relative path: resolved relative to current working directory. |
| `usr/bin/bash` | Absolute path: resolved relative to the file system root.      |

## Browsing the file system

| Command      | Meaning                                                                                |
| ------------ | -------------------------------------------------------------------------------------- |
| `cat <file>` | Catinate `<file>` to stdout, interpreted as plain text.                                |
| `cd`         | Change working directory to home directory, equivalent to `cd ~`.                      |
| `cd <path>`  | Change directory to `<path>`.                                                          |
| `ls`         | List files in working directory.                                                       |
| `ls -a`      | List **all** with hidden files (starting with a .).                                    |
| `ls -l`      | List files in **long format**, including permissions, owner, change date, size, et al. |
| `ls <path>`  | List files in `<path>`.                                                                |
| `pwd`        | Print working directory.                                                               |
| `hexdump`    | Print bytes in `<file>` using hexadecimal digits.                                      |
