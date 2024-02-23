# html-css
This code creates a basic visual representation of a traffic light composed of three circles representing red, yellow, and green lights
 using HTML and CSS 

 HTML:
<!DOCTYPE html>: Declares the document type and version of HTML being used.

<html lang="en">: Defines the root element of the HTML document, with the language attribute set to English.

<head>: Contains meta-information about the HTML document, such as character encoding and viewport settings.

<meta charset="UTF-8">, <meta name="viewport" content="width=device-width, initial-scale=1.0">: Specifies the character encoding and viewport settings.

<title>Document</title>: Sets the title of the HTML page to "Document".

<link rel="stylesheet" href="style.css">: Links an external CSS file (style.css) to the HTML document for styling.

<h1><b>Traffic light</b></h1>: Creates a level one heading with the text "Traffic light", wrapped in a bold (<b>) tag.

<div>: Opens a div container for organizing content.

<div class="heading1">, <div class="heading2">, <div class="heading3">: Creates div elements with classes "heading1", "heading2", and "heading3", representing the red, green, and yellow lights respectively.

<div class="heading4">: Creates an empty div with the class "heading4", used as a spacer between the lights.

<div class="heading5">: Creates a div with the class "heading5", representing the frame/pole of the traffic light.

Closing tags: Properly closes the opened HTML elements (</div>).

<body>: Begins the body section of the HTML document.

Closing tags: Properly closes the opened HTML elements (</body>, </html>).


CSS:
div: This applies styling to all div elements.

width: 100px; height=100px;: Sets the width and height of all div elements to 100 pixels. (Note: there's a typo, it should be height: 100px; instead of height=100px;)
background-color: brown;: Sets the background color of all div elements to brown.
.heading1, .heading2, .heading3, .heading4, .heading5: These are classes used to style specific elements.

.heading1: Styles the red light.

width: 100px; height: 100px;: Sets the width and height of the red light to 100 pixels.
background-color: red;: Sets the background color of the red light to red.
border-radius: 50%;: Rounds the corners of the red light to make it circular.
text-align: center;: Centers the text inside the red light.
.heading2: Styles the green light. Similar properties as .heading1 but with a green background color.

.heading3: Styles the yellow light. Similar properties as .heading1 but with a yellow background color.

.heading4: Styles an empty div. This is used as a spacer between the lights.

.heading5: Styles the frame/pole of the traffic light.

width: 30px; height: 400px;: Sets the width to 30 pixels and height to 400 pixels.
background-color: black;: Sets the background color to black.
text-align: center;: Centers the content vertically.
margin-left: 35px;: Provides some margin to the left to adjust the position of the pole.
h1: Styles the heading "Traffic light".

text-align: center;: Centers the text horizontally.
