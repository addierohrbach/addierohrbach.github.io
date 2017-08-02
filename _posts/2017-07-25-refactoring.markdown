---
layout: post
title:  "Refactoring"
date:   2017-07-24
---

Refactoring your code is one of the most vital steps in creating a project. Throughout the creation, you add code that may not actually contribute to the final design or you can simply make your code more concise and easier to understand.

### Version Control
In my first week here at 8th Light I was told to look into a method called version control, but I hadn't used it until now. After working with it, I totally understand the value that it has when trying to refactor your code. Version control (in github) allows you to work on a copy of your code, without messing up the original, working version.
<br>
<br>
In order to do this, you have to add a branch by typing in `git checkout -b branch-name` to the terminal. Now, you should be in a separate copy of your code. In this branch you can create any changes you would like by making commits just as you would in the master branch. However, it does not make official changes to your project until you merge the two branches.
<br>
<br>
I made the pull request and merged the two branches on the git website as I found that easier than doing it in the terminal. Making a pull request is helpful because people can look at it and decide if you should really commit these changes to the official project document. Once the decision has been made, you can easily click the merge branches button and you have a refactored project!

### Using Google's Developer Tools
I found that the most valuable tool in my process of refactoring was those available through Google Chrome. It was extremely helpful because once you host your project, you can inspect it. Inspecting code allows you to see what changing your code does in real time. I found that the most useful way to use this was to uncheck certain styles and see what it changed. In my project, this resulted in realizing that I had a lot of extraneous code that didn't really do anything.

### My Takeaways
The code for my website definitely needed a lot of refactoring. I found that when I originally coded this website I kept on adding styles to my CSS file until I achieved the desired look. Although the end result looks the same; however, after refactoring the code is extremely more concise and understandable.
