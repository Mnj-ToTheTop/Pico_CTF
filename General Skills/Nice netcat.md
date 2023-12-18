# Nice netcat...

## Overview
  15 Points; General Skills.

## Description
  There is a nice program that you can talk to by using this command in a shell: `$ nc mercury.picoctf.net 43239`, but it doesn't speak English...

## Solution
  I first connected to the program provided. On connecting, a bunch of numbers were displayed. As per the description, then we have to convert it into English     i.e. characters.
  So I used an ASCII to character converter online and converted the numbers given to me, which was the flag.

  ![image](https://github.com/Mnj-ToTheTop/Pico_CTF/assets/153396359/097a198b-dd83-4417-8774-2e46793881ca)

  We could also create a python file to convert all the ASCII numbers to characters.

  ![image](https://github.com/Mnj-ToTheTop/Pico_CTF/assets/153396359/7f6bc864-c547-4d90-aa1a-6b21b7bb0f43)
  ![image](https://github.com/Mnj-ToTheTop/Pico_CTF/assets/153396359/9e16c4b3-5892-4396-9617-58e8f13598c7)
