# Title

## HTML

### Introduction

***

HTML stands for HyperText Markup Language:

* A markup language is a computer language that defines the structure and presentation of raw text.
* In HTML, the computer can interpret raw text that is wrapped in HTML elements.
* HyperText is text displayed on a computer or device that provides access to other text through links, also known as hyperlinks. 

Learning HTML is the first step in creating websites, but even a bit of knowledge can help you inject code snippets into newsletter, blog or website templates. As you continue learning, you can layer HTML with CSS and JavaScript to create visually compelling and dynamic websites. Using HTML we can add and modify basic content on a page, like text, images, and videos. Don’t worry if the websites look ugly — we’re just getting started.

### Elements

An HTML file is made of elements. These elements are responsible for creating web pages and define content in that webpage. An element in HTML usually consist of a start tag <tag name>, close tag </tag name> and content inserted between them. Technically, an element is a collection of start tag, attributes, end tag, content between them.

```HTML
<!DOCTYPE html>  
<html>  
<head>  
    <title>WebPage</title>  
</head>  
<body>  
    <h1>This is my first web page</h1>  
    <h2> How it looks?</h2>  
        <p>It looks Nice!!!!!</p>  
</body>  
</html>  
```

![](https://static.javatpoint.com/htmlpages/images/html-elements.png)

### HTML Atrrubutes

HTML attributes generally come in name-value pairs, and always go in the opening tag of an element. The attribute name says what type of information you’re providing about the element, and the attribute value is the actual information.

For example, an anchor (< a >) element in an HTML document creates links to other pages, or other parts of the page. You use the href attribute in the opening < a > tag to tell the browser where the link sends a user.

Here’s an example of a link that sends users to google.com’s home page:

```HTML
<a href="www.google.org">Click here to go to freeCodeCamp!</a>
```

Notice that the attribute name (href) and value (“www.google.org”) are separated with an equals sign, and quotes surround the value.

There are many different HTML attributes, but most of them only work on certain HTML elements. For example, the href attribute won’t work if it’s placed in an opening < h1 > tag.

In the example above, the value supplied to the href attribute could be any valid link. However, some attributes only have a set of valid options you can use, or values need to be in a specific format. The lang attribute tells the browser the default language of the contents in an HTML element. The values for the lang attribute should use standard language or country codes, such as en for English, or it for Italian.

### HTML Heading
***

 HTML heading or HTML h tag can be defined as a title or a subtitle which you want to display on the webpage. When you place the text within the heading tags < h1 >.........</ h1 >, it is displayed on the browser in the bold format and size of the text depends on the number of heading.

There are six different HTML headings which are defined with the < h1 > to < h6 > tags, from highest level h1 (main heading) to the least level h6 (least important heading).

h1 is the largest heading tag and h6 is the smallest one. So h1 is used for most important heading and h6 is used for least important.

Example - 

```HTML
<!DOCTYPE html>  
<html>  
 <head>  
    <title>Heading elements</title>  
 </head>  
 <body>  
     <h1>This is main heading of page. </h1>  
      <p>h1 is the most important heading, which is used to display the keyword of page </p>  
     <h2>This is first sub-heading</h2>  
      <p>h2 describes the first sub heading of page. </p>  
     <h3>This is Second sub-heading</h3>  
      <p>h3 describes the second sub heading of page.</p>  
      <p>We can use h1 to h6 tag to use the different sub-heading with their paragraphs if         
                     required.   
                </p>  
   </body>  
</html> 
```

![](https://static.javatpoint.com/htmlpages/images/html-heading.png)

### HTML Paragraphs
***

The < p > HTML element represents a paragraph. Paragraphs are usually represented in visual media as blocks of text separated from adjacent blocks by blank lines and/or first-line indentation, but HTML paragraphs can be any structural grouping of related content, such as images or form fields.

```HTML
<!DOCTYPE html>
<html>
<body>
	<p>A Computer Science portal for geeks.</p>
	<p>
	It contains well written, well thought
	articles.
	</p>
</body>
</html>
```

![](https://media.geeksforgeeks.org/wp-content/uploads/hp.jpg)


### HTML hyperlinks
***

A link or hyperlink is a connection from one web resource to another. Links allow users to move seamlessly from one page to another, on any server anywhere in the world.

A link has two ends, called anchors. The link starts at the source anchor and points to the destination anchor, which may be any web resource, for example, an image, an audio or video clip, a PDF file, an HTML document or an element within the document itself, and so on.

```HTML
<a href="https://www.google.com/">Google Search</a>
<a href="https://www.tutorialrepublic.com/">Tutorial Republic</a>
<a href="images/kites.jpg">
    <img src="kites-thumb.jpg" alt="kites">
</a>
```

The href attribute specifies the target of the link. Its value can be an absolute or relative URL.

An absolute URL is the URL that includes every part of the URL format, such as protocol, host name, and path of the document, e.g., https://www.google.com/, https://www.example.com/form.php, etc. While, relative URLs are page-relative paths, e.g., contact.html, images/smiley.png, and so on. A relative URL never includes the http:// or https:// prefix.

### HTML images
***

HTML img tag is used to display image on the web page. HTML img tag is an empty tag that contains attributes only, closing tags are not used in HTML image element.

```HTML
<h2>HTML Image Example</h2>  
<img src="good_morning.jpg" alt="Good Morning Friends"/>  
```

Output -

![](https://static.javatpoint.com/htmlpages/images/good-morning.jpg)

Attributes of < img > tag

* src

It is a necessary attribute that describes the source or path of the image. It instructs the browser where to look for the image on the server.

The location of image may be on the same directory or another server.

* alt

The alt attribute defines an alternate text for the image, if it can't be displayed. The value of the alt attribute describe the image in words. The alt attribute is considered good for SEO prospective.

* width

It is an optional attribute which is used to specify the width to display the image. It is not recommended now. You should apply CSS in place of width attribute.

* height

It h3 the height of the image. The HTML height attribute also supports iframe, image and object elements. It is not recommended now. You should apply CSS in place of height attribute.

Example : 
```HTML
<img src="animal.jpg" height="180" width="300" alt="animal image">  
```

Output-

![](https://static.javatpoint.com/htmlpages/images/html-image.png)

### HTML Table tags
***

The HTML table provides a way to derive or define the data such as text, images, links etc., in terms of rows and columns of cells. The HTML tables can be created by using <table> tag. By default, the table data is left aligned. In this topic, we are going to learn about HTML Table Tags.

The table can be created by using < th >, < td >, and < tr > tags.

    The < th > tag defines a heading for the table.
    The < td > tag specifies the table data cells which are used to make the column.
    The <tr> tag specifies the table rows which is used to make a row.

The table data can be structured within < table >content of the table< /table > with numerous table elements.


Example-

```HTML
<table>
<tr>
<th>Table Heading 1</th>
<th>Table Heading 2</th>
</tr>
<tr>
<td>Data Cell 1</td>
<td>Data Cell 2</td>
</tr>
<tr>
<td>Data Cell 3</td>
<td>Data Cell 4</td>
</tr>
</table>
```


Output-

<table>
<tr>
<th>Table Heading 1</th>
<th>Table Heading 2</th>
</tr>
<tr>
<td>Data Cell 1</td>
<td>Data Cell 2</td>
</tr>
<tr>
<td>Data Cell 3</td>
<td>Data Cell 4</td>
</tr>
</table>


***



### HTML Lists
***
HTML lists are used to present list of information in well formed and semantic way. There are three different types of list in HTML and each one has a specific purpose and meaning.

* Unordered list — Used to create a list of related items, in no particular order.
* Ordered list — Used to create a list of related items, in a specific order.
* Description list — Used to create a list of terms and their descriptions.

1) HTML Unordered lists

An unordered list created using the <ul> element, and each list item starts with the <li> element.

The list items in unordered lists are marked with bullets. Here's an example:

```html
<ul>
    <li>Chocolate Cake</li>
    <li>Black Forest Cake</li>
    <li>Pineapple Cake</li>
</ul>
```
Output-

<ul>
    <li>Chocolate Cake</li>
    <li>Black Forest Cake</li>
    <li>Pineapple Cake</li>
</ul>


2) HTML ordered lists

An ordered list created using the < ol > element, and each list item starts with the < li > element. Ordered lists are used when the order of the list's items is important.

The list items in an ordered list are marked with numbers. Here's an example:

```html
<ol>
    <li>Fasten your seatbelt</li>
    <li>Starts the car's engine</li>
    <li>Look around and go</li>
</ol>
```
Output-

<ol>
    <li>Fasten your seatbelt</li>
    <li>Starts the car's engine</li>
    <li>Look around and go</li>
</ol>


### Block and Inline Elents
***

Every HTML element has a default display value, depending on what type of element it is.

There are two display values: block and inline.

1) **Block Level Elements**

A block-level element always starts on a new line.

A block-level element always takes up the full width available (stretches out to the left and right as far as it can).

A block level element has a top and a bottom margin, whereas an inline element does not.

```html

<address>

<article>

<aside>

<blockquote>

<canvas>

<div>

<dl>

<dt>

<fieldset>

<figcaption>

<figure>

<footer>

<form>

<h1>-<h6>

<header>

<hr>

<li>

<main>

<nav>

<noscript>

<ol>

<p>

<pre>

<section>

<table>

<tfoot>

<ul>

<video>
```

<br>


2) **Inline Elements**

An inline element does not start on a new line.

An inline element only takes up as much width as necessary.

This is a < span > element inside a paragraph.

```html

<a>

<abbr>

<acronym>

<b>

<bdo>

<big>

<br>

<button>

<cite>

<code>

<dfn>

<em>

<i>

<img>

<input>

<kbd>

<label>

<map>

<object>

<output>

<q>

<samp>

<script>

<select>

<small>

<span>

<strong>

<sub>

<sup>

<textarea>

<time>

<tt>

<var>

```

### HTML Classes
***

The HTML class attribute is used to specify a class for an HTML element.

Multiple HTML elements can share the same class.

**Using the class attributes**

The class attribute is often used to point to a class name in a style sheet. It can also be used by a JavaScript to access and manipulate elements with the specific class name.

In the following example we have three <div> elements with a class attribute with the value of "city". All of the three <div> elements will be styled equally according to the .city style definition in the head section:

```html
 <!DOCTYPE html>
<html>
<head>
<style>
.city {
  background-color: tomato;
  color: white;
  border: 2px solid black;
  margin: 20px;
  padding: 20px;
}
</style>
</head>
<body>

<div class="city">
  <h2>London</h2>
  <p>London is the capital of England.</p>
</div>

<div class="city">
  <h2>Paris</h2>
  <p>Paris is the capital of France.</p>
</div>

<div class="city">
  <h2>Tokyo</h2>
  <p>Tokyo is the capital of Japan.</p>
</div>

</body>
</html> 
```
### HTML id
***

The HTML id attribute is used to specify a unique id for an HTML element.

You cannot have more than one element with the same id in an HTML document.

**Using the id attribute**

The id attribute specifies a unique id for an HTML element. The value of the id attribute must be unique within the HTML document.

The id attribute is used to point to a specific style declaration in a style sheet. It is also used by JavaScript to access and manipulate the element with the specific id.

The syntax for id is: write a hash character (#), followed by an id name. Then, define the CSS properties within curly braces {}.

In the following example we have an < h1 > element that points to the id name "myHeader". This < h1 > element will be styled according to the #myHeader style definition in the head section:

```html
 <!DOCTYPE html>
<html>
<head>
<style>
#myHeader {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
}
</style>
</head>
<body>

<h1 id="myHeader">My Header</h1>

</body>
</html> 
```

### HTML Responsive
***

Responsive web design is used to make your web page look appropriate, good, and well placedon all devices (desktop, tablet, smartphone etc.)

Responsive web design uses HTML and CSS to resize, hide, shrink, enlarge, or move the content. It makes the content look good on any screen.

```html
<!DOCTYPE html>  
<html>  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<body>  
<h2>Responsive Image</h2>  
<p>When we set the CSS width property to 100%, it makes the image responsive.    
Resize the browser window to see the effect.</p>  
<img src="img_girl.jpg" style="width:100%;">( change image)  
</body>  
</html>
```

## **CSS**

### CSS Introduction
***

CSS tutorial or CSS 3 tutorial provides basic and advanced concepts of CSS technology. Our CSS tutorial is developed for beginners and professionals. The major points of CSS are given below:

* CSS stands for Cascading Style Sheet.
* CSS is used to design HTML tags.
* CSS is a widely used language on the web.
    HTML, CSS and JavaScript are used for web designing. It helps the web designers to apply style on HTML tags.


Example-

```html
<!DOCTYPE>  
<html>  
<head>  
<style>  
h1{  
color:white;  
background-color:red;  
padding:5px;  
}  
p{  
color:blue;  
}  
</style>  
</head>  
<body>  
<h1>Write Your First CSS Example</h1>  
<p>This is Paragraph.</p>  
</body>  
</html> 
```

### CSS Selectors
***

CSS selectors are used to select the content you want to style. Selectors are the part of CSS rule set. CSS selectors select HTML elements according to its id, class, type, attribute etc.

There are several different types of selectors in CSS.

1. CSS Element Selector
2. CSS Id Selector
3. CSS Class Selector
4. CSS Universal Selector
5. CSS Group Selector

1) CSS Element selector

The element selector selects the HTML element by name.

```html
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    p{  
        text-align: center;  
        color: blue;  
    }   
    </style>  
    </head>  
    <body>  
    <p>This style will be applied on every paragraph.</p>  
    <p id="para1">Me too!</p>  
    <p>And me!</p>  
    </body>  
    </html>    
```

2) CSS id selector

