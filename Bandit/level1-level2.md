# Bandit Level 1 - level 2 

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

There was a file called `-`. I opened it using:

```bash
cat ./-
```

The file contained the password for **Level 1**.

> **Password:** FIND BY YOURSELF

### What I learned

This level helped me understand the basics of SSH and how to open files start with - . I also practiced using `ls` and `cat` to work with files in Linux.

**Tools/Commands:** `ssh`, `ls`, `cat`
