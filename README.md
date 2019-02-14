# How to submit your code callenges

1. Save your code on your computer
   Make a new folder/directory and save your answers in there. H
   We dont care too much how you cave them, so long as you know how to demonstrate your answers it's fine. If If you want to make multiple files then do that
   If you want to make one file then do that
   If you want to make multiple sub-directories then do that
   etc

2. make sure "git" is installed on your computer. You can find instructions here: https://www.atlassian.com/git/tutorials/install-git

3. Now open up a terminal on your computer and `cd` into the directory where you saved your files.
   If this step makes absolutely no sense then please visit: http://rik.smith-unna.com/command_line_bootcamp/?id=91tih1fq76g and go through the tutorial up until the end of step 5

4. Make sure you are in the right place:
   if you type `ls` in your terminal then you should see all your answer files and/or directories. And you SHOULD NOT see any other files

5. Create a github user account

   1. go to https://github.com
   2. create a "free" account.

6. Create public repo on github

   1. on the left hand side of the page there is a "Create a repository" link. click on it
   2. give your repo a name. For example "umuzi_bootcamp_coding_challenges"
   3. make sure "public" is selected
   4. submit the form

7. "Push" your code to github
   You should now see a bunch of headings and funny looking commands. Look for the title that says "…or create a new repository on the command line". Copy the code from there and paste it into your terminal.

   The last command `git push -u origin master` requires your username and password. If you get an autherisation error then enter thatcommand again.

   Now paste in the following code:

```
git add .
git commit -m "my code"
git push
```

Now you will be able to view your code on github.

It will ask you to authnticate again.

8. If you want to make any changes to your submitted code then just make those changes on your local machine and paste in thoselast three commands again.

9. When you are happy that your challenges are complete then please find Dibwe or Sheena
