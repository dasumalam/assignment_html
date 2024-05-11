
**Que:-1 Are the HTML tags and elements the same thing?**

**Ans:**
 
  <u>**HTML tag:**</u>
             
HTML Elements are components that are used in HTML Page. 
HTML Tags usually exist in pairs consisting of a starting and an ending tag. 
some tags do not have a closing tag.
 
 <u>**Elements:**</u>
          
The content inside is typically displayed in italic. 
`<i>` tag is often used to indicate a technical term, a phrase from another 
language, a thought, a ship name, etc. 
Use the `<i>` element only when there is not a more appropriate semantic element.        

**For Example:👍**

```html
         <em> (emphasized text) <strong> (important text)
```

---

**Que:-2 What are tags and attributes in HTML?**

**Ans:**

<u>**Tags:**</u>

The basic structure of an HTML document includes tags, which surround content and apply meaning to it.
To get back to the point, `<html>` is the opening tag that kicks things off and tells the browser that everything between that and the `</html>` closing tag is an HTML document. 
The stuff between `<body>` and `</body>` is the main content of the document that will appear in the browser window.
The `</body>` and `</html>` put a close to their respective elements.

 **For Example:👍**

```html 
        <html>
        <head>
        <title> hii sir</title>
        </head>
        <body>
              GOOD MORNINIG SIRRR
              WELCOME TO MY COLLEGE
        </body>
        </HTML>
```

<u>**Attributes:**</u>

Tags can also have attributes, which are extra bits of information. Attributes appear inside the opening tag and their values sit inside quotation marks.
HTML  Attributes can be used to change the color,size OR Functionality of HTML elements.

          
  
**For Example:👍**
```html
            <img src="/image/img2.jpg" alt=""/>

        City:
        <select name="" id="" required>
          <option value="">Baroda</option>
          <option value="">Rajkot</option>
          <option value="">Surat</option>
          <option value="">Junagadh</option>
          <option value="">jamnagae</option>
          <option value="">pune</option>
          <option value="">shikago</option>
          <option value=""> Kanpur</option>
        </select>
    
         <input type="email" name="" id="">

```
        
Most of the HTML elements are surrounded by start and end tags to specify the starting and end of the element.

---

**Que:-3 What are void elements in HTML?** 

**Ans:**

<u>**Void Elements:**</u>

There is a special group of elements that only have start tags and does not contain any content within it, these elements are called void elements.
Void elements doesn’t have ending tags and can only have attributes but do not contain any kind of content. 
These elements can have backslash before ending of start tag but that is completely optional. 

**For Example👍** 

        <br>, <hr>, <img>, <input>, <link>, 
        <base>, <meta>, <param>, <area>, 
        <embed>,<col>, <track>, <source> etc.

---

**Que:-4  What are HTML Entities?** 

**Ans:**        

HTML Entity provides some methods to display reserved characters. 
Reserved characters are those characters that are either reserved for HTML or those that are not present in the basic keyboard.
For instance, `‘<‘` is reserved in HTML language. if the less than `(<)` or greater than `(>)` signs are used in the code, it might be possible that the browser may think as a tag.
this character needs to be displayed on the web page which creates ambiguity in the code. 
Along with these are the characters that are normally not present in basic keyboards `( £, ¥, €, © )`, etc. 
HTML provides some Entity names and Entity numbers to use these symbols. Entity names are case-sensitive. 
Entity numbers are easy to learn. 

**For Examplae:👍**    
 
 ```html  

<p>I will display &amp;	</p>
<p>I will display &copy;</p>
<p>I will display &nbsp; </p>

Output:

 I will display &	
 I will display ©
 I will display    

 ```

---

**Que:-5 What are different types of lists in HTML?**

**Ans:**

HTML lists come in three main categories: 
               ` unordered lists, 
                ordered lists,
                definition lists.`
Each type serves a specific purpose and can be customized to fit your design and content needs.

 **For Example: 👍**