The id selector selects the id attribute of an HTML element to select a specific element. An id is always unique within the page so it is chosen to select a single, unique element.

It is written with the hash character (#), followed by the id of the element.

Let?s take an example with the id "para1".

```html
<!DOCTYPE html>  
<html>  
<head>  
<style>  
#para1 {  
    text-align: center;  
    color: blue;  
}  
</style>  
</head>  
<body>  
<p id="para1">Hello Javatpoint.com</p>  
<p>This paragraph will not be affected.</p>  
</body>  
</html>
```
3) CSS Class Selector

The class selector selects HTML elements with a specific class attribute. It is used with a period character . (full stop symbol) followed by the class name. 

```html
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    .center {  
        text-align: center;  
        color: blue;  
    }  
    </style>  
    </head>  
    <body>  
    <h1 class="center">This heading is blue and center-aligned.</h1>  
    <p class="center">This paragraph is blue and center-aligned.</p>   
    </body>  
    </html>  
```

4) CSS Universal Selector

The universal selector is used as a wildcard character. It selects all the elements on the pages. 

```html
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    * {  
       color: green;  
       font-size: 20px;  
    }   
    </style>  
    </head>  
    <body>  
    <h2>This is heading</h2>  
    <p>This style will be applied on every paragraph.</p>  
    <p id="para1">Me too!</p>  
    <p>And me!</p>  
    </body>  
    </html>    
```

