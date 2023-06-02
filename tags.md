## TAG-1 Comments

### Syntax
```
<!--...-->
```
* The two forward slashes at the end of comment line (//) is the JavaScript comment symbol. This prevents JavaScript from executing the --> tag.

___

## TAG-2<!DOCTYPE>
          
### Syntax
          
```
<!DOCTYPE html>
```
** All HTML documents must start with a <!DOCTYPE> declaration.
** The declaration is not an HTML tag. 
It is an "information" to the browser about what document type to expect.
___

          
 ## TAG-3 <a>
## Syntax
              ```
              <a href="https://www.w3schools.com">Visit W3Schools.com!</a>
              ```
              **  tag defines a hyperlink, which is used to link from one page to another.
              An unvisited link is underlined and blue
              A visited link is underlined and purple
              An active link is underlined and red
              
              
Attribute	   Value	                 Description

download	filename	Specifies that the target will be downloaded when a user clicks                            on the hyperlink

href	URL	             Specifies the URL of the page the link goes to

___



## TAG-4  abbreviation
## Syntax

```
The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.
```
* tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
___

## TAG-5  Acronym

## Syntax

```The <acronym> tag was used in HTML 4 to define an acronym.

```
*Not Supported in HTML5.
___

## TAG-6 Address

## Syntax

```<address>
Written by <a href="mailto:webmaster@example.com">Jon Doe</a>.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```

* The address tag defines the contact information for the author/owner of a document or an article.
* The contact information can be an email address, URL, physical address, phone number, social media handle, etc.

___

## TAG-7 Applets
## Syntax

* The applet tag was used in HTML 4 to define an embedded applet (Plug-in).

___

## TAG-8 Area

## Syntax

```
<img src="workplace.jpg" alt="Workplace" usemap="#workmap" width="400" height="379">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
</map>

```
* The <area> tag defines an area inside an image map (an image map is an image with clickable areas).

<area> elements are always nested inside a <map> tag.

* The usemap attribute in <img> is associated with the <map> element's name attribute, and creates a relationship between the image and the map.

___

## TAG-9 Article

## Syntax

```<article>
<h2>Google Chrome</h2>
<p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
</article>

```
* The article tag specifies independent, self-contained content.

* Forum post
* Blog post
* News story

___

## TAG-10 Aside

## Syntax

```
<aside>
<h4>Epcot Center</h4>
<p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</aside>

```
* The aside tag defines some content aside from the content it is placed in.
* The aside content should be indirectly related to the surrounding content.

* content is often placed as a sidebar in a document.

___

 
 ## TAG-11 Audio

## Syntax

```
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
```
* The <audio> tag is used to embed sound content in a document, such as music or other audio streams.


___

## TAG-12 BOLD 

## Syntax 

```<b>
```
* The b tag specifies bold text without any extra importance.

___

# TAG-13 Base

## Syntax

```
<head>
  <base href="https://www.w3schools.com/" target="_blank">
</head>

```
* The base tag specifies the base URL and/or target for all relative URLs in a document.
* The base tag must have either an href or a target attribute present, or both.

## TAG-14 Basefont

* The basefont tag was used in HTML 4 to specify a default text-color, font-size or font-family for all the text in an HTML document.

___

## TAG-15 Bi-Directional Isolation

## Syntax

```
<ul>
  <li>User <bdi>hrefs</bdi>: 60 points</li>
  <li>User <bdi>jdoe</bdi>: 80 points</li>
  <li>User <bdi>إيان</bdi>: 90 points</li>
</ul>
```

* The bdi tag isolates a part of text that might be formatted in a different direction from other text outside it.

___

## TAG-16  Bi-Directional Override

## Syntax
```<bdo dir="rtl">
This text will go right-to-left.
</bdo>
```

*The bdo tag is used to override the current text direction
___

## TAG-17 BIG

* The big tag was used in HTML 4 to define bigger text.

___

## TAG -18 Blockquote
## Syntax
```
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally.
</blockquote>

* The blockquote tag specifies a section that is quoted from another source.
___

## TAG-19 Body
## Syntax
```
<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>
</body>
```

* The body tag defines the document's body
*  There can only be one body element in an HTML document

____

## TAG-20  Breaks
## Syntax
```
<p>To force<br> line breaks<br> in a text,<br> use the br<br> element.</p>
```
* The br tag inserts a single line break.
* The br tag is useful for writing addresses or poems.
* The br tag is an empty tag which means that it has no end tag.

___
## TAG-21 Button
## Syntax
```
<button type="button">Click Me!</button>
```
* The  <button> tag defines a clickable button.
* Inside a <button> element you can put text (and tags like <i>, <b>, <strong>, <br>, <img>, etc.). That is not possible with a button created with the <input> element!

___
## TAG-22 Canvas
## Syntax
```
<canvas id="myCanvas">
Your browser does not support the canvas tag.
</canvas>
```
* The <canvas> tag is used to draw graphics, on the fly, via scripting (usually JavaScript).
* Any text inside the <canvas> element will be displayed in browsers with JavaScript disabled and in browsers that do not support <canvas>
___
## TAG-23 Caption
## Syntax
```
  <caption>Monthly savings</caption>
  ```
  * The <caption> tag defines a table caption.
  * The <caption> tag must be inserted immediately after the <table> tag.
  ___
  ## TAG-24 Center
  * The <center> tag was used in HTML4 to center-align text.
  ___
  ## TAG-24 Cite
  ## Syntax
  ```
  <p><cite>The Scream</cite> by Edward Munch. Painted in 1893.</p>
  ```
  * The <cite> tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.)
  ___
  ## TAG-25  Code
  ## Syntax
    ```
    <p>The HTML <code>button</code> tag defines a clickable button.</p>
    ```
    * The <code> tag is used to define a piece of computer code. The content inside is displayed in the browser's default monospace font.
    ___
    ## TAG-26 col
    ## Syntax 
    ```
    <col span="2" style="background-color:red">
    ```
    * The <col> tag specifies column properties for each column within a <colgroup> element.
    ___
    ## TAG-27 Colgroup
    ## Syntax
    ```
     <colgroup>
    <col span="2" style="background-color:red">
    <col style="background-color:yellow">
  </colgroup>
  ```
  * The <colgroup> tag specifies a group of one or more columns in a table for formatting.
  * The <colgroup> tag is useful for applying styles to entire columns, instead of repeating the styles for each cell, for each row.
  ___
  ## TAG-28 Data
  ## Syntax 
  ```
    <li><data value="21053">Cherry Tomato</data></li>
    ```
    * The <data> tag is used to add a machine-readable translation of a given content.
    ___
    ## TAG-29 Datalist
    ## Syntax
    ```
    <datalist id="browsers">
  <option value="Edge">
  <option value="Firefox">
  <option value="Chrome">
  <option value="Opera">
  <option value="Safari">
</datalist>
```

* The <datalist> tag specifies a list of pre-defined options for an <input> element.
* The <datalist> tag is used to provide an "autocomplete" feature for <input> elements. Users will see a drop-down list of pre-defined options as they input data.
___
## TAG-30 DD
# Syntax
```
 <dd>Black hot drink</dd>
 ```
 * The <dd> tag is used to describe a term/name in a description list.
 * The <dd> tag is used in conjunction with <dl> (defines a description list) and <dt> (defines terms/names).
 ___
 ## TAG-31 Del
 ## Syntax
 ```
 <p>My favorite color is <del>blue</del> <ins>red</ins>!</p>
 ```
 * The <del> tag defines text that has been deleted from a document. Browsers will usually strike a line through deleted text.
 
 ___
 ## TAG-32 Details
 ## Syntax
 ```
 <details>
  <summary>Epcot Center</summary>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</details>
```
* The <details> tag specifies additional details that the user can open and close on demand
* The <details> tag is often used to create an interactive widget that the user can open and close. By default, the widget is closed. When open, it expands, and displays the content within.
___
## TAG-33 Definition element
## Syntax
```
<p><dfn>HTML</dfn> is the standard markup language for creating web pages.</p>
```
* The <dfn> tag stands for the "definition element", and it specifies a term that is going to be defined within the content
___
## TAG-34
## Syntax
```
<dialog open>This is an open dialog window</dialog>
```
* The <dialog> tag defines a dialog box or subwindow.
* The <dialog> element makes it easy to create popup dialogs and modals on a web page.
___
## TAG-35 Dialog
## Syntax
```
<dialog open>This is an open dialog window</dialog>
```
* The <dialog> tag defines a dialog box or subwindow.
* The <dialog> element makes it easy to create popup dialogs and modals on a web page.
___
## TAG-36 Dir
## Syntax

* Not Supported in HTML5
___
## TAG-37 Div
## Syntax
```
<div class="myDiv">
  <h2>This is a heading in a div element</h2>
  <p>This is some text in a div element.</p>
</div>
```
* The <div> tag defines a division or a section in an HTML document.
* The <div> tag is used as a container for HTML elements - which is then styled with CSS or manipulated with JavaScript.
* The <div> tag is easily styled by using the class or id attribute.
___
## TAG-39 DL
## Syntax
```
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>
```
* The <dl> tag defines a description list
* The <dl> tag is used in conjunction with <dt> (defines terms/names) and <dd> (describes each term/name).
___
## TAG-40 Defines
## Syntax
```
 <dt>Coffee</dt>
 ```
 * The <dt> tag defines a term/name in a description list.
 * The <dt> tag is used in conjunction with <dl> (defines a description list) and <dd> (describes each term/name)
 ___
 


 
 


          
          