```html 
 
 <html>
    <head>
        <title> fast food List</title>
     </head>
    <body>
         </a>
        <ol> 
            <h1> 1.GIR GAMTHI</h1>
            <ul type="1">
                <li>Panir tika</li>
                 
                <li>Dal Fray</li>
                <li>soup </li>

                        <ul type="disk">
                            <li> Tomato soup</li>
                            <li> veg manchow soup</li>
                        </ul>
                      </li>
                  </ul>
              </ol>
        <ol>
                    <h2>2. SARAZA</h2>
            <ul type="1">
                <li> Pizza </li>
                <ul type="disk">
                    <li> Margherita</li>
                    <li> peppy panner</li>
                    <li>Cheese and Tomato Pizaa</li>
                </ul>
                <li> Dosa </li>
                <ul type="disk ">
                    <li> Plain Dosa </li>
                    <li> Masala Dosa</li>
                </ul>
                <li> ice-cream </li>
                <ul type="disk">
                    <li>Mawa Masti </li>
                    <li>Cean Berry</li>
                </ul>
            </ul> 
        </ol>
    </body>

</html>
```

---

**Que:-6 What is the ‘class’ attribute in HTML?** 

**Ans:**

The class attribute specifies one or more classnames for an element.
The class attribute is mostly used to point to a class in a style sheet. 
However, it can also be used by a JavaScript (via the HTML DOM) to make changes to HTML elements with a specified class.

**Fro Example:👍**

```html
<html>
<head>
<style>
h1.intro {
  color: blue;
}

p.important {
  color: green;
}
</style>
</head>
<body>

<h1 class="intro">Header 1</h1>
<p>A paragraph.</p>
<p class="important">Note that this is an important paragraph.</p>

</body>
</html>
```
---

**Que:-7 What is the difference between the ‘id’ attribute and the ‘class’ attribute of HTML elements?**

**Ans:**

The only difference between them is that “id” is unique in a page and can only apply to at most one element, while “class” selector can apply to multiple elements. 

<u>**difference between the ‘id’ attribute and the ‘class’ attribute**</u>

 `ID Attribute`|	`Class Attribute`
 -------------|----------------
Uniquely identifies one element.|Can be applied to multiple elements.
Primarily used for styling or JavaScript.|	Also used for styling or JavaScript.
Only one element can have a specific ID.|	Multiple elements can share the same class.
Written as id="example".|	Written as class="example".
Accessed in CSS with #example selector.|	Accessed in CSS with .example selector.
Often used for unique page elements.|	Commonly used for styling groups of elements.

---

**Que:-8  What are the various formatting tags in HTML?**

**Ans:**

Text formatting in HTML refers to the way text is displayed on a web page. It is the process of applying various styles, colors, fonts, sizes, and other visual enhancements to text content within an HTML document.    
HTML offers a range of tags that can be used to 
format text, including: Bold text: `<b>` or `<strong>`
        
<u>**Formatting elements were designed to display special types of text:**</u>
```html
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text
```
**For Example:👍**
```html
      <html>
         <body>
                <p><b>This text is bold</b></p>
                <p><i>This text is italic</i></p>
                <p>This is<sub> subscript</sub> 
                and <sup>superscript</sup></p>
                </body>
                </html>
```

---

**Que:-9 How is Cell Padding different from Cell Spacing?**

**Ans:** 
  
  Cell padding is used to create a border around the content area of a web page, whereas cell spacing is used for positioning elements (such as images or text) within that content area. Cell padding can be set through CSS, while cell spacing can only be controlled using HTML5.

  <u>**differences between Cell padding and cell spacing**</u>
 `Cellpadding` | `Cellspacing`
-----------|--------------
Cell padding is the term used to describe the area between a table cell’s border and its content. | The gap between each neighbouring cell is often called “cellspacing.”|
It may be made using the HTML table> tag but changes the type property to cell padding.	|It may be produced using the HTML table> tag. However, that changes the type property to cell spacing.|
It concerns just one cell.|It is exposed to several cells (more than one) at once.
|The default value for cell padding is 1.|Cellspacing has a default value of 2.
|When compared to cell spacing, it is quite effective. It is, therefore, very commonly used.|Comparatively speaking, it is less efficient than cell padding.

---

**Que:-10 How can we club two or more rows or columns into a single row or column in an HTML table?**

**Ans:**

To merge two or more row cells, use the rowspan attribute. If you want to combine the first two cells in the first column, you can use the colspan="2" attribute in the first tag. The number represents how many cells to use (merge) for the tag.

**For Examaple:👍**