5) CSS Group Selector

The grouping selector is used to select all the elements with the same style definitions.

Grouping selector is used to minimize the code. Commas are used to separate each selector in grouping.

Let's see the CSS code without group selector.
```css
    h1 {  
        text-align: center;  
        color: blue;  
    }  
    h2 {  
        text-align: center;  
        color: blue;  
    }  
    p {  
        text-align: center;  
        color: blue;  
    }  
```

As you can see, you need to define CSS properties for all the elements. It can be grouped in following ways:

```css
    h1,h2,p {  
        text-align: center;  
        color: blue;  
    }  
```
### CSS Colors
***
CSS supports 140+ color names, HEX values, RGB values, RGBA values, HSL values, HSLA values, and opacity.

**RGBA Colors**

RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color.

An RGBA color value is specified with: rgba(red, green, blue, alpha). The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (fully opaque).

Example-
```css
#p1 {background-color: rgba(255, 0, 0, 0.3);}  /* red with opacity */
#p2 {background-color: rgba(0, 255, 0, 0.3);}  /* green with opacity */
#p3 {background-color: rgba(0, 0, 255, 0.3);}  /* blue with opacity */
```

**HSL Colors**

HSL stands for Hue, Saturation and Lightness.

An HSL color value is specified with: hsl(hue, saturation, lightness).

