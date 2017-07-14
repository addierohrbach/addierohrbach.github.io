---
layout: post
title:  "CSS Methodologies"
date:   2017-07-14
---

CSS (or Cascading Style Sheets) is a vital part of the code for every website available. It takes the html, or the building block of the website, and styles it and makes it look visually appealing. Due to its job, CSS documents usually amass huge amounts of code. It is super easy to fall into the trap of repeating code and for people new to the document, it can be very hard to read.

### BEM (block element modifier)
1. Block: standalone entities that are meaningful on their own (ex: headers, menus, containers)
2. Element: a part of a block that has no meaning by itself and it semantically tied to its block (ex: menu item, list item)
3. Modifier: a flag on a block or element, used to change appearance or behavior (ex: checked, disabled, active)

### OOCSS (object oriented css)
The main objective of OOCSS is to separate the structure from the skin, which means breaking apart the positioning styles from the presentational styles, and the container from the content, which means to break elements' dependencies on their containers.
<br>
<br>
So why use OOCSS? When all of the css styles are accounted for, it is extremely fast and there is absolutely no repetition. It is also very maintainable and scaleable as classes can be reapplied to any element.
<br>
<br>
An example of coding with OOCSS:
<br>
HTML:<br>
{% highlight html %}
<h1 class="no-margin section-heading">Heading</h1>
{% endhighlight %}
CSS:<br>
{% highlight css %}
.no-margin {
  margin: 0;
}

.section-heading {
  font-size: 1.5em;
  text-transform: uppercase;
}
{% endhighlight %}

### SMACSS (scalable and modular architecture for css)
SMACSS splits css code into five difference categories: base, layout, module, state, and theme rules.
<br>
1. Base rules are defaults; they are almost always single element selectors, such as body, a, or h1.
2. Layout rules usually divide the page.
3. Modules are reusable parts, such as sidebar sections or lists.
4. State rules are rules determining how something will look when in a particular state (ex: active, inactive, hover); they indicate a javascript dependency. When using a state style that overrides another style, you must include `!important`.
5. Theme rules describe how something will look (these are less common).
<br>
The naming of css rules is very important because it increases the readability for someone looking at your code. SMACSS provides a method for naming: state rules always start with an 'is' (`.is-hidden`), modules are simply the name of the module, and layout rules are often styled with an ID or start with an l (`.l-inline`).
<br>
<br>
Another main part of SMACSS is the idea of shallow depth. This means that there should not be any rules that tag html elements with many tags (ex: `h1 ul li p { }`).