```html
<html>
    <head>
        <title> chinu malam</title>
    </head>
    <style>
        tr:hover{
                 
            color: rgb(227, 37, 37);
        }
    </style>
    <caption>
        <font color=" darkgreen" align="center">
                    <h1>Time Table</h1> 
    </caption>
    

    </style>
     <body>
        <table border="3" align="center" style="background-color: rgb(255, 251, 199);" style="top: 0px;" >
        <tr style="color: rgb(0, 0, 0);">
           <th> <h2> Day/Lecture </h2></th>
            <th> <h2> 9 to 10 </h2> </th>
            <th><h2>10 to 11 </h2> </th>
            <th><h2> 11 to 12 </h2></th>
            <th><h2> 12 to 1</h2> </th>
            <th> <h2>1 to 2 </h2></th>
            <th> <h2> 2 to 3 </h2></th>
            <th><h2> 3 to 4 </h2> </th>
            <th> <h2>4 to 5 </h2> </th>
        </tr>
         <tr>
            <td style="color: black;"><h2> monday </h2></td>
            <td style="color: chocolate;" ><h3> Eng </h3></td>
            <td style="color: darkgreen;"><h4>Mat </h4> </td>
            <td style="color:  darkgreen;"><h3>Mat </h3></td>
            <td rowspan="5" style="color: brown;"><h2> lunch </h2></td>
            <td colspan="3" style="color: cornflowerblue;"><h3> LAB </h3> </td>
            <td style="color: maroon;"> <h3>phy </h3></td>
         </tr>
         <tr>
         <td style="color: black;"><h2>Tuesday </h2>  </td>
         <td colspan="3" style="color: cornflowerblue;"><h3> LAB </h3></td>
         <td style="color:chocolate"> <h3> Eng </h3></td>
         <td style="color: darkgreen;"> <h3>Mat </h3> </td>
         <td style="color: darkgreen;"> <h3>Mat </h3>  </td>
         <td> <h3> SPORTS </h3> </td>
        </tr>

        <tr>
             <td style="color: black;"><h2>Wednesday </h2>  </td>
             <td style="color: darkgreen;"><h3>Mat </h3> </td>
             <td style="color: maroon;"> <h3>Phy </h3></td>
             <td style="color: chocolate;"> <h3> Eng </h3> </td>
             <td style="color: fuchsia;"> <h3>Che</h3></td>
             <td colspan="3"><h3> LIBRARY </h3> </td>
        </tr>
        <tr> 
            <td style="color: black;"><h2>Thersday </h2></td>
            <td style="color: maroon;"><h3> Phy </h3> </td>
            <td style="color: chocolate;"><h3> Eng </h3> </td>
            <td style="color: fuchsia;"> <h3>Che</h3> </td>
            <td colspan="3" style="color: cornflowerblue;"> <h3> LAB </h3></td>
            <td style="color: darkgreen;"> <h3>Mat </h3>  </td>
        </tr>

         <tr>
        <td style="color: black;"><h2>Friday </h2></td>
        <td style="color: maroon;"> <h3>Phy </h3></td>
        <td style="color: chocolate;"><h3> Eng </h3></td>
        <td style="color: fuchsia;"><h3>Che</h3></td>
        <td colspan="3" style="color: cornflowerblue;"><h3> LAB </h3></td>
        <td style="color: darkgreen;"> <h3>Mat </h3> </td>
        </tr>

        </table>
    </body>
</html>
```
---

**Que:-11 What is the difference between a block-level element and an inline element?**

**Ans:**

The inline and block elements of HTML are one of the important areas where web developers often get confused because they were unable to know which are inline and block elements which may cause clumsiness in a webpage in case he assumes some element to be a block but it is an inline element which causes next element comes next to it.

So let us see the differences between the inline and block elements in HTML and the different frequently used inline and block HTML elements. 

<u>**Block elements:**</u>

 They consume the entire width available irrespective of their sufficiency. They always start in a new line and have top and bottom margins. It does not contain any other elements next to it.

**Examples of Block elements:👍**
```html
<h1>-<h6> : This element is used for including headings of different sizes ranging from 1 to 6.
<div>: This is a container tag and is used to make separate divisions of content on the web page.
<hr>: This is an empty tag and is used for separating content by horizontal lines.
<li>: This tag is used for including list items of an ordered or unordered list.
<ul>: This tag is used to make an unordered list.
<ol>: This tag is used to make an ordered list.
<p>: This tag is used to include paragraphs of content in the webpage.
<table>: This tag is used for including the tables in the webpage when there is a need for tabular data. 
```
<u>**Inline elements:**</u>

 Inline elements occupy only enough width that is sufficient to it and allows other elements next to it which are inline. Inline elements don’t start from a new line and don’t have top and bottom margins as block elements have.