1. Hue is a degree on the color wheel (from 0 to 360):
    * 0 (or 360) is red
    * 120 is green
    * 240 is blue
2. Saturation is a percentage value: 100% is the full color.
3. Lightness is also a percentage; 0% is dark (black) and 100% is white.

```css
#p1 {background-color: hsla(120, 100%, 50%, 0.3);}  /* green with opacity */
#p2 {background-color: hsla(120, 100%, 75%, 0.3);}  /* light green with opacity */
#p3 {background-color: hsla(120, 100%, 25%, 0.3);}  /* dark green with opacity */
#p4 {background-color: hsla(120, 60%, 70%, 0.3);}   /* pastel green with opacity */
```
**Opacity**

The CSS opacity property sets the opacity for the whole element (both background color and text will be opaque/transparent).

The opacity property value must be a number between 0.0 (fully transparent) and 1.0 (fully opaque).

The following example shows different elements with opacity:

```css
 #p1 {background-color:rgb(255,0,0);opacity:0.6;}  /* red with opacity */
#p2 {background-color:rgb(0,255,0);opacity:0.6;}  /* green with opacity */
#p3 {background-color:rgb(0,0,255);opacity:0.6;}  /* blue with opacity */
```

### CSS Borders

The CSS border properties allow you to specify the style, width, and color of an element's border.

