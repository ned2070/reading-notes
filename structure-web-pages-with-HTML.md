# STRUCTURE WEB PAGES WITH HTML

### What is HTML?

HTML (**HyperText Markup Language**) is the code used to define the structure and contnts of a web page.

It's written as a plain text file with the ,htm or .html extension (e.g. myfile.html)

A web browser interprets the html file and generates a web page according to its instructions. 

The exact appearance may differ between browsers but the content is the same.



[Introducibg HTNL](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

[More on HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)



### Why use HTML?

HTML is the basic building block of the World Wide Web. Pages may be constructed in a graphical tool but these tools are merely manipulating HTML. 


[Introduction to web page design using wireframes](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/)


The links which connect web pages together are the **Hypertext** part of its name.

**Mark up** means that it annotates the page content using *tags* to control the pages.

**Tags** are instructions which enclose (*wrap*) the contents to which the instructions apply.



### HTML Elements

A HTML page is comprised of *elements*. Each **element** consists of:

+ **Opening tag**. The name of the element in angle brackets e.g \<p\> for a paragraph.

+ **Content**. The content, whether it be text, an image, a link etc.

+ **Closing tag**. The name of the element preceded by a backslash \, surrounded by angle brackets e.g. \<\p\>. Some types of elements don't need to be closed.

Thus for a heading \<h1\>This is the largest heading\<\h1\>

Tags may also contain **attributes** e.g *font-size* which contain extra information.



[HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)


A heading is an example of a *Semantic tag* .

**Semantic tag** means that the tag conveys a meaning which could be potentially understood by e.g. a search engine or screen reader.

For instance it would be possible to use the font-size attribute to make a normal length of text the same size as the one in te heading element. But it would not have the semantic information of a header and would not be recognised as a header by a screen reader even though it might be by a human user.

[More on semantic tags](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)