**Examples of Inline elements:👍**
```html
<a>: This tag is used for including hyperlinks in the webpage.
<br>: This tag is used for mentioning line breaks in the webpage wherever needed.
<input>: This tag is used for taking input from the users and is mainly used in forms.
<img>: This tag is used for including different images in the webpage to add beauty to the webpage.
<span>:  This is an inline container that takes necessary space only.
<b>:  This tag is used in places where bold text is needed.
<label>: The tag in HTML is used to provide a usability improvement for mouse users i.e, if a user clicks on the text within the <label> element, it toggles the control.
```

---

**Que:-12 How to create a Hyperlink in HTML?** 

 **Ans:**

To make a hyperlink in an HTML page, use the `<a>`and `</a>` tags, which are the tags used to define the links. The  `<a>` tag indicates where the hyperlink starts and the `</a>` tag indicates where it ends. Whatever text gets added inside these tags, will work as a hyperlink. Add the URL for the link in the `<a herf="">`.

**For Example:👍**
```html
<html>
    <head>
        <title> web page</title>
    </head>
<body>
<a href="https://thumbor.forbes.com/thumbor/fit-in/900x510/https://www.forbes.com/advisor/wp-content/uploads/2023/07/top-20-small-dog-breeds.jpeg.jpg"> Dog</a>   
</body>
</html>
```

---

**Que:-13What is the use of an iframe tag?**

**Ans:**

   An inline frame (iframe) is a HTML element that loads another HTML page within the document. It essentially puts another webpage within the parent page. They are commonly used for advertisements, embedded videos, web analytics and interactive content.

**For Example:👍**

```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <iframe width="500" height="300" src="https://www.youtube.com/embed/nOvTk0Ll_Sg?si=LBlqR2ybRelgvV1H"
     title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; 
     -media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" 
     allowfullscreen>
    </iframe><br>
    
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d26997.53251957014!2d77.16652019156676!3d32
    .239470379111786!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39048708163fd03f%3A0x8129a80ebe5076cd!
    2sManali%2C%20Himachal%20Pradesh!5e0!3m2!1sen!2sin!4v1714453816408!5m2!1sen!2sin" width="500" 
    height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
</iframe>
   
</body>
</html>
```

---

**Que:-14What is the use of a span tag? Explain with example?**

**Ans:**

 The `<span>` tag is an inline container used to mark up a part of a text, or a part of a document.
 The `<span>` tag is easily styled by CSS or manipulated with JavaScript using the class or id attribute.
 The `<span>` tag is much like the `<div>` element, but `<div>` is a block-level element and `<span>` is an inline element.

**For Example:👍**
```html
<html>
<body>

<h1>The span element</h1>

<p> My mother has <span style="color:blue;font-weight:bold">blue</span> 
eyes and my father has <span style="color:darkolivegreen;font-weight:bold">dark green</span> eyes.
</p>

</body>
</html>
```

---

**Que:-15How to insert a picture into a background image of a web page?**

**Ans:**

 We can use the background attribute in the body tag to set an image as the background of the webpage. We will need to specify the URL or the location of the image which we want to set to the background attribute of the body tag.

**For Example:👍**
```html
 <html>
<head>
<style>
body {  background-image:url(htitute-logo1651830982.png)
}
</style>
</head>
<body>

<h2>Background Image</h2>

<p>Best IT & Software Training Institute of Rajkot for Training & Placements -TOPS Offers Best Computer Classes </p>

</body>
</html>
```

---

**Que:-16 How are active links different from normal links?**

**Ans:**

<u>**Active Link:**</u>


An Active link is a hyperlink that is currently being interacted with the user. Whenever the user holds the mouse button on the link and not released yet or if right clicked on it, it will change its color into red, this is when the link will be in active state.

The active state is temporary and ends once the user releases the mouse button. However, we can customize the style of the active links using the CSS properties

