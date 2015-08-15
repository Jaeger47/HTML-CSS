<a name="README"><img src="https://s3-us-west-2.amazonaws.com/testdrivenlearningbucket/htmlcss.png" width="200px" height="200px"/></a>

# HTML/CSS: Tutorial

Use this tutorial as a guide to learn HTML and CSS. Each unit contains an annotated lesson that can assist you in developing your Web Development skills.

Technologies
====================
<img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" width="70px" height="70px" />
<img src="http://ohdoylerules.com/content/images/css3.svg" width="70px" height="70px" />

Topics
================
 - Basics
 - Divs
 - Fonts
 - Hexadecimal Colors
 - Images
 - Links
 - Selectors
 - The Box Model
 - Web Forms
 
Basics.html
====================
```HTML
<!--HTML: Basics-->

<!--HTML: HyperText Markup Language-->
<!--HTML, is the standard markup language used to create web pages-->

<!-- To add content, you should use HTML tags -->
<!-- These pre-defined tags, have opening and closing versions -->


<!-- <!DOCTYPE> tag -->
<!-- Defines the HTML version the browser should use to display the HTML Tags-->
<!-- By writing <!DOCTYPE html> and not specifying the version, the browser will use the latest version-->
<!DOCTYPE html>


<!-- <html> tag -->
<!-- All of the HTML tags are placed inside the <html> tag -->
<!-- You should use it to organize all of the other tags for the Web Page -->
<html>

<!-- <head> tag -->
<!-- All the not-visible content of the web page should be contained on the <head> tag -->
<!-- You can use this tag to load scripts like CSS and Javascript -->

<!--Nesting tags: HTML tags can contain other tags-->
<head lang="en"><!-- the <head> tag is called the parent tag (for <meta> and <title>)-->
    <meta charset="UTF-8">
    <!-- the <meta> tag is called a children tag (of <head>)-->
    <title>HTML Basics</title><!-- the <title> tag is called a children tag (of <head>)-->
</head>

<!-- <link> tag -->
<!-- Allows you to reference other files that work together with this file-->

<!-- The type attribute set to text/css lets the browser know you are loading a CSS file -->
<!-- The rel attribute is short for relationship-->
<!-- The CSS selectors and rules are contained in the CSS file-->
<link rel="stylesheet" type="text/css" href="../CSS/Basics.css"><!-- The <link> is an empty tag, it doesn't have a closing tag -->


<!-- <body> tag -->
<!-- All the visible content of the web page should be contained on the <body> tag -->
<body>

<!-- <h*> headers -->

<!-- You can use heading tags to define your content hierarchy -->
<!-- Higher heading numbers mean the content that appears between the tags is less important -->

<!-- <h1> is an opening tag -->
<h1>Header H1</h1>
<!-- </h1> is an closing tag and has a slash before the tag name-->
<h2>Header H2</h2>

<h3>Header H3</h3>
<h4>Header H4</h4>

<!-- <p> paragraphs -->

<!-- You can use paragraph tags for non-heading text -->
<p>This is a paragraph</p>
<p>This is another paragraph</p>

<!-- <ul> Unordered List -->
<!-- You can use unordered list tags to display a list fo items-->
<ul>
    <!-- <li> list item -->
    <!-- Every list item needs to be put inside of  li tag -->
    <li>List Item 1</li>
    <li>List Item 2</li>
    <li>List Item 3</li>
</ul>

<!-- You can use ordered list tags to display a list fo items in certain order-->
<ol>
    <!-- <li> list item -->
    <!-- Every list item needs to be put inside of  li tag -->
    <li>List Item 1</li>
    <li>List Item 2</li>
    <li>List Item 3</li>
</ol>

</body>
</html>
```
 Basics.css
