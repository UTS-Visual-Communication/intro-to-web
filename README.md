# Introduction to The Web

## Overview of Class for 14th of August

### CSS with focus on typography
* andrew will give you a template file which shows students how they can use css to control the style of the type
* take them through controlling the basic style of the font
* first font-family, and explain how their are common web-safe fonts available on machines
* see this link for a list https://www.w3schools.com/cssref/css_websafe_fonts.asp
* get them to set font-family for one of their type elements, it tries to load the first font specified in this list, and if this is not available the next one and so on. i.e. font-family: "Times New Roman", Times, serif;
* so you cannot just use any font available on your system, as the person looking at your web page somewhere else might not have that font on their system. we will show them how you can get around this next 
* then go through the rest of the properties in the template stylesheet provided
* give them time to play around with these


### How to use web fonts
* for this we will just be using google's web fonts
* goto https://fonts.google.com/
* look at a font
* click select this font
* click family selected
* then on customise, here you can select which weight/s you want to use
* get students to pick one weight
* click on embed
* copy the standard embed link i.e. <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
* and get them to paste it above where they import their style sheet, this is so that the fonts are referenced BEFORE they load their own style sheet and use them
* get them to go into their style sheet and for one of their type element tags (i.e. h1) copy the 'specify in css' from Google Fonts i.e. font-family: 'Roboto', sans-serif; as a property for their style
* save the file and refresh their version so they can see if their Google font has loaded


### Basic Layout
* for this you will just be taking them through applying padding and margin to the type elements i.e. adding white space

### How to sketch up a layout
* Students think up how they want to arrange the content, what content they want and sketch up a layout over the (looong) break until the next class. They can also work on the HTML in this time.

## Overview of Class for 7th of August

### Download these files first. These are the files that students will be working with in class
* https://github.com/clavis-magna/intro-to-web/archive/master.zip

### How the web works
* get students to download the example files
and to open the index.html file (in 1.1-basic-web-page) up in the web browser (Chrome)
* they will see the url starts will file:// this means we are viewing the file locally. Just like when you open a file on your computer.
* get them to go to the assignment url it starts with http, explain that this means we are viewing the page over the internet. Basically when you put in a url, your computer requests files from a server that is hosting them, with this basic web page the browser interprets the html and the css files and displays it in the browser window
* the html (stands for hypertext markup language) describes the content of the page (i.e. the text, and what type of content the text is)
* the css (stands for cascading style sheet) styles the page

### Course Tools
* we use Brackets to edit the html
* we use Chrome to test out our files
* get them to open the html file up in Brackets
* go through the basic document structure
* html is a markup langauge
* it uses ‘tags’ to describe the content of the page
* head tag just contains information about the file
* body tag contains information about what to display in the browser window, they will be mainly changing things inside the body tags
* look at the code and change something in one of the html tags
* then go back to the local file and refresh it, they can see the changes
* each time they make a change they need to refresh (if they are viewing the file locally)

### Uploading a file to the server (we give them a base file) - we have a setup now that students will be using throughout their degree, will give you details on how this works.
* You can find a PDF that overviews this process on UTSOnline see Subject Documents > Getting Your Work Online (Server Instructions)
* We have asked for a folder to be made for each of you, once it is available we will let you know and you an go through this process before your class on Tuesday.
* We also have some little tutorials on different things in the 'Web Task Tutorials' folder which the students can access or you can too!
* Lead the students through the material that is in the PDF
* This will take a while to heard them through this
* Get them to upload the index.html file that is inside 1.1-basic-web-page
* Then go to their URL and check it (make sure they are not viewing the file locally)
* Change something locally and then upload again and refresh their URL
* You don’t need to upload every time you make a change
* Explain to them that you can work on your file and view locally, and then upload when you are happy with all of your edits

### Basic HTML elements (i.e. h, p , img)
* get them to drag the 1.2-basic-tags folder to the Brackets icon, this shows the whole working folder on the left hand panel of Brackets. Click on index.html
* talk through the different html tags
* When we have everything from a start tag to an end tag, it is is called a HTML element, some html elements have content, which is placed between the tags, some html elements like the br or img elements do not, these tags close and open in the one tag, see the img tag in the example.
* Go through each of the tags h1 - h6 is the hierarchy of headings, with h1 the most semantically
* If time get them to open up 1.3-basic-visual-heirachy. HTML tage are semantic, we can see how the different tags denote what types of content the text is and creates a semantic hierarchy of information. The browser also does a basic stylised interpretation of this i.e. headings a bold and of different sizes and paragraph text is regular weight.
* We have also given them the basic text of the Emil Ruder essay 'Rhythm' that they will be working with (1.4-page-with-copy-text). They should have a read of this over the week and also have a go at applying tags to the content. And to bring that file in next week.
* They should also read through the brief online, https://monicamonin.github.io/intro-to-web/, and bring any questions that have to you next week.