**CSS border-style**
The border-style property specifies what kind of border to display.

The following values are allowed:

    dotted - Defines a dotted border
    dashed - Defines a dashed border
    solid - Defines a solid border
    double - Defines a double border
    groove - Defines a 3D grooved border. The effect depends on the border-color value
    ridge - Defines a 3D ridged border. The effect depends on the border-color value
    inset - Defines a 3D inset border. The effect depends on the border-color value
    outset - Defines a 3D outset border. The effect depends on the border-color value
    none - Defines no border
    hidden - Defines a hidden border

The border-style property can have from one to four values (for the top border, right border, bottom border, and the left border).

Example-

```css
p.dotted {border-style: dotted;}
p.dashed {border-style: dashed;}
p.solid {border-style: solid;}
p.double {border-style: double;}
p.groove {border-style: groove;}
p.ridge {border-style: ridge;}
p.inset {border-style: inset;}
p.outset {border-style: outset;}
p.none {border-style: none;}
p.hidden {border-style: hidden;}
p.mix {border-style: dotted dashed solid double;}
```
### CSS Margins

CSS Margin property is used to define the space around elements. It is completely transparent and doesn't have any background color. It clears an area around the element.

Top, bottom, left and right margin can be changed independently using separate properties. You can also change all properties at once by using shorthand margin property.

There are following CSS margin properties:

```css
<html>  
<head>  
<style>  
p {  
    background-color: pink;  
}  
p.ex {  
    margin-top: 50px;  
    margin-bottom: 50px;  
    margin-right: 100px;  
    margin-left: 100px;  
}  
</style>  
</head>  
<body>  
<p>This paragraph is not displayed with specified margin. </p>  
<p class="ex">This paragraph is displayed with specified margin.</p>  
</body>  
</html>  
```

### CSS Padding
***

CSS Padding property is used to define the space between the element content and the element border.

It is different from CSS margin in the way that CSS margin defines the space around elements. CSS padding is affected by the background colors. It clears an area around the content.

Top, bottom, left and right padding can be changed independently using separate properties. You can also change all properties at once by using shorthand padding property. 

```css
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    p {  
        background-color: pink;  
    }  
    p.padding {  
        padding-top: 50px;  
        padding-right: 100px;  
        padding-bottom: 150px;  
        padding-left: 200px;  
    }  
    </style>  
    </head>  
    <body>  
    <p>This is a paragraph with no specified padding.</p>  
    <p class="padding">This is a paragraph with specified paddings.</p>  
    </body>  
    </html>  
```

### CSS Box model
***

The components that can be depicted on the web page consist of one or more than one rectangular box.

A CSS box model is a compartment that includes numerous assets, such as edge, border, padding and material. It is used to develop the design and structure of a web page. It can be used as a set of tools to personalize the layout of different components. According to the CSS box model, the web browser supplies each element as a square prism.

The following diagram illustrates how the CSS properties of width, height, padding, border and margin dictate that how much space an attribute will occupy on a web page.

![](https://static.javatpoint.com/csspages/images/css-box-model.png)

The CSS box model contains the different properties in CSS. These are listed below.

* Border
* Margin
* Padding
* Content

Now, we are going to determine the properties one by one in detail.

**Border Field**

It is a region between the padding-box and the margin. Its proportions are determined by the width and height of the boundary.

**Margin Field**

This segment consists of the area between the boundary and the edge of the border.

The proportion of the margin region is equal to the margin-box width and height. It is better to separate the product from its neighbor nodes.

**Padding Field**

This field requires the padding of the component. In essence, this area is the space around the subject area and inside the border-box. The height and the width of the padding box decide its proportions.

**Content Field**

Material such as text, photographs, or other digital media is included in this area.

It is constrained by the information edge, and its proportions are dictated by the width and height of the content enclosure

```css
    <!DOCTYPE html>   
    <head>   
    <title>CSS Box Model</title>   
    <style>   
                .main   
    {   
                    font-size:30px;   
                    font-weight:bold;   
                    Text-align:center;   
                }   
                .gfg   
    {   
                    margin-left:50px;   
                    border:50px solid Purple;   
                    width:300px;   
                    height:200px;   
                    text-align:center;   
                    padding:50px;   
                }   
                .gfg1   
    {   
                    font-size:40px;   
                    font-weight:bold;   
                    color:black;   
                    margin-top:60px;   
                    background-color:purple;   
                }   
                .gfg2   
    {   
                    font-size:20px;   
                    font-weight:bold;   
                    background-color:white;   
                }   
    </style>   
    </head>   
    <body>   
    <div class = "main">CSS Box-Model Property</div>   
                <div class = "gfg">   
                <div class = "gfg1">JavaTpoint</div>   
                <div class = "gfg2">A best portal for learn Technologies</div>   
    </div>   
    </body>   
    </html>  
```

### CSS Display
***

CSS display is the most important property of CSS which is used to control the layout of the element. It specifies how the element is displayed.

Every element has a default display value according to its nature. Every element on the webpage is a rectangular box and the CSS property defines the behavior of that rectangular box. 

There are following CSS display values which are commonly used.

1. display: inline;
2. display: inline-block;
3. display: block;
4. display: run-in;
5. display: none;

<br>

1) **CSS display inline**

The inline element takes the required width only. It doesn't force the line break so the flow of text doesn't break in inline example. 

The inline elements are:

    <span>
    <a>
    <em>
    <b> etc.


