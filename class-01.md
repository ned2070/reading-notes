# CLASS 01

## Readings Overview

### The components of the internet and how they relate together

- Internet connection
- Clients and servers
- Internet protocols
- Domain Name Service
- Files and assets

[Overview of how the web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

[Video overview of the web](https://www.youtube.com/playlist?list=PLo3w8EB99pqLEopnunz-dOOBJ8t-Wgt2g)

[More on web history and standards](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/The_web_and_web_standards)

_The client and the server_  
_Talk in HTTP_  
_Like notes in a bottle_  
_Guided across the sea_

### File parsing in the web browser

- The HTML file is read by the browser first
- As it encounters references to CSS and Javascript pages it requests those pages from the server
- The browser builds the structure of the web page in local memory
- The web page is displayed on screen and the Javascript is compiled into machine language and executed

A HTML page is made up of **elements** which consist of _content_ and **tags** which _mark up_ the content, i.e. control how it interacrs with the browser. An element has an _opening tag_ and a _closing tag_ enclosing the content and may have additional tags as well. Elements and tags may be nested.

Example:

<\article> This element is of the article type <\/article>

A tag may also have **attributes** which contain **metadata** about the element, i.e. data which is not part of the content. The size of a file, for instance, is data related to a file but not part of the file's contents; it is metadata about the file.

Attributes are always enclosed in the opening tag and written as:

Name of attribute = "value of attribute"

Example:

<\section name = "mysection"\> This element has the section type and a name attribute with the value mysection <\/section\>

An _article_ element is used to group together related content while a _section_ element is used to group together related functionality.

Tags are enclosed in angle brackets. Note backslash on closing tag.

**Semantic** tags convey neaning in their names. For example it is better to use <\h1> tags for a heading rather than <\span> tags because the former conveys the meaning of a header to the browser. This can then be acted upon appropriately by e.g. screen reader software.

### How to start to design a website

- What do you hope to achieve with your website?
- How will the website help you achieve that?

### Introduction to web development

- HTML
- CSS
- Javascript
- Web page design
- Web page publishing

[Getting started with web development](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)

[Inroduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

[Getting started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

[Introduction to designing a website](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

### Elements of a typical website

A typical website has a **head** element which contains metadata about the site and a **body** element containing the site content.

The body can be subdivided into a **header**, a **main** and a **footer** element.

It is also common to have a **siderbar** or **navigation bar** (or both) to help navigate around a site.

Metadata is not visible on the web page but it can be scanned by search engines. The **meta** tag can be given attributes which help with _Serach Engine Optimization_, making the page more quickly and easily found.

[More detal on website structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

[More on metadaa in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

[More on SEO with meta tags](https://www.wordstream.com/meta-tags)

### Website content

A web page may contain text, images, data tables or various other types of content.

The best way to find images for your own web page is to search the internet for royalty free images, which can be easily incorporated into a web site without technical, legal or financial issues. Unsplash is a useful source.

[Unsplash](https://unsplash.com/)

### What is Javascript?

**Javascript** is used to make a webpage responsive to the user. Generally any interactive feature of a webpage, such as hiding and revealing information and zooming in on an image, requires the use of Javascript.

There are 3 ways of adding Javascript to a HTML document:

- Inline. Place a Javascript function inside a tag. This is considered bad practice.
- Internal. Place Javascript between <\script> tags on the HTML page.
- External. Place a **src** attribute inside an opening <\script\> tag with the src value being the path to a .js file containing the Javascript. Preferred method.

[What is Javascript?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

[More on Javascript](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

_Variables_ are often used to pass information between HTML and Javascript.

A **variable** is a named container for a piece of data. Variables are used in Javascript to store, exchange and manipulate information.

A **string** is a variable containing a length of text. A string can be created (_declared_) with the _let_ command or by assigning a variable a string value enclosed in quotes e,g myString = "myName" declares a new string variable called myString, wth the contents "myName".

A **number** variable contains a number and is created similarly e.g. let myNum = number or let myNum = 7.

Note that a string variable containg the text _7_ is not the same as a number variable containing the number _7_.

## Things I want to know more about

- Interaction between front and back end programs

---
