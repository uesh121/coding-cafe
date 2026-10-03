1. What did `pwd` print?
it printed my directory that I was working on

2. What did `ls -Force` show that plain `ls` did not?
it showed all files and directories 

3. Pick one line from `ls`. What do you think the `Mode` column means?
the mode column shows what type of item the file is in that line

4. Why does that work from where you are standing? Which kind of path is `coding-cafe\week02`? Absolute or Relative?
- coding cafe is a relative path , it works from where you are standing because because coding cafe is currently in the directory we are in.

5. `mv` did two different jobs above. What were they?
- it both moved a file into a directory and renamed the name of that file

6- How many folders are on your `PATH`? (They are separated by `:`)
- there are many folders in my path , more than 30
7. **Write down exactly where your `python3` lives.** You will need this again in a minute.
- /usr/bin/python3
8. Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?
- yes they are the same because python3 is installed in the same place for everybody

9. What exactly did the shell say? Explain the error in your own words, using the word **PATH**.
Command 'pyton3' not found, did you mean:
  command 'python3' from deb python3 (3.14.3-0ubuntu2)
Try: sudo apt install <deb name>
 pyton3 folder was not found in the path in our system.

 10. `.venv` did not appear with plain `ls`. Why not? (Refer back to section 1.)
files with . are treated as hidden files in linux , ls -a shows all hidden files and folder

11 What changed about your prompt?
(.venv) is coming infront of prompt

12 Compare this with what you wrote down for question 7. Is it the same path? If not, what does that tell
    you about what `activate` actually did to your `PATH`?
- this method shows the whole longer path and has .venv 


13. What is in the second list that was not in the first?

- the second list also has package of requests and its library

14 Where does `python3` point now?

- python3 points back to the original and shorter path now

15. Find what `ls -h` does. Write it in your own words.
- displays files are easy to read suffies like KB , GB instead of raw byte count.

16. What is the difference between what Ctrl + C and Ctrl + D did?
- Cntrl C is keyboard interrupt , ctrl +d is exit from interface





