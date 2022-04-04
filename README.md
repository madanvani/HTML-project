# HTML-project:=

                            HTML Introduction:=

HTML stands for Hyper Text Markup Language.
HTML is used to create static web pages.
HTML is widely used language on the web.
We can create static website by HTML only.
An HTML document is made of many HTML tags and each HTML tag contains different content.
Browsers do not display the HTML tags, but use them to render the content of the page.


                            HTML Syntax:=

An HTML element usually consists of a start tag and end tag, with the content inserted in between:<tagname>Content goes here...</tagname>
All HTML documents must start with a document type declaration: <!DOCTYPE html>.
The HTML document itself begins with <html> and ends with </html>.
Head tag represents the document's header and its start with <head> and close with </head>
The <title> tag is used inside the head tag to mention the document title.
The visible part of the HTML document is between <body> and </body>.
  

                         HTML Basic Tags:=
  
<br> br stands for break line, it breaks the line of the code. It is useful for writing a poem or an address, where the division of lines is significant.
<pre> tag represents preformatted text. Whitespace inside this element is displayed as typed.
<code> tag is used for indicating a piece of code. The code tag surrounds the code being marked up.The code being marked up could represent an XML element name, a filename, a computer program, or any other string that a computer would recognize.



                          HTML Headings:=
                          
A HTML heading or HTML h tag can be defined as a title or a subtitle which you want to display on the webpage. When you place the text within the heading tags it is displayed on the browser in the bold format and size of the text depends on the number of heading.
There are six different HTML headings which are defined with the <h1> to <h6> tags.
<h1> defines the most important heading. <h6> defines the least important heading. Search engines use the headings to index the structure and content of your web pages.


                         HTML Paragraphs:=
                         
HTML paragraph or HTML p tag is used to define a paragraph in a webpage.
It is a notable point that a browser itself add an empty line before and after a paragraph.
The HTML <p> element defines a paragraph.

                     
                           HTML Formatting:=
                           
HTML also defines special elements for defining text with a special meaning.
HTML uses elements like <b> and <i> for formatting output, like bold or italic text.
Formatting elements were designed to display special types of text. 

                          <b> - Bold text - </b>
  <strong> - Important text  -  </strong>
  <i>      - Italic text     - </i>
  <em>     - Emphasized text - </em>
  <mark>   - Marked text     - </mark>
  <small>  - Small text      - </small>
  <del>    - Deleted text    - </del>
  <ins>    - Inserted text   - </ins>
  <sub>    - Subscript text  - </sub>
  <sup>    - Superscript text- </sup>
  
  
                           HTML Comments:=
                           
Comment tags are used to insert comments in the HTML source code.
You can add comments to your HTML source by using the following syntax:
<!-- Write your comments here -->
<!-- Single line comment -->
    
  <!-- Multiline comment
   Here you can write any number of lines
  -->
  
  
                           HTML Background:=
                           
These are the attributes to change web page looking.
Attributes are used inside a tag and it follows att_name="value" format. Ex : text="red"
bgcolor attribute is used to change the background-color in a web page.
text attribute is used to change the text color in a web page.
background attribute is used to set an image as a background in a web page. Here we have to give the whole image url with extension.
  
  
                             HTML Images:=
                             
You can insert any image in your web page by using <img> tag.
The simple syntax to use this tag is <img src="Image URL" ... attributes-list/>
The src attribute is used to give the address of the image with extension.
The alt attribute is a mandatory attribute which specifies an alternate text for an image, if the image cannot be displayed.
You can set image width and height based on your requirement using width and height attributes.
By default image will have a border around it, you can specify border thickness in terms of pixels/value using border attribute. A thickness of 0 means, no border around the picture.
By default image will align at the left side of the page, but you can use align attribute to set it in the center or right.


                             HTML Tables:=
                             
The HTML tables allow to arrange data like text, images, links, other tables, etc. into rows and columns of cells.
The HTML tables are created using the <table> tag in which the <tr> tag is used to create table rows and <td>tag is used to create data cells.
Here border is an attribute of <table> tag and it is used to put a border across all the cells. If you do not need a border then you can use border="0".You can also set border color also using bordercolor attribute.
Table heading can be defined using <th> tag. This tag will be put to replace <td> tag, which is used to represent actual data cell.
There are two attribiutes called cellpadding and cellspacing which you will use to adjust the white space in your table cells.
cellpadding represents the distance between cell borders and the content within a cell.
The cellspacing attribute defines the width of the border.
You will use colspan attribute if you want to merge two or more columns into a single column. Similar way you will use rowspan if you want to merge two or more rows.
bgcolor attribute is used to set background color for whole table or just for one cell.
background attribute is used to set background image for whole table or just for one cell.
You can set a table width and height using width and height attrubutes.
The caption tag will serve as a title or explanation for the table and it shows up at the top of the table.


                                  HTML Lists:=
                                  
HTML offers three ways for specifying lists of information. All lists must contain one or more list elements.
<ul> - An unordered list. This will list items using plain bullets.
The Unordered list starts with <ul> tag and list items start with the <li> tag.
You can use type attribute for <ul> tag to specify the type of bullet you like. By default it is a disc. But you can change to square or circle
<ol> - An ordered list. This will use different schemes of numbers to list your items.
The numbering starts at one and is incremented by one for each successive ordered list tagged with <li>.
You can use type attribute for <ol> tag to specify the type of numbering you like. By default it is a number.
But you can change to Roman Numbers(I),Small roman numbers(i), alphabets(A), small aplhabets (a).
You can use start attribute for <ol> tag to specify the starting point of numbering you need.
<dl> - A definition list. This arranges your items in the same way as they are arranged in a dictionary.
<dl> - Defines the start of the list.
<dt> - Defines a term.
<dd> - Defines term definition


                               HTML Links:=
                               
