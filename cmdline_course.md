---
layout: default
---
# Overall introduction to Command Line Tools for Linguistics

This course is designed for beginners or the students who have little experience with the command line before. Through this course, you will build a foundation in command line tools and learn jow to navigate file system, deal with text using tools like "grep" and "sed", also will gain knowledge in manage remote servers, how to use Git and Githhub. Prepare youself with useful tools in future study and work.

# Week1

## What I've learned

During the first week, I set up my local command-line environment and learned some basic command, for example, I leaned how to make new directories and how to change it, I also learned useful tools like wget which can help me download files from internet quickly, also how to view text files using 'less' and how to check and modify files.

> _Reflection:_ I found that using terminal is a effective way to manage files.  

## Example from week1: 

```bash
wget https://the file you want to download online.com
```
#wget command demonstrateds how to download contents from internet using terminal.

# Week2

## What I've learned

During the second week, I learned character encoding and converting, we also did couple practice like counting lines, transforming uppercase to lowercase, sorting and removing lines.

> _Reflection:_ The founctions I learned this week is highly relevant for linaguistic research and some field work tasks.

## Example from week2:

```bash
grep "^[A-Z]" somefile.txt
```
#grep is used to search sepecific patterns in a target file.

# Week3
## What I've learned

During this week, I learned how to write simple bash scripts, and use "if" statement to control script, I also learned how to view with "echo", how to modify with "export" and more useful thing is I learned how to install software using "brew".

> _Reflection:_ Using Python virtual environments is a new thing to me and I feel like it a wonderful way to prevent package conflicts.

## Example from week3:

```bash
if [something]; then
   echo "anything"
else
   echo "nothing"
fi
```
#if and else statement can be used for conditional logic while echo for outputting text to the terminal.

# Week4
## What I've learned

This week introduced romote servers, I learned how to biled remote connections to servers and run command in the background. Another interesting learning this week was Git and Github. I tried to set up my own repositories, committed changes, track my code history and pushed code to Github. I also learned how to undo mistakes by reverting the previous commits.

> _Reflection:_ Learning how to use Git and get to know informations about Github is the most interesting Skill I've learned from this course, as it will allow me to do more project in the future.

## Example from week4:

```bash
git add .
git commit -m "really fun course"
git push origin
```
#these command are used to save the changes locally with descriptive message

# Summery of each week's content

| Week | Topic | Key Commands Learned |
| :--- | :--- | :--- |
| **Week 1** | Introduction to Command Line Environments | `ls`, `mkdir`, `cd`, `wget`, `chmod` |
| **Week 2** | Text Processing in UNIX | `egrep`, `sed`, `sort`, `uniq` |
| **Week 3** | Scripting, Configuration Files and Installing Programs | `if`, `echo`, `export`, `pip`, `brew`, `sudo` |
| **Week 4** | Using ssh, scp and Version Control | `ssh`, `git`, `scp`, `kill`, `jobs` |

# My Goal for this course

- [x] Complete every moulde quizes
- [x] Mater 70% tools intorduced in this course
- [x] Write basic bash scripts
- [x] Complete final project
- [x] Know how to use Github

![My Image](assets/images/Thanks.jpg)
