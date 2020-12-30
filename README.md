<!DOCTYPE html>
<html>
<head>

</head>
<body>
<h1> CSS Sytax </h1>
<p>A CSS rule-set consists of a selector and a declaration block:<br>
The selector points to the HTML element you want to style.<br>
The declaration block contains one or more declarations separated by semicolons.<br>
Each declaration includes a CSS property name and a valude, separated by a colon.<br>
Multiple CSS declaration are separated with semicolons,and declararion block are surround by curly braces.</p>
<h1> CSS Selectors</h1>
<p>CSS selectors are used to "find "( or select) the HTML elements you want to style.<br>
We can divide CSS selectors into five categories:<br>
Simple seletors ( select elements based on name,id, class)<br>
Combinator selectors ( selector elements based on a specific relationship between them)<br>
Pseudo-class selectors (selector elements based on a certain state )<br>
Pseudo-elements selectors (select and style a part of an element)<br>
Attribute selectors ( select elements based on an attribute or attribute value)<br>
This page will explain the most basic CSS selectors.<br>
</p>
<h1> The CSS element Selector</h1>
<p>The element selector selectors HTML elements based on the element name.<br>
<h1> The CSS id Selector</h1>
<p>The id selector uses the id attribute of an HTML element to select a specific element.<br>
The id of an element is unique within a page,so the id selector is used to select one unque element!<br>
To select an element with a specific id, write a hash (#) charater, followed by the id of the element.<br>
<strong> Note:</strong> An id name cannot start with a number</p>
<h1> The CSS class Selector</h1>
<p>The class selector selects HTML elements with a specific class attribute.<br>
To select elements with a specific class,write a period(.) character, followed by the name <br>
You can also specify that only specific HTML elements should be affected by a class</p>
<h1> The CSS Universal Selector</h1>
<p> The univeral selector (*) selectd all HTML elementd on the page<br></p>
<h1> The CSS Grouping Selector</h1>
<p>The grouping selector selects all the HTML elements with the same style definitions.<br>
Look at the following CSS code (the h1, h2, and p elements have the same style definitions):</p>
<p>
It will be better to group the selectors, to minimize the code.<br>
To group selectors, separate each selector with a comma<br>
<h1> How To Add CSS</h1>
<p> When a brower reads a style sheet , it will format the HTML document acoording to the information in the style sheet.<br></p>
<h2> Three Ways to Insert CSS </h2>
<p> There are three ways of inserting a style sheet:<br>
External CSS<br>
Internal CSS<br>
Inline CSS<br>
</p>
<h1> External CSS </h1>
<p> With an external style sheet, you can change the look of an entire website by changing just one file!<br>
Each HTML page must include a reference to the external style sheet file inside the link element, inside the head section.<br>
An external style sheet can be writen in any text editor, and must be saved with a.css extension.<br>
The external .css file should not contain any HTML tags.<br>
Here is how the "mystyle.css" file looks:<br>
</p> 
<h1> Internal CSS </h1>
<p> An internal style sheet may be used if one single HTML page has a unique style.<br>
The internal style is defined inside the style element, inside the head section<br></p>
<h1> Inline CSS</h1>
<p>
An inline style may be used to apply a unique style for a single element.<br>
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property<br>

<strong> Tip: </strong> An inline style loss many of the  advantages of a style sheet1( by mixing content with presentation ). Use this method sparingly</p>
<h1> Multiple Style Sheets</h1>
<p>If some propertieis have been defined for the same selector ( element) in different style sheets , the value from the last read style sheet will be used.</p>
<h1> Cascading Order</h1>'
<p> What style will be when there is more than one style specified for an HTML element ?<br>
All the style  in a page will "cascade" into a new "virtual " style sheet by the following rules, where number one has the highest priority:<br>
1.Inline style (inside an HTML element)<br>
2.External and internal style sheets ( in the head section)<br>
3.Brower default.<br>
So, an inline style has the highest priority, and will override external and internal style and brower default</p>
</body>
</html>
