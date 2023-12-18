# Magikarp Ground Mission

## Overview
  Points: 30
  Category: General Skills

## Description
  Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `6d448c9c`.

## Solution
  On reading the description, I realized all we had to do was traverse along the differnt directories and files.
  On starting the instance, I used the `ls` command to look at the contents of the directory I was in. There I found two files, `1of3.flag.txt` and `instructions-to-2of3.txt`. As mentioned the first part of the flag was in the `1of3.flag.txt` and the instruction to the second one was in the other, both I accessed using the `cat` command.

  ![image](https://github.com/Mnj-ToTheTop/Pico_CTF/assets/153396359/419ecfe3-366a-4bf0-9a3d-ba8385ecdf76)

  The instruction asked me to access the root of all things. First, I figured out the directory I was presently in using the `pwd` command.

  ![image](https://github.com/Mnj-ToTheTop/Pico_CTF/assets/153396359/13c872d9-7275-4602-8d5b-1e4558da144c)

  To go the the root, I used `cd` command twice. Once, I reached the root which I confirmed by using the `pwd` command, I once again used `ls` command. 

  ![image](https://github.com/Mnj-ToTheTop/Pico_CTF/assets/153396359/fe9dd772-7fbb-4ff7-8e8b-21801b4f1a84)

I accessed the `2of3.flag.txt` and the next set of instructions using the `cat` command.

![image](https://github.com/Mnj-ToTheTop/Pico_CTF/assets/153396359/a6d16413-95c7-4553-94de-92ac185147a1)

Once, reaching the "home" using `cd ~` command. I accessed the list of the files using `ls` and was able to find the last `3of3.flag.txt` i.e. the last part of our flag.

![image](https://github.com/Mnj-ToTheTop/Pico_CTF/assets/153396359/a27da663-2f0a-4ab0-bedb-d44e1cd1b4ab)

![image](https://github.com/Mnj-ToTheTop/Pico_CTF/assets/153396359/5dbbdca2-1d44-41fa-aec7-3e5ae4fd9862)