**For Example:👍**
        
   ```html     
<html>
    <head>
        <title>
            chinu malam
        </title>
    </head>
    <style>
        tr:hover{
            background-color: rgb(19, 7, 10);
            color: rgb(207, 207, 149);
        }
    </style>
    <caption>
        
        <td> <font color="black" align="center" hight="5" wight="5">
                 <h1> ENQUIRY FORM</h1>
        </td>
    </caption>
    <body>
        <table border="2" align="center">
            <thead>
                <tr>
                    <td>
                    <th colspan="5" align="center ">
                        Fill The Form 
                    </th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Name</td>
                    
                    <td colspan="5"></td>
                </tr>
                <tr>
                    <td>Password</td>
                    <td colspan="5"> </td>
                </tr>
                
                <tr>
                    <td>Gender</td>
                    <td>
                        <input type="radio" name="gender" value="Male">Male
                        <input type="radio" name="gender" value="FeMale">FeMale
                        
                    </td>
                
                </tr>
                <tr>
                    <td>Subject</td>
                    <td><input type="checkbox" name="Subject" value="Web">web</td>
                    <td><input type="checkbox" name="Subject" value="Math">Math</td>
                    <td><input type="checkbox" name="Subject" value="Graphics"> Graphics</td>
                    <td><input type="checkbox" name="Subject" value="English"> English</td>
                    
                 </tr>
                 <tr align="left">
                    <td> Feddback</td>
                    <td>
                        <textarea rows="4" cols="25" style="overflow: scroll;"></textarea>
                    </td>
                 </tr>
                      
                 </tr>
                 
            </tbody>

        </table>
    </body>
</html>
```

---

**Que:-17 What are the different tags to separate sections of text?**

**Ans:**

 We separate a section of texts in HTML using the below tags: `<br>` tag – It is used to separate the line of text. It breaks the current line and shifts the flow of the text to a new line. `<p>` tag–This tag is used to write a paragraph of text.

**For Example:👍**

 ```html
 <html>
<body>
    <section>
        <h1>Monday</h1>
        <p>Monday</p>
    </section>
    <section>
        <h1>tops</h1>
        <p>tops</p>
    </section>
    <section>
        <h1> Pizaa</h1>
        <p>Pizaa</p>
    </section>
</body>
</html>
```

---

**Que:-18 What is SVG?**

**Ans:-**

        SVG stands for Scalable Vector Graphics
        SVG is used to define vector-based graphics for the Web
        SVG defines graphics in `XML` format
        Each element and attribute in SVG files can be animated
        SVG is a W3C recommendation
        SVG integrates with other standards, such as `CSS, DOM, XSL and JavaScript`

**For Example:👍**
```html
<html>
<body>

<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
</svg>

</body>
</html>
```

---

**Que:-19 • What is difference between HTML and XHTML?**

**Ans:**
  
  <u><h4> Difference between HTML and XHTML</h4></u>

`HTML`|`XHTML`
----|-----
HTML stands for Hypertext Markup Language.|	XHTML stands for Extensible Hypertext Markup Language.
It was developed by Tim Berners-Lee.|	It was developed by W3C i.e World Wide Web Consortium.
It was developed in 1991.|It was released in 2000.
It is extended from SGML.|	It is extended from XML and HTML.
The format is a document file format.|	The format is a markup language.
All tags and attributes are not necessarily to be in lower or upper case.|	In this, every tag and attribute should be in lower case.
Doctype is not necessary to write at the top.|	Doctype is very necessary to write at the top of the file.
It is not necessary to close the tags in the order they are opened.|	It is necessary to close the tags in the order they are opened.
While using the attributes it is not necessary to mention quotes.  For e.g. `<Geeks>`. |	While using the attributes it is mandatory to mention quotes.  For e.g. `<Geeks=”GFG”>`.
Filename extension used are .html, .htm.|	Filename extension are .xhtml, .xht, .xml.
Lewd structure is used in HTML|It contains a very strict structure.

---

**Que:-20 What are logical and physical tags in HTML?**

**Ans:**

Physical and Logical tags are used in HTML for better visibility and understanding of the text by the user on the web page. However, both tags differ from each other as suggested by their names.

<u>**Logical Tags:**</u>
        
Logical Tags are used in HTML to display the text according to the logical styles. Following are the Logical tags commonly used in HTML.

<u>**Logical Tags:**</u>

```html
Tag	        Description
<abbr>	        Defines an abbreviation
<acronym>	Defines an acronym
<address>	Defines an address element
<cite>	        Defines citation
<code>	        Defines computer code text
<blockquote>	Defines a long quotation
<del>	        Defines text
```
<u>**Physical Tags:**</u>

Physical Tags are used in HTML to provide actual physical formatting to the text. Following are the Physical tags commonly used in HTML.

<u>**Physical Tags:**</u>
```html
Tag	Description
<b>	Defines bold text
<big>	Defines big text
<i>	Defines italic text
<small>	Defines small text
<sup>	Defines superscripted text
<sub>	Defines subscripted text
<tt>	Defines teletype text
<u>	Deprecated. Use styles instead
```     
---