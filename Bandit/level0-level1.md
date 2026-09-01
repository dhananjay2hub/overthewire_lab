# Bandit Level 0 - level 1 

### Goal

Connect to the Bandit server using SSH and find the password for the next level.

### What I did

I connected to the server using:

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

After logging in, I used `ls` to see what files were available:

```bash
ls
```

There was a file called `readme`. I opened it using:

```bash
cat readme
```

The file contained the password for **Level 1**.

> **Password:** `[REDACTED]`

### What I learned

This level helped me understand the basics of SSH and how to specify a custom port. I also practiced using `ls` and `cat` to work with files in Linux.

**Tools/Commands:** `ssh`, `ls`, `cat`