====================
```CSS
/*CSS*/

/*Set of rules for the styles of HTML elements*/
/*It is used to change the appearance of HTML*/

/*Selectors*/
/*CSS elements that allow you to find HTML elements*/

/*Selectors: Type*/
/* You can create a Type selector by writing the tag name without <> brackets*/
p {
    text-overline: 3;/* You can change any property of the tag*/
}

/*Selector: Syntax*/
/*

selectorName {
    property: value;
}

*/
/* A single selector can change multiple properties*/
p {
    text-overline: 3;
    text-underline: dot-dash;
    color: red;
}

/* Selectors will select all matching tags on the page and apply the properties*/

/* Descendant Selectors*/
/* They can be used to select tags only if they are children of another tag*/

ul li {
    font-size: 30px;
    color: darkgreen;
}

/* Pseudo Selectors*/
/* Pseudo-selectors are modifiers that can be added to a selector to select a Tag
only when a certain condition has occurred*/
ul li:hover{
    color: pink;
}

/* Pseudo Selector: First Child*/
/* The :first-child pseudo-selector can be applied to narrow the amount of child selected*/
ol li:first-child{
    color: lightcoral;
}
```

TheBoxModel.css
====================
```CSS
/*The Box Model*/
/*Every tag shown in the body is contained in an invisible rectangle called Box*/
/*The box model is a way to describe the borders and spacing in between the boxes of each tag*/

/*Block-level tags*/
/*The content of block-level tags take up the entire width (horizontal space) of the container*/
/*Every box is pushed to the line below*/

/*Examples of block-level tags*/
/* h1 , h2,  h3,  p,  ul,  li*/

/*Inline-level tags*/
/*Every tag that is not block-level, is called inline-level/
/*The content of these tags do not try to take the entire width of the container*/

/*Examples of inline-level tags*/
/* a, img , input, label*/

/*Converting block-level tags into inline-level tags*/
/*Allows you to display items horizontally instead of vertically*/

ul li {
    display: inline;
}

/*Box Model Parts*/

/*Content area*/
/*Contains the actual content (text, images, etc.)*/
/*It will take up as much vertical space as it needs to display the content inside*/

/*Padding*/
/*Padding is a layer on every edge of the content area*/
/*Padding can be added to the top, right, bottom or left of the content area*/

/*Border*/
/*Border can be added to the top, right, bottom or left of the padding*/

/*Margin*/
/*Border can be added to the top, right, bottom or left of the border*/

/*Box Model: Size*/
/*The full size of a box is calculated by adding all of these properties*/
/* Content Area width + padding-left + padding-right + border-left + border-right + margin-left + margin-right*/

/*Applying the box model properties*/
/*It is possible to add every property at once*/
/*Padding*/
h2 {
    padding-top: 4px;
    padding-bottom: 8px;
    padding-right: 9px;
    padding-left: 3px;
}
```
Run and Play
====================
All the html files are linked to their respective CSS file. Open your browser, change the content and start learning!

<img src="https://s3-us-west-2.amazonaws.com/testdrivenlearningbucket/Play.png"/>

Questions ?
====================
If you have any questions, please feel free to ask me:
[Martin Chavez Aguilar](mailto:martin.chavez@live.com)

Contributors
====================
* [Martin Chavez Aguilar](http://martinchavezaguilar.com/) - Wrote the project

Continue Learning
====================
<a name="README">[<img src="https://camo.githubusercontent.com/eb464a60a4a47f8b600aa71bfbc6aff3fe5c5392/68747470733a2f2f7261772e6769746875622e636f6d2f766f6f646f6f74696b69676f642f6c6f676f2e6a732f6d61737465722f6a732e706e67" width="50px" height="50px" />](https://github.com/MartinChavez/Learn-Javascript)</a>
<a name="README">[<img src="https://pbs.twimg.com/profile_images/2149314222/square.png" width="50px" height="50px" />](https://github.com/MartinChavez/AngularJs-Basics)</a>
<a name="README">[<img src="http://spin42.com/assets/languages/angularjs_gray-4b0d229ceae4c13fc31e4657359f4dcc.png" width="50px" height="50px" />](https://github.com/MartinChavez/AngularJS-Advanced-Topics)</a>
<a name="README">[<img src="https://s3-us-west-2.amazonaws.com/testdrivenlearningbucket/c%23.jpg" width="50px" height="50px" />](https://github.com/MartinChavez/CSharp)</a>
<a name="README">[<img src="http://precision-software.com/wp-content/uploads/2014/04/jQurery.gif" width="50px" height="50px" />](https://github.com/MartinChavez/jQueryBasics)</a>