```css
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    p {  
    display: inline;   
    }  
    </style>  
    </head>  
    <body>  
    <p>Hello Javatpoint.com</p>  
    <p>Java Tutorial.</p>  
    <p>SQL Tutorial.</p>  
    <p>HTML Tutorial.</p>  
    <p>CSS Tutorial.</p>  
    </body>  
    </html>   
```

2) **CSS display inline-block**

The CSS display inline-block element is very similar to inline element but the difference is that you are able to set the width and height.

```css
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    p {  
    display: inline-block;   
    }  
    </style>  
    </head>  
    <body>  
    <p>Hello Javatpoint.com</p>  
    <p>Java Tutorial.</p>  
    <p>SQL Tutorial.</p>  
    <p>HTML Tutorial.</p>  
    <p>CSS Tutorial.</p>  
    </body>  
    </html>  
```

3) **CSS display block**

The CSS display block element takes as much as horizontal space as they can. Means the block element takes the full available width. They make a line break before and after them. 

```html
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    p {  
    display: block;   
    }  
    </style>  
    </head>  
    <body>  
    <p>Hello Javatpoint.com</p>  
    <p>Java Tutorial.</p>  
    <p>SQL Tutorial.</p>  
    <p>HTML Tutorial.</p>  
    <p>CSS Tutorial.</p>  
    </body>  
    </html>  
```
### CSS Position
***


The CSS position property is used to set position for an element. it is also used to place an element behind another and also useful for scripted animation effect.

You can position an element using the top, bottom, left and right properties. These properties can be used only after position property is set first. A position element's computed position property is relative, absolute, fixed or sticky.

Let's have a look at following CSS positioning:

* CSS Static Positioning
* CSS Fixed Positioning
* CSS Relative Positioning
* CSS Absolute Positioning

1) **CSS Static Positioning**

This is a by default position for HTML elements. It always positions an element according to the normal flow of the page. It is not affected by the top, bottom, left and right properties.

2) **CSS Fixed Positioning**

The fixed positioning property helps to put the text fixed on the browser. This fixed test is positioned relative to the browser window, and doesn't move even you scroll the window. 

```html
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    p.pos_fixed {  
        position: fixed;  
        top: 50px;  
        right: 5px;  
        color: blue;  
    }  
    </style>  
    </head>  
    <body>  
      
    <p>Some text...</p><p>Some text...</p><p>Some text...</p><p>........</p><p>.... ...</p  
    ><p>........</p><p>........</p><p>........</p><p>........</p>  
    <p>........ </p><p>........</p><p>........</p><p>........</p><p>........</p>  
    <p>........</p><p>........</p><p>Some text...</p><p>Some text...</p><p>Some text...</p>  
    <p class="pos_fixed">This is the fix positioned text.</p>  
    </body>  
    </html>  
```

3) **CSS Relative Positioning**

The relative positioning property is used to set the element relative to its normal position. 

```html
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    h2.pos_left {  
        position: relative;  
        left: -30px;  
    }  
    h2.pos_right {  
        position: relative;  
        left: 30px;  
    }  
    </style>  
    </head>  
    <body>  
    <h2>This is a heading with no position</h2>  
    <h2 class="pos_left">This heading is positioned left according to its normal position</h2>  
    <h2 class="pos_right">This heading is positioned right according to its normal position</h2>  
    <p>The style "left:-30px" subtracts 30 pixels from the element's original left position.</p>  
    <p>The style "left:30px" adds 30 pixels to the element's original left position.</p>  
    </body>  
    </html>  
```

4) **CSS Absolute Positioning**

The absolute positioning is used to position an element relative to the first parent element that has a position other than static. If no such element is found, the containing block is HTML.

With the absolute positioning, you can place an element anywhere on a page.

