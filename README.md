Download Link: https://assignmentchef.com/product/solved-cinf362-week-4-css-part-i
<br>
<strong>Agenda</strong>

<ul>

 <li>Introduction to CSS

  <ul>

   <li>What is CSS?</li>

   <li>How can we add styles to a page?</li>

   <li>CSS Examples</li>

   <li>First CSS Exercise</li>

   <li>CSS Research Initial Post &amp; Response</li>

  </ul></li>

 <li>Next Week</li>

</ul>

<h2>Introduction to Cascading Style Sheets (CSS)</h2>

<strong>What is CSS?</strong>

CSS stands for Cascading Style Sheets. Unlike HTML, which is used to represent the structure of a web page, CSS is the language for the determining the presentation of a page in terms of colors, fonts, positioning, etc. We use CSS to select specific HTML elements in order to give them styles. After selecting specific elements (either directly or based on certain criteria), we can then choose whatever properties we’d like and give them different values. An example would be targeting paragraph tags and giving them a red font color. We can do that with the code below:




p {

color: red;

}




“p” is the selector (all paragraph tags), “color” is the property, and “red” is the value we are assigning to the property. The selector comes first followed by curly brackets “{}”. Inside of the curly brackets is where we choose our properties and values. The properties and values are always separated by a colon and the whole statement (color: red) is ended with a semicolon. The entire set of code from the “p” up until the closing curly bracket is a CSS declaration. You can have as many statements as you want inside of curly brackets.




It is <strong>best practice</strong> to separate your HTML and CSS. The reason for this is because it is easier to update your code if it is in a different location. If you have a consistent banner style on many pages of your website and use inline/internal styling, you would have to go into the code for each page and edit it. If you use external styling, you can edit the code in one place and the changes would persist across all pages.

<strong> </strong>

<u>Additional Reading</u>

<ul>

 <li><a href="https://www.htmldog.com/guides/css/">https://www.htmldog.com/guides/css/</a> – CSS Tutorials for all levels</li>

 <li><a href="https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps">https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps</a> – Excellent resource with guides/tutorials for CSS</li>

 <li><a href="https://www.tutorialspoint.com/css/css_syntax.htm">https://www.tutorialspoint.com/css/css_syntax.htm</a> – Specific syntax examples</li>

 <li><a href="https://css-tricks.com/">https://css-tricks.com/</a> – Cool website for code snippets and articles</li>

</ul>

Besides the links provided above, there is a PowerPoint document available on Blackboard under today’s Lecture Notes or in the Resources folder which explains everything in this document in addition to things we will learn in future weeks.




<strong>How can we add styles to a page?</strong>

There are three main ways for implementing CSS on a web page and each one is explained below with a link to an example. To see the code in the example, right-click the page and select “View Source” or “Inspect Element” and look around the window the appears.

<u>Inline CSS</u>

This is typed directly into the HTML tag as part of the style attribute.

<u>Internal CSS</u>

This is CSS typed between &lt;style&gt;&lt;/style&gt; tags which are located inside of the &lt;head&gt;&lt;/head&gt; tags of your HTML document.

<u>External CSS</u>

This is CSS placed in a separate document with a “.css” extension. It is connected to our HTML through the usage of a &lt;link&gt; tag which is placed inside of the &lt;head&gt;&lt;/head&gt; tags.




<strong>Example Link:</strong> <a href="https://iinf362.000webhostapp.com/examples/using-css/">https://iinf362.000webhostapp.com/examples/using-css/</a>




<strong><u>If you haven’t done so already, please read the “Creating and Viewing our Web Pages.docx” file on Blackboard. You will not be able to submit anything for the assignment without completing that portion first. </u></strong>




<strong>First CSS Exercise</strong>

Download the “First-CSS-Exercise.zip” folder from Blackboard under today’s Lecture Notes or the Assignment folder. Inside of this zip folder, there will be an HTML file, a css folder with a style.css file in it, and an image. Using CSS, make t­­­­he web page look as close as possible to the image provided. It doesn’t have to be an exact replica (I’m not providing padding, margin, border sizes) but try to get the general styles placed correctly. Make sure to pay attention to the image because there are small nuances that can easily be missed with the styles (list type, text decoration, borders, etc.). You also don’t have to use the CSS file I’ve provided but your CSS should still be externally placed.

