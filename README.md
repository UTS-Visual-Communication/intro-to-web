# Introduction to The Web

## Overview of Class for 30th of July

Please take a look through these overviews before class so that you are prepared. If you are not up to speed on basic web programming we suggest working through these steps in your own time.

These short lectures could also be worthwhile watching over the weeks as well http://www.dontfeartheinternet.com/

### Download these files first. These are the files that students will be working with in class
* https://github.com/UTS-Visual-Communication/intro-to-web-resources

### How the web works
* get students to download the example files from GitHub (URL above)
* then to open the index.html file that is inside 1.1-basic-web-page up in the web browser (Chrome)
* they will see the url starts will file:// explaon that this means we are viewing the file locally i.e. the browser is reading the file that is on the computer. Just like when you open a file on your computer in any other program.
* get them to go to the assignment url (https://uts-visual-communication.github.io/intro-to-web/) it starts with http, explain that this means we are viewing the page over the internet. Basically when you put in a url, your computer requests files from a server that is hosting them, with this basic web page the browser interprets the html and the css files and displays it in the browser window
* the html (stands for hypertext markup language) describes the content of the page (i.e. the text, and what type of content the text is)
* the css (stands for cascading style sheet) styles the page

### Take students through the brief
* Talk students through what is required of them (see brief)
* Ask if they have any questions from the lecture / about the brief

### Take them through subject tools
* we use Brackets to edit the html, Brackets is available on all of the Level 3 machines. Brackets is free they can download it on their own machines.
* we use Google Chrome to test out our files
* get them to open the html file up in Brackets
* go through the basic document structure
* html (hypertext markup language) is a markup langauge
* it uses ‘tags’ to describe or 'mark up' the content of the page
* notice how there are opening tags and closing tags. Tags describe the content that is between their opening and closing
* head tag just contains information about the file that the browser uses to understand the file and display it
* body tag contains information about what to display in the browser window, they will be mainly changing things inside the body tags
* look at the code and change something the h1 tags, and save the file
* then go back to the browser and refresh it, they can see the changes
* each time they make a change they need to save and refresh 

### Uploading a file to the server (we give them a base file) - we have a setup now that students will be using throughout their degree, will give you details on how this works.
* You can find a PDF that overviews this process on UTSOnline see Subject Documents > Getting Your Work Online (Server Instructions)
* We have asked for a folder to be made for each of you (these should be available from Friday, you will get an email to your UTS staff email account)
* We also have some little tutorials on different things in the 'Web Task Tutorials' folder which the students can access or you can too!
* Lead the students through the material that is in the PDF
* This will take a while to heard them through this (maybe the WHOLE class)
* Get them to upload the index.html file that is inside 1.1-basic-web-page
* Then go to their URL and check it (make sure they are not viewing the file locally - get them to check that it starts with http)
* Change something in their file locally and then upload again and refresh their URL
* You don’t need to upload every time you make a change
* Explain to them that you can work on your file and view locally, and then upload when you are happy with all of your edits
* If you have a generous amount of time left you could take them through the Basic HTML Elements (see first section of next week)

### For next week
* Students watch out for a place/structure they want to do their web page on according to the Vanessa Berry-led categories. Recommend taking a quick snap on their smartphone when they see something of interest!


## Overview of Class for 6th of August

### Basic HTML elements (i.e. h, p , img)
* get them to drag the 1.2-basic-tags folder to the Brackets icon, this shows the whole working folder on the left hand panel of Brackets. Click on index.html
* talk through the different html tags
* When we have everything from a start tag to an end tag, it is is called a HTML element, some html elements have content, which is placed between the tags, some html elements like the br or img elements do not, these tags close and open in the one tag, see the img tag in the example.
* Go through each of the tags h1 - h6 is the hierarchy of headings, with h1 the most semantically
* If time get them to open up 1.3-basic-visual-heirachy. HTML tage are semantic, we can see how the different tags denote what types of content the text is and creates a semantic hierarchy of information. The browser also does a basic stylised interpretation of this i.e. headings a bold and of different sizes and paragraph text is regular weight.
* We have also given them the basic text of the Emil Ruder essay 'Rhythm' that they will be working with (1.4-page-with-copy-text). They should have a read of this over the week and also have a go at applying tags to the content. And to bring that file in next week.
* They should also read through the brief online, https://monicamonin.github.io/intro-to-web/, and bring any questions that have to you next week.

### CSS with focus on typography
* andrew will give you a template file which shows students how they can use css to control the style of the type
* get students to download the files and open up the html file, notice the type does not have the default style
* we style our webpages using CSS, cascading style sheet. CSS = Style. HTML = Content.
* we reference an external stylesheet, a CSS file (show them CSS link, and get them to open up the CSS file in the HTML editor)
* take them through how to attach a style to a HTML element i.e. a h1 element
* h1 { } we denote the element we want to style and then have two curly brackets, inside these curly brackets we can style various properties of the element
* i.e. font-style: italic; it's always property: propertyvalue;
* then show them font-family, and explain how their are common web-safe fonts available on machines
* see this link for a list https://www.w3schools.com/cssref/css_websafe_fonts.asp
* get them to set font-family for one of their type elements, it tries to load the first font specified in this list, and if this is not available the next one and so on. i.e. font-family: Arial, Helvetica, sans-serif; see https://www.w3schools.com/cssref/pr_font_font-family.asp
* so you cannot just use any font available on your system, as the person looking at your web page somewhere else might not have that font on their system. we will show them how you can get around this next 
* then go through the rest of the properties in the template stylesheet provided
* give them time to play around with these


### How to use web fonts
* what if we want to use fonts that aren't  system fonts?
* then we can use fonts hosted by someone else or host fonts on our server
* for example typekit has web fonts you can use, but you need to pay for them
* for this we will just be using google's web fonts, as they have ok fonts, are easy to use and free, and will give you a sense of how web fonts work
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
* we can put space between blocks of type within a tyle element using line-height, but if we want to create space between different elements i.e. between a h1 and a p, then we need to using padding/margin
* you can imagine each type element like a block, that spans the width of the web browser
* i.e. if you do h1 {background: yellow;} we can see the 'box', this describes the 'content' area i.e. https://www.w3schools.com/css/css_boxmodel.asp
* if you set the padding i.e. padding: 20px, this will add 20px padding around the entire element on all sides. See what happens
* if we set the margin this creates space between the edge of the box and the next element
* margin is generally the best way to create space between elements
* if you do margin: 0px 0px 20px 0px; this allows you to set different margins for the different sides of the element. this will put a 20px margin between the h1 element and the p element beneath it. the sides are top right bottom left
* for this you will just be taking them through applying padding and margin to the type elements i.e. adding white space


### Placing an Image
* Andrew will give an example showing how to place images, take students through this code - still to come -
* If time show them how to save images to the right size for web. this is a resource for how to do this https://www.taralesher.com/blog/exporting-photoshop-images-for-web