```html
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    h2 {  
        position: absolute;  
        left: 150px;  
        top: 250px;  
    }  
    </style>  
    </head>  
    <body>  
    <h2>This heading has an absolute position</h2>  
    <p> The heading below is placed 150px from the left and 250px from the top of the page.</p>  
    </body>  
    </html>  
```

### CSS Units
***

There are various units in CSS to express the measurement and length. A CSS unit is used to determine the property size, which we set for an element or its content. The units in CSS are required to define the measurement such as margin: 20px; in which the px (or pixel) is the CSS unit. They are used to set margin, padding, lengths, and so on.

We cannot apply the whitespace between the number and the unit. The unit can be omitted for the value 0. Some properties of CSS allow the negative values of length.

**Absolute lengths**

These are the fixed-length units, and the length expressed using the absolute units will appear as exactly that size. It is not recommended to use on-screen, because the size of the screen varies too much. So, the absolute units should be used when the medium of output is known, such as the print layout.
Absolute units are useful when the responsiveness is not considered in a project. They are less favorable for the responsive sites because they do not scale when the screen changes.

Example-

```html
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    body{  
    text-align: center;  
    }  
    </style>  
    </head>  
    <body>  
    <h1> Absolute units </h1>  
    <p style = "font-size: 20px;" > It has a font-size: 20px; </p>  
    <p style = "font-size: 1.2cm;" > It has a font-size: 1.2cm; </p>  
    <p style = "font-size: .7in;" > It has a font-size: .7in; </p>  
    <p style = "font-size: 18pt;" > It has a font-size: 18pt; </p>  
    <p style = "font-size: 2pc;" > It has a font-size: 2pc; </p>  
    <p style = "font-size: 10mm;" > It has a font-size: 10mm; </p>  
    </body>  
    </html>  
```

**Relative lengths**

Relative units are good to style the responsive site because they scale relative to the window size or the parent. They specify the length, which is relative to another length property.

Depending on the device, if the size of the screen varies too much, then the relative length units are the best because they scale better between the different rendering mediums. We can use the relative units as the default for the responsive units. It helps us to avoid update styles for different screen sizes.

```html
    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    body{  
    text-align: center;  
    }  
    p{  
    line-height: 0.1cm;  
    color: blue;  
    }  
    </style>  
    </head>  
    <body>  
    <h1> Relative units </h1>  
    <p style = "font-size: 2em;" > It has a font-size: 2em; </p>  
    <p style = "font-size: 8ex;" > It has a font-size: 8ex; </p>  
    <p style = "font-size: 6ch;" > It has a font-size: 6ch; </p>  
    <p style = "font-size: 4rem;" > It has a font-size: 4rem; </p>  
    <p style = "font-size: 4vw;" > It has a font-size: 4vw; </p>  
    <p style = "font-size: 10vh;" > It has a font-size: 10vh; </p>  
    <p style = "font-size: 10vmin;" > It has a font-size: 10vmin; </p>  
    <p style = "font-size: 8vmax;" > It has a font-size: 8vmax; </p>  
    <p style = "font-size: 400%;" > It has a font-size: 400%; </p>  
    </body>  
    </html>  
```

![](https://static.javatpoint.com/csspages/images/css-units2.png)


### CSS Specificity

When more than one conflicting rules of CSS indicates the same element, then the browser will follow some rules for determining the particular one. Specificity is the way which helps the browsers to decide which property value is most relevant for the element. It determines which style declaration is applied to an element.

Before going in deep about specificity, let's discuss some points about it:

 *   The CSS specificity is important only when various selectors are affecting the same element. In this case, the browser needs a way to identify the style to be applied to the matching element, and CSS specificity is the way of doing it.

 *   When two or more selectors have equal specificity value, then the latest one considers.

 *   Universal selectors (*) and the inherited values have lower specificity, i.e., 0 specificity.

 *   The style property has a greater specificity value compare to the selectors (except the !important in the stylesheet selector).

  *  The !important alter the selector specificity. When two selectors have equal specificity, then the selector having !important
