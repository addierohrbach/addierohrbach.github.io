---
layout: post
title:  "Working with Jekyll"
date:   2017-06-26
---
In order to get this site up and running, I needed to use a program called Jekyll. In the end, this software provided a wonderful platform on which I could create this website; however, it took me a while to even get to the point at which I could begin coding.

### Downloading Jekyll
Surprisingly, downloading the Jekyll program took a decently long time. This is due to the problem that I kept on getting a response saying that I did not have the correct permissions. I went through a lot of tutorials which told me to download a separate version of ruby that I could make changes to. After a while of trying this, I was still getting the same error response.
<br>
<br>
Finally, I learned about the `sudo` command, which overrides incorrect permission errors. This command only works if you are the admin of the computer that you are using. This then allowed me to download Jekyll through typing `sudo gem install jekyll` into the terminal.

### Understanding Jekyll
When I first started a new Jekyll site by running the `jekyll new` command, I was overwhelmed with the folder that it automatically created. Before starting this apprenticeship, I only ever worked with an html file and a css file, that's it. Seeing all of the different folders required to create a website, I was extremely confused. I consulted many different online sources to figure out what it was all about. I finally began to understand Jekyll through reading and changing certain files and seeing the changes that it made.
<br>
<br>
One of the most interesting parts of working with Jekyll is the fact that it uses a local host. The local host allows you to see a live preview of your website by typing `html://localhost:4000` in your browser after running `jekyll serve`. Every time you save a new change in your code, you can refresh the browser and see the updated version.
<br>
<br>
The main difficulty that I had after understanding what each folder and file meant was figuring out all of the extra content that the root directory needed in order to fully customize your website. This directed me back to online tutorials that instructed me how to add and use the `_includes`, `_layouts`, and `_sass` folders, as well as create more pages and blog posts.

### Coding in Jekyll
At first, I began with simply changing the code inside of the default website. This was very helpful in learning the role of each file; however, this method was not ideal in creating a fully custom website. After experimenting with this for a while, I deleted that website and started a new one through `jekyll new`. In this new website, I created new html and sass documents that I could fully customize. This is where the fun began and I was able to begin customization.

### Things I learned
Probably the most important thing that I learned from creating this project, is the vital importance of the terminal. Not only was it required to download Jekyll, but it was massively useful and more convenient when navigating through directories and creating files. I found that the easiest way to create a file was through through typing the command `touch file_name` into the terminal. This created a file that you could then open up through any platform desired.
<br>
<br>
As for platforms, I found Atom to the be the most useful in this situation. Before starting this project, I used Text Wrangler (downloaded from the App Store); although it was fairly nice and easy to use, it was missing some vital features. I found that Atom was able to open a whole entire directory, which made it easy to navigate all the various directories and files inside the root one. Atom also allows you to work on two files side by side, which is helpful when you have to consult both the html and css documents. In the Text Wrangler app, you would have needed to open two separate windows in order for this to occur.