To get started, open the HTML/CSS files inside of a text editor and add code as necessary. I would recommend using classes ­on each of the main three divs to target the content inside of them. Feel free to code your CSS as you see fit though. Please note that no HTML should be removed…only classes and ids should be added as attributes to help you with selecting content using CSS. No inline or internal styling is permitted.

For this assignment and all future assignments after this one, your CSS must be <strong>externally placed.</strong> This is because it will be easier to manipulate styles on your page if the styles are separated. Below I have listed the requirements based on selectors, properties, and things that aren’t visible in the image.

<u>Requirements</u>

<ul>

 <li>Add a hover effect the &lt;a&gt; tag in the unordered list

  <ul>

   <li>When I hover over the &lt;a&gt; tag, the background of the &lt;a&gt; tag should become blue and the text should become white</li>

   <li>You will need to use the “:hover” pseudo selector on the &lt;a&gt; tag for this part</li>

  </ul></li>

 <li>Background</li>

 <li>Color</li>

 <li>Text-align</li>

 <li>Border</li>

 <li>List-style-type</li>

 <li>Border-collapse</li>

 <li>Text-decoration</li>

 <li>Nth-child selector</li>

 <li>The grey color you see is #ccc, otherwise the color values used are white, red, blue, and green</li>

 <li>There are three different types of borders being used</li>

 <li>The light blue line you see around the list in the first section can be ignored…that’s something from Brackets when it selects HTML during screen presentation and isn’t really part of the CSS.</li>

</ul>

To receive credit for the assignment, submit <strong>ONE</strong> link in total. The link should direct me to the page you have created for this assignment. Make sure the CSS is placed correctly as mentioned above. The link is due Wednesday, February 19<sup>th</sup> at midnight.




<strong>CSS Research Initial Post &amp; Response</strong>

In your <strong>initial post</strong>, do some research on any of the CSS properties listed below and report your findings. In addition to writing about what you discovered, you must create an original example demonstrating some capability of that CSS property and submit a link to that example with your initial post. The example doesn’t have to be very elaborate, but it should clearly depict what the CSS property you chose does and include an explanation of how it works. You can either submit a write up with a link or you can submit the write up inside of the HTML file used to create your example. I’ve listed some starting points, but you can include other pieces of information you find that are interesting as well.

<ul>

 <li>What is the property?</li>

 <li>What does it do?</li>

 <li>Does it require other properties for its usage?</li>

 <li>What version of CSS was it introduced in?</li>

 <li>What browsers support this property? Which ones don’t?</li>

 <li>Do you think this property is used very often?</li>

</ul>

<u>Properties to Research</u>




<ul>

 <li>Visibility</li>

 <li>Text-shadow</li>

 <li>Transform</li>

 <li>Clip</li>

 <li>Float</li>

 <li>Grid</li>

 <li>Text-transform</li>

 <li>Content</li>

 <li>Table-layout</li>

 <li>Animation</li>

 <li>Position</li>

 <li>Border-radius</li>

 <li>Box-shadow</li>

 <li>Flex</li>

 <li>Overflow</li>

 <li>@font-face</li>

 <li>Text-decoration</li>

 <li>Z-index</li>

 <li>Word-wrap</li>

 <li>Media queries</li>

 <li>Filter</li>

</ul>

<h2>Next Week</h2>

Next week we will look at more complicated CSS properties that will allow us to manipulate the positioning of the content on our page. This is one of the tougher areas of web development because manipulating positioning on a web page can be difficult based on your content and layout needs. I would recommend reading up on the CSS Box Model and Floats at the very least. Below are some links to get you started:

<ol>

 <li><a href="https://www.htmldog.com/guides/css/intermediate/layout/">https://www.htmldog.com/guides/css/intermediate/layout/</a></li>

 <li><a href="https://css-tricks.com/all-about-floats/">https://css-tricks.com/all-about-floats/</a></li>

 <li><a href="https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model">https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model</a></li>

 <li><a href="https://css-tricks.com/the-css-box-model/">https://css-tricks.com/the-css-box-model/</a></li>

</ol>


