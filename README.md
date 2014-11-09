sweet-shove markdown into your html
===========

Shove that Markdown straight into some sweet styled HTML


*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

*You **can** combine them*

* Item 1
* Item 2
  * Item 2a
  * Item 2b


It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)


preview_markdown_
===============

What is it?
----------
preview\_markdown\_locally illustrates how to give your repository a README.html file that renders your README.md locally so can iterate and preview before you push up to Github.

To see it in action, clone this repository and drop it under any static-file-serving web server. Then navigate to README.html.

If you're seeing this and you're not on github.com, you already have. Congrats ):

The README.html contains a hotlink to Github's bundled stylesheet, and the containers are named such that it'll apply properly. This helps me get a better picture of what the documentation will look like on github.com. That said, it's totally optional and you may have other HTML & CSS that you prefer.

Caveats
-------
Github uses Github Flavored Markdown (GFM). The included markdown.js does not contain the GFM extensions. Thus, you might see slight differences when rendered on Github.

See Also
--------
+ https://www.npmjs.org/package/markdown-preview
+ https://www.npmjs.org/package/downtown
+ https://github.com/pyrocat101/moo
+ https://www.npmjs.org/package/walkthrough