A webpage can contain various links that take you directly to other pages and even specific parts of a given page. These links are known as hyperlinks.
Hyperlinks allow visitors to navigate between Web sites by clicking on words, phrases, and images.
A link is specified using HTML tag <a>. This tag is called anchor tag and anything between the opening <a>tag and the closing </a> tag becomes part of the link
Following is the simple syntax to use <a> tag.<a href="Document URL" ... attributes-list>Link Text</a>
target attribute is used to specify the location where linked document is opened. Possible options are
_blank Opens the linked document in a new window or tab.
_self Opens the linked document in the same frame.
_parent Opens the linked document in the parent frame.
_top Opens the linked document in the full body of the window.
You can set colors of your links, active links and visited links using link, alink and vlink attributes of <body>tag.
You can create text link to make your PDF, or DOC or ZIP files downloadable. This is very simple, you just need to give complete URL of the downloadable file.
It's simple to use an image as hyperlink. We just need to use an image inside hyperlink at the place of text.


                                  HTML Fonts:=
                                  
Fonts play very important role in making a website more user friendly and increasing content readability.
HTML tag to add style, size, and color to the text on your website.
You can set content font size using size attribute. The range of accepted values is from 1(smallest) to 7(largest). The default size of a font is 3.
You can set font face using face attribute.
You can set font color using color attribute.


                                 HTML Forms:=
HTML Forms are required when you want to collect some data from the site visitor.For example during user registration you would like to collect information such as name, email address, credit card, etc.
There are various form elements available like text fields, textarea fields, drop-down menus, radio buttons, checkboxes, etc.
The HTML <form> tag is used to create an HTML form.
Apart from common attributes, following is a list of the most frequently used form attributes:
action Backend script ready to process your passed data.
method Method to be used to upload data. The most frequently used are GET and POST methods.
target Specify the target window or frame where the result of the script will be displayed. It takes values like _blank, _self, _parent etc.
There are different types of form controls that you can use to collect data using HTML form:
  
Those are:
Single-line text input controls <input type="text" name="name"/>
Password input controls <input type="password" name="pwd" />
Email input controls <input type="email" name="email" />
Number input controls <input type="number" name="number" />
Dae input controls <input type="date" name="date" /> 
Multi-line input controls <textarea rows="5" cols="50" name="description"/>
Checkbox controls <input type="checkbox" name="m1" />
Radio Button controls <input type="radio" name="male" />
Select Box controls <select name="select" ><option value="Maths">Maths</option>
File upload box <input type="file" name="fileupload" accept="image/*" />
Button controls <input type="submit" name="submit" value="Submit" /> 
<input type="reset" name="reset" value="Reset" /> 
<input type="button" name="ok" value="OK" /> 
<input type="image" name="imagebutton" src="/html/images/logo.png" /> 
color <input type="color" name="color" /> 
search <input type="search" name="search" /> 
url <input type="url" name="url" /> 
Some attributes of form controls size, maxlength, checked, multiple, placeholder, value, pattern


                            HTML5:=


HTML5 tutorial provides details of all 40+ HTML tags including audio, video, header, footer, data, datalist, article etc.
HTML5 is a next version of HTML. Here, you will get some brand new features which will make HTML much easier. These new introducing features make your website layout clearer to both website designers and users.
There are some elements like <header>, <footer>, <nav> and <article> that define the layout of a website.
It allows you to play a video and audio file.
<article>-This element is used to define an independent piece of content in a document, that may be a blog, a magazine or a newspaper article.
<audio>-It is used to play audio file in HTML.
<footer> It defines a footer for a section.
<header> It defines a header for a section.
<main> It defines the main content of a document.
<nav>-It is used to define the navigation link in the document.
<progress>-It specifies the progress of the task.
<section>- It defines a section in the document.
<time>- It is used to define a date/time.
<video>-It is used to play video file in HTML.


                            HTML Marquee:=
                            
An HTML marquee is a scrolling piece of text displayed either horizontally across or vertically down your webpage depending on the settings.
This is created by using HTML <marquee> tag.
<marquee attribute_name="attribute_value"....more attributes> Text here </marquee>
Attributes are width This specifies the width of the marquee. This can be a value like 10 or 20% etc.
height This specifies the height of the marquee. This can be a value like 10 or 20% etc.
direction This specifies the direction in which marquee should scroll. This can be a value like up, down, left or right.
scrolldelay This specifies how long to delay between each jump. This will have a value like 10 etc.
scrollamount This specifies the speed of marquee text. This can have a value like 10 etc.
loop This specifies how many times to loop. The default value is INFINITE, which means that the marquee loops endlessly.
bgcolor This specifies background color in terms of color name or color hex value.
hspace This specifies horizontal space around the marquee. This can be a value like 10 or 20% etc.
vspace This specifies vertical space around the marquee. This can be a value like 10 or 20% etc.


                               HTML Audio:=
                               
HTML audio tag is used to define sounds such as music and other audio clips. Currently there are three supported file format for HTML 5 audio tag.
autoplay Specifies that the audio will start playing as soon as it is ready
controls Specifies that audio controls should be displayed (such as a play/pause button etc)
loop Specifies that the audio will start over again, every time it is finished
src Specifies the URL of the audio file


                                 HTML Video:=

HTML 5 supports <video> tag also. The HTML video tag is used for streaming video files such as a movie clip, song clip on the web page.
autoplay Specifies that the audio will start playing as soon as it is ready
controls Specifies that audio controls should be displayed (such as a play/pause button etc)
loop Specifies that the audio will start over again, every time it is finished
src Specifies the URL of the audio file
height pixels Sets the height of the video player
widthSets the width of the video player
poster Specifies an image to be shown while the video is downloading, or until the user hits the play button
