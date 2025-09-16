# CTF Write-up: Bandit Level 0 → 1

📝 Goal: Log in to the remote server using SSH and find the password for the next level, which is in a file named readme.

## My Attack Vector:

>I had no idea what SSH was at first 😅, so my first step was Googling:

    “What is SSH and how to use it on Linux?”

>I found that SSH is like a secure way to remotely log in to another computer.

>Got the command and, with a quick password entry, I was in! 

>Tried the exact command given in the instructions:

    ssh bandit0@bandit.labs.overthewire.org -p 2220
Typed the password bandit0 and — boom! — I was inside my first remote shell.

## Commands Used:

    ls            # Check what files are in the current directory
    cat readme    # Display the contents of the readme file


## Password:

    ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
    
## What I Learned

>How to use ssh for the first time → ssh user@host -p port

>That CTFs expect me to search and learn on my own — that’s part of the fun.

## Reflection:

>Felt WOW finally to “hack into” my first server — even though it was just SSH, it felt like I entered a secret world 🔥
