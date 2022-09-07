# ME 701 -- Homework 1 -- Devin Burgett

## Instructions

Your solution should be an update to this `README.md` file that will be
committed back to your repository created when you clicked the HW 1 link.

## Problem 1 -- Open-Source Software

### Statement

Think of the things you do routinely on a computer that require
specific software packages.  Find an
open-source solution from the software repository
for one of these activities and tell me about it in 100 words or less.
For example, I used to do lots of audio recording when I was in
high school (not *that* long ago) and used special (and
pretty expensive) tools like
Cakewalk Sonar.  Since then, I've found an
open-source package for doing multitrack
recording called Ardour that doesn't have all the bells and
whistles but, because I can program in C++ and the
source code is available, I could, in theory,
create any such whistles I need.  **Note**: You may not
describe anything already discussed in class (e.g., the LibreOffice suite
or Octave).

### Solution

I am interested in 3d printing and need to model parts often. An open source tool that I found to do organic modeling such as rounded objects and complex ellipsoids is blender. It is generally used to create artistic 3d models but, is a very versatile modeling program which runs on python scripts.


## Problem 3 -- Your CPU

### Statement
```bash
lscpu #Displays information about the computer including processor speed, number of cores, sockets, Architecture, Model Name, etc.
```

### Solution

To display CPU information, I used the following command:

```bash
ls -al # <--- that's not right, but it shows you how to include
       #      code in Markdown!
```

## Problem 4 -- Resource Hogs

### Statement

Figure out how to list the programs that use the most
amount of (1) processing and (2) memory.  Describe your command(s)
in your writeup.

### Solution
```bash
ps aux --sort -%cpu #The ps aux command shows running processes on Linux, using the -sort modifier it lists processes in descending order of cpu usage

ps aux --sort -%mem #This time I sort by the memory usage in descending order
```

## Problem 5 -- `bash`

### Statement

Where is `bash` located on your Linux system?  And what version of
`bash` are you using?  Make sure to provide any commands you use to
determine this information.

### Solution
```bash
which bash #Returns the path to the bash executable, in my case usr/bin/bash

echo "{BASH_VERSION}" #Responds with the version of bash by calling the variable where the release is named, mine is version 5.0.17(1)
```
