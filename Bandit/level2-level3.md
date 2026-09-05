# Bandit Level 2 - level 3

### Goal

The password for the next level is stored in a file called - located in the home directory

### What I did

I connected to the server using:

```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
```

After logging in, I used `ls` to see what files were available:

```bash
ls
```

There was a file called `--spaces in this filename--`. I opened it using:

```bash
cat ./"--spaces in this filename--"
```

The file contained the password for **Level 1**.

> **Password:** FIND BY YOURSELF

### What I learned

This level helped me understand the basics of SSH and how to open files start with - . I also practiced using `ls` and `cat` to work with files in Linux.

**Tools/Commands:** `ssh`, `ls`, `cat`
