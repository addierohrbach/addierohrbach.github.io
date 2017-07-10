---
layout: post
title:  "Semantics and Accessibility"
date:   2017-07-04
---

In my first blog post, I touched on the idea of semantics; however, in this post I will dive deeper them as well as into accessibility.

### Accessibility
Making a website "accessable" means creating a page that is available to everyone (even people with disabilities). There are assistive softwares for people who are blind or who suffer from mobility disabilities. For people who are deaf or hearing impaired, text options for video and audio elements such as closed captioning or transciptions must be used.
<br>
<br>
The most important as well as one of the most overlooked aspects of making a site more accessible is good design and good user experience; there are a great deal of websites that are too complicated, which makes it difficult to use.
<br>
<br>
Some examples of accessibility include: images should contain an alternative text in the code using the `alt=""` tag, as well as allows all the functionality to be controlled through the keyboard. 

### Semantics
Of course, the basis of a good website is good coding; however, this sometimes gets overlooked. 
<br>
The original creators of HTML did not have design in mind while developing this language as they had no idea the potential of the internet. The header tags (`<h1>` through `<h6>`) were then not meant for styling, in fact they were meant for creating a hierarchy. Designers can then change the visual aspect of the heading without altering the underlying semantic element and meaning. Assistive technologies can then use these sematics to help people with disabilities understand what is in front of them.
<br>
Note: With headings, the most important one usually has the `<h1>` tag and the second degree ones have the `<h2>` tag and so on. It is vital to use the heading tags when creating a header instead of simply styling text to be large or bold. It is also important to not use heading tags when styling an element that is not meant to be a header.
<br>
<br>
Using lists properly is also another important skill to learn as lists in HTML have a specific hierarchy and meaning. Unordered lists must hold elements that have no specific sequence; whereas, ordered lists must hold elements that have to be in a certain order. Lists can never be empty and must be structured correctly.
<br>
<br>
Examples of semantic elements:
<br>
`<header>` - should be used as a container for introductory content <br>
`<section>` - defines a specified group of content, usually with a heading (some pages are separated into sections for the introduction, content, and content information) <br>
`<article>` - an independent, self-contained content; it should make sense on its own, such as blog posts <br>
`<footer>` - typically contains the author or copyright information <br>
`<nav>` - defines a set of navigation links <br>
`<aside>` - information that is related to the main content, but seperate from it <br>
`<figure>` - holds the `<img>` and `<figcaption>` elements; used when the image is a main part of the page (you can use this for other types of content as well, such as audio or videos) <br>
HTML5 finally has amazing support for audio and video files: <br>
`<video>` and `<audio>` - specify a source; users can use the keyboard to control the content <br>

### HTML5
Semantics are amazing and very helpful; however, not all browsers will support all the new elements.
<br>
For browsers that don't completely support HTML5, developers can use ARIA, which can achieve the same results. For example: `<header>...</header>` is the same as `<div role="banner">...</div>`. The main difference in using the header tag versus the div tag is that the semantic tag `<header>` adds meaning and structure to the page.
<br>
<br>
There are few things you can do to cover all your bases in the different browser versions. You can use both HTML5 and ARIA: `<header role="banner">`. This will still render in older browsers. (Note: you will have to add a `display: block` rule to have the element act completely like how it acts in HTML5).
