# DESIGN WEB PAGES WITH CSS

### Whar is CSS?

CSS stands for **Cascading Style Sheets**. CSS is a language which modifies the appearance of HTML documents from the bland default. HTML controls the *strucure* and *contents* of a web page. CSS controls its *style*.

The *cascading* term refers to the ordee in which CSS attribute is applied.

[More CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

[CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

### How is CSS used?

There are **3** ways to insert CSS into a project.

+ **Inline** CSS. A *style* attribute containing CSS is added to a single HTML element, modifying that element alone.
+ **Internal** CSS. A *<style>* element containing CSS is added to the HTML header section of a web page, modifying that page.
+ **External** CSS. A *<link>* element in the header connects to a text file with a **.css** containing CSS - the *sheet* part of CSS.

Best practice in web design is to avoid mixing content and presentation, hence **external CSS is generally preferred** to internal CSS and the latter is preferred to inline CSS.



[More about using CSS](https://www.w3schools.com/css/css_howto.asp)


### Examples of CSS in use.

Inline CSS:

\<P style="color: red;"\>Your text here!\</P\>
Turns the text in this paragraph red.

Internal CSS:

\<style\>\
        p{color: red;}\    
\</style\>\

Turns all text on a page within a \<p\> tag red.

External CSS:

p { color: red }

Turns all text written within a \<p>\ tag on any linked page red.

[More about colours in CSS](https://www.w3schools.com/cssref/pr_text_color.php)

Note compulsry use of US spelling for color.

[An example use of CSS](https://meyerweb.com/eric/tools/css/reset/)

---
