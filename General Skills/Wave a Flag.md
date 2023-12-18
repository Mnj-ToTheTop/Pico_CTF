# Wave a Flag

## Overview
  Points: 10
  Category: General Skills
  
## Description
  Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information…

## Solution
  Just like the "Obedoent Cat" problem we’ll download the provided file using `wget` command. 
  To run the file warm we’ll need to first make it into an executable file. 
  To do that, we’ll be using the `chmod +x warm` command. 
  Once the executable file is created we’ll execute the file using `./warm`.

  ![image](https://github.com/Mnj-ToTheTop/Pico_CTF/assets/153396359/61a9ffbc-b43e-4f82-973e-c762a14a0371)

  As we can see we’ll have to pass the `-h` with the `./warm` to know the working of the program given to us. 
  `-h` stand for the "help" menu which is used to show all the information regarding a particular tool.
  Since the description of the problem includes tools we'll be using `-h` to find information on the program.
