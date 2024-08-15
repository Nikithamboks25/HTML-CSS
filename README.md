# HTML-CSS
**Introduction**
HTML and CSS are the foundation of web development and the building blocks of web pages. The web consists of three programming languages: HTML, CSS, and JavaScript. <br>
**Programming languages** - known for their logical and consistent nature.<br>
**Internet** - acts as the meeting point for human and computer languages. <br>
**Semantic markup** <br>
•	means labelling content for what it is.
•	using semantic markup, ensures that screen readers and search engines can accurately interpret and categorize the information on a page. <br>
**What is a confident computer user?** <br>
•	Knowing how to cope when things go wrong
•	 Knowing how to learn new computing skills independently <br>

**Hypertext Mockup Language (HTML)** <br>
•	HTML forms the foundation of website and web app development
•	Has a straightforward structure without any programming logic, loops, or functions – this is known as declarative language
•	 It is the language that allows you to make sure your content is understandable to both people and computers
•	Responsible for marking up the content of a website
•	Grants access to a wide range of built-in browser functionalities that can be utilized by incorporating specific HTML code.
•	HTML is designed to structure our content and bridge the gap between human and computer languages.
•	Html is simple and offers resilience and robustness
•	It handles missing and misspelled elements by taking a guess and fixing it. It displays the page regardless of the misspelled elements. <br>
**Cascading Style Sheet (CSS)** <br>
•	CSS is responsible of the look and feel of the web page, this includes the colors, fonts, and sizes used. Also capable of adding animation and interactions
•	Hiccups in the CSS code, the browser skips that part and move on to the rest. <br>
**JavaScript** <br>
•	JavaScript is a scripting language used to develop web pages
•	Allows developers to create a dynamic and interactive web page to interact with visitors and execute complex actions
•	It enables users to load content into a document without reloading the entire page.
•	JavaScript can be a bit fragile/delicate at times, this is because If there is an issue with the code or the browser is outdated and does not understand the code it refuses to run and does not figure out what to do like HTML or CSS <br>
**Web Browser and Website** <br>
**Website** - it is expected to work even after several years without any updates. <br>
**Web** <br>
•	runs on various platforms like Mac, Windows, iOS, Android, Linux, and more. 
•	Enable people to share content, even when our computers are different.
•	Relies on three different programming languages — HTML, CSS, and JavaScript
•	Combining these languages, developers can achieve resilience, robustness, and power in their websites. <br>

**Text Formatting** <br>
**Html Syntax** <br>
•	Html is a language used to structure web pages and tags.
•	The purpose of HTML markup is to give meaning to the content and help computers understand it. It serves as a bridge between the human and computer worlds.
•	Tags are enclosed in a less-than and greater-than symbols to mark different elements.
•	Common mistake in HTML is forgetting to include the closing tag at the end of an element. <br>
**Tags** <br>
•	tags work together to define elements, which are like packages containing contents
•	Some of these elements require both opening and closing tags, but some don’t 
•	Anything placed a closing tag will still be displayed on the same HTML page, but the browser will understand it as being outside the tag. <br>
**Types of tags:*
•	opening tags – example <p>
•	closing tags – example </p> <br>
**Elements** <br>
•	HTML elements can be nested within one another
•	For example, the <em> element can be used inside the <p> element to emphasize a text.
•	Choice of HTML elements impact the user experience on your website, including people with various disabilities. It all starts with nesting those HTML elements. <br>
**Document Object Model tree (DOM)** <br>
•	It pays attention to the structure of how everything is related.
•	It is used by the browser to create accessibility <br>
**HTML Paragraphs** <br>
•	It is important to have opening and closing tags to indicate each paragraph on web page, if not the browser will show your paragraphs as a single chunk text. <br>
**HTML Headlines** <br>
•	Play crucial role in helping people understand the web page structure
•	Headlines are the main content on landing pages, they act as clickable titles that leads readers to further information.
•	They can be found everywhere
•	There is html elements used for marking up headlines which are h1, h2, h3, h4, h5, and h6. These elements have difference or a distinctive visual effect and convey a sense of hierarchy.
•	The size from h1 to h6 goes from big to small, making h1 the largest and most prominent and h6 the smallest and least attention grabbing
•	Choice of the headline level is its meaning and not the appearance. Meaning it would make sense to make the main heading a h1 and the subheading a h2. This is to be able to distinguish what is most important and what is less important.<br>
**Html Bold and Italics** <br>
•	The are four html elements related to these, two for bold and two for italic
•	The reason we use italics is to make strong points <br>

**Html Lists**\
•	Lists on the internet do not always look like the traditional list w are familiar with
•	List can be navigation bars with links, enticing photos, and headlines that are clickable.
•	 There are different type of list elements, mainly : unorderded list elements , ordered lists elements, and definition list elements.

**Unordered List Elements*
<ul>
  <li>This are the most common used list type</li>
  <li>All of its items are wrapped with a "ul" element which stands for unordered list</li>
  <li> Each list item is enclosed by the "li" element which represents a list item</li>
  <li>To make the list more readable we need to indent the list items by adding space or tabs before each one</li>
  <li>Indentation does not affect the appearance of a webpage, the browser determines the default appearence of the list</li>
</ul>

**Ordered List Elements*
<ol>
  <li>This type of list uses a "ol" element to wrap the list items.</li>
  <li>The "ol" stands for ordered list which means that there is a specific order on the list items, it will number the items showing the particular order of occurence</li>
</ol>

**Definition List/Description List Elements*
<ul>
  <li>This is used when we want to create a list that resembles a key-valu pair in computer Science</li>
  <li>Meaning, this type of list will have a term and each term corresponding definition</li>
  <li>The "dt" tag which stands for definition term is used to enclose the term or key</li>
  <li>The "dd" tag which stands for description is used to enclose the description or value of the term - can have multiple of "dd" tags for one term</li>
  <li>The "dl" tag which represents the definition list wraps up the entire list</li>
  <li> "dd" tags and "dt" tags are placed side by side without any additional wrapper around them</li>
</ul>

**HTML Quotes**
<ul>
<li>Html quotes are used to cite a individuals phrase, the elements that are used here are "cite" and "blockquote"</li>
<li>The "cite" element is used to attribute the individuals phrase</li>
<li>The "blockqoute" element is used to distinguish the qoute/phrase from its surrounding text by wrapping the whole thing up</li>
<li>Both elements serve a semantic purpose and provide a convenient way to apply custom styling</li>
</ul>

**Inline Qoutes*
<ul>
<li>These qoutes appear within the text by simply being typed in and do not wrap anything</li>
<li>Examples of inline qoutes either than "q" are elements like "<strong>", "<b>", "<I>", and "<em>" - These are called inline qoutes because they are meant to wrap around phrases of text that are inline with other content.  </li>
<li> <b>block-level elements: </b> This element creates seperate blocks on a page, they are refered to standalone enttities that can be followed by another block</li>
</ul>

**Date and Time Elements**
<ul>
<li>These elements allow us to specify the date or time in a format that a computer will understand</li>
<li>The format of the time within the date time attribute has to be specific in order for the computer to process it</li>
<li>Machines prefer a highly standardized format, these times need to be indicated by using the time element. Machine-readable version prefers numbers in the 24-hour clock format, and we can choose whether to include seconds and fractions of a second or not. </li>
</ul>

**How to combine date and time attribute?*
<ul>
<li>First implement the date element then the time</li>
<li>If you want to seperate them use a "T" or simply leave a space</li>
</ul>

**HTML Date and Time Inputs**
<ul>
  <li>Html simplifies the mess that comes with implementing date and times unlike other programming languages</li>
  <li>"time" element is the single element used to mark anything that specifies a time of day, date, or duration in a way that a computer will understand</li>
  <li>"datetime" attribute is used when wanting to convey the exact date or time to computers</li>
  <li>Example on how it is written: "We write it like this: <time datetime="2025-05-08">May 8, 2025</time>."</li>
</ul>

**HTML Code, pre, and br**
<ul>
  <b>Code Element:</b>
  <li> It is used to define a piece of computer code. The content inside is displayed in the browser's default monospace font but however one can customize it to desired look.</li>
  <li>It is treated as an inline element because it remains part of a sentence its in</li>
  <li> "&lt" is a Html entity that is displayed as a less than sign(less thanTry it). The entity is useful when wanting to display text</li>
  <li> "&gt" - Html entity that displays a greater than sign(greater thanTry it) </li>

  <b>br Element:</b>
  <li>Adds line break on sentences and browser will recognize</li>
  <li>They can be added at the end of each line.</li>
  <li>Its is a simple tag without an opening or closing tag.It does not contain anything inside it; it just indicates where a line break should happen.</li>

  <b>pre Element:</b>
  <li></li>
</ul>

**HTML Superscripts, Subscripts, and Small Text**
<ul>
  <li>These are used when wanting to mark up a certain content as having a different meaning than the rest</li>
  <li> <b>Subscripts: </b> Are characters that are set below the normal baseline of a text</li>
  <li> <b>Superscripts: </b> Are characters set above normal baseline of text</li>
</ul>

**HTML Capabilities**

<ul>
  <li> <b>Troubleshoot and Debugging Html code: </b> It is to inspect the html code in a browser developer tools</li>
</ul>

**HTML Attributes**
<ul>
  <li>Attributes are specific to a particular element. For example daytime willl be only used with time element. They can also work with multiple elements but not all</li>

  **Global attributes:* are attributes in html that work universal. The different types and highly useful ones are:
  
  **Class Attribute:* Are commonly used, that allows the assigning of a resuable name to any element, which can then be styled using CSS for all elements sharing that class.

  *ID Attribute** 
  <li>similar to class attribute, but allows use of unique names once on the entire HTML page.</li>
  <li>ID are used for CSS targeing but can sometimes cause issues. Therefore, CSS developers prefer using Class attributes.</li>
  <li>ID are handy when specific elements need to be addressed in Javascript or targeted links</li>
  
  **"dir" and "lang Attributes*
  <li>"dir" attribute explicitly indicates the direction in which the text flows, using "LTR" for left-to-right scripts and "RTL" for right-to-left scripts.</li>
  <li>lang" attribute allows us to specify the language of the content using a short language code.</li>

  **Content Editable Attribute:*
  <li>Allows visitors to edit content on a web page</li>
  <li>Allow interaction with the screen, keyboard, and assistive devices</li>
</ul>

**HTML Links**
<ul>
<li>When when wants to create a link, they can use the A element which stands for Anchor</li>
<li>Then implement the "href"(HyperText Reference) attribute with the URL that is enclosed in qoutes</li>
<li>The Url(Uniform Resource Locator) takes us to the intended page</li>
</ul>

**Absolute URL's**
<ul>
  <li>They point to a precise location on a web</li>
  <li>It is compulsory on a absolute Url to include the HTTP(Hypertext Transport Protocol) or HTTPSecure</li>
  <li> <b>HTTP: </b> This protocol defines the rules for communication on the web and is crucial for linking.</li>

  **HTML URL Pathways**
  <li>Url uses slashes to indicated that we should look deeper into the file or go one level down. The slashes formulate the path way of page or file</li>

  **Navigation**
  <li> "nav" element allow us to create menus or navigation bars</li>
</ul>

**HTML Working with Graphics and Images**
<ul>
  **Images**
  <li> "img" element is used to add a image on a web page  </li>
  **The following are the four attributes to be added for every image**
  <ol>
    <li>Source attribute (SRC), which tells the browser which image file to load</li>
    <li>alt attribute (ALT), which provides a text description of the image.</li>>
    <li>width and height attributes, which determine the size of the image.</li>
  </ol>

  **Image Formats**
  <li>Image in a web page need to have a particula format that the web browser would understand</li>
  <li>The main four file formats that are commonly used on the web are: GIF, SVG, JPG, and PNG</li>
  <li>GIF: Have large areas of the same color but falls short when it comes to photographs. They support 256 colors. Images become pixelated unless retro vibe is used. Have transperent area</li>
  <li>SVG: A vector file that contains instructions for drawing. They are perfect for icons and logos</li>
  <li>JPG: Popular choice for compressing photographs and most cameras save images as this file format</li>
  <li>PNG: Works well with transparency in a photograph</li>
</ul>

**HTML Generic Elements** - ```<div>``` annd ```<span>``` 
<ul>
  ```<div>```- is a block element <br>
  ```<span>``` - is a inline element
</ul>

**HTML PAGE**
<ul>
  <li>HTML pages are retrieved when one opens up a web browser/view and enter a specific url that will redirect the user to that particular web page.</li>
  <li> Web Server - is the one that responds by sending back the specific Html file located at that address</li>
  <li>Basic process of the web - Users visit a URL, which prompts a request for an HTML file, and the server returns a single HTML file. </li>
  <li> ```<doctype html>``` - indicates the era of a HTML file</li>
  <li>```<html>``` - This is a html element that means everything wrapped by this tag has html content</li>
  <li> ```<head></head>``` - Element that contains all the metdata that the browser needs to know but is not displayed on the page</li>
  <li>```<body></body>``` - The body is where most action happens, it contains all content need for the paged and is composd by different elements inside it </li>


**Document Head**
<li>Document head include elements such as ```<meta>``` where it shows the character set that is not intended to be seen by users.</li>
<li>```<meta>```- placed inside the head as they provide the metadata about the page</li>
<li>```<meta name>``` or ```<title>``` - It is what appears on the browser tab or bookmark when saved. It is also the name that appears under top sites when a new browser tab is opened</li>
  <li> ```<meta>``` - This tag has various purpose. One of its common use is to inform the browse the layout adjusted for small screens, making it responsive. Without this tage browser will assume we are following old layput.</li>
  <li> ```<link>``` - This is a crucial element that is used extensively on the head section. It connects various assets that should load. Example: CSS files, fonts, and/or favicons</li>
  <li> ```<link rel>``` - The rel attribute informs the browser about the specific type of asset</li>
  <li> ```<link href>``` - The href attribute is used to specify the URL for the asset</li>
  <li> ```<script></script>``` - Used in HTML document's head, but some also placed at the end of the document. It instructs the browser to load a JavaScript file.</li>

**Content Structuring**
This Subsection will touchbase on the typical structure inside the body, following the six elements:
<ol>
  
  **Main**
  <li> ```<main>``` - used once per webpage and tells the browser where the main content is located </li>
    
  **Header**
    <li> ```<header>``` - usually found at the top of most web pages and may include a logo, site name, and navigation. It is used for site headers, article headers, and headers within the content. Not that Headers and Head elements are not the same. </li>
    
  **Footer**
  <li> ```<footer></footer>``` - portrays the extra information regarless the position on page, but most footers for some sites are allocated at the bottom of the page containing links, copyright information, and additional details about the company..</li>

 **Article**
 <li>The article element wraps around any type of content unit, whether it is a long written article, a short snippet, a teaser card, a tweet, or even an app element. It represents a standalone unit of content.</li>
 <li>Article often starts with a title, subtitle, author's name, and publication date, which can also be considered a header</li>

 **Section**
 <li>A section element is used to mark sections of content, each section starts with its own headline. It is usefull for dividing different topic zones on a website</li>

**Aside**
<li>The aside element is for content that is off to the side, like sidebar information or additional details that accompany an article but are not part of its main flow. Example: Advertisments</li>
</ol>
</ul>


**Working with Forms and Interactive Elements**

**Form Fundamentals**
<ol>
  <li>Form fields are essential for the web and are used for various tasks like logging into websites, making purchases, conducting search, and adding content.</li>
  <li> Use form element to create a form</li>
  <li> Placing type attribute informs the web page what type of input should be taken in a text field</li>
  <li>The "Required" attribute acts as a reminder to fill out all required fields on a web page and does not allow user to submit unless field is filled in</li>
</ol>

**HTML Tables**
<ul>
  <li>Html tables are used for Tabular Data</li>
  <li>Table - refered to as a chart of data from a research project</li>
  <li>Data table - refered as a bunch of information that is best communicated by aligning in rows and columns.</li>
  <li>To create an HTML table, you use several different HTML elements in just the right combination. Table, TR, TH, and TD</li>
![HTML-CSS101M1Fig82](https://github.com/user-attachments/assets/0a5c464e-5f9b-4d66-b11a-113ade90405b)
</ul>

**Module Focus - Cascading Style Sheets(CSS)**

**What is CSS**
<ul>
  <li>It is like a CSS fle that holds all the styles of a webpage that will add visual appeal to the page.</li>
  <li>To connect Html and Css, one should simply link.</li>

  **CSS Two Parts - The Selector and Declaration Block**
  <li>The Selector: It specifies a pattern in html, and if that pattern match, the style within the declaration block are applied to the corresponding html elements</li>

  **CSS Components**
  <li>The two style declaration that CSS consist of is "Property" and "Value"</li>
  ![HTML-CSS102Fig2](https://github.com/user-attachments/assets/73200f62-dcc7-4e2a-8f18-c7bd3df111ae)
</ul>

**Comment and Element Selector**
<li> CSS write their comments like /*Hello World*/ </li>
<li> Elements can be selected singly or multiple to apply styling</li>
<ul>

**Writing a Class Selector**
<li>To style a specific element text, you can assign classes to the HTML element, this creates a reference point for the styling</li>
<li>A class is a attribute that can be added to any HTML element, by providing additional details of that element.</li>
<li> Span elements can also be used with class attribute to style a part of a paragraph</li>

**Grouping Selectors**
<li>Useful for styling different element to one particular pattern by combining them</li>

**Descendent Selectors**
<li>A descendant selector allows us to select list items that are descendants of either an ordered or an unordered list. The relationship can be direct or indirect, similar to a family tree.</li>
<li>Example: The ordered list head can have its own styling and the childen list can have a diffrent style. The Descendent Selector use the code like this "OL LI". The space between "OL" and "LI" signifies the descendant relationship.</li>
</ul>

**Identify a Color Scheme**
Users can also explore other combinations like
<ul>
  <li>Monochromatic- where two similar colors are chosen </li>
  <li>Analogous - involves various shades of greens and blues, or triadic, which creates a pattern on the color wheel using an equilateral triangle</li>
  <li>There is also the option of tetradic, which generates a square's worth of colors. </li>

 **Background and Text Color in CSS**
 <li>Background color property is ```<background-color></background-color>``` </li>
 <li>To set background of the whole page, use the body element on styles</li>

 **Understanding Images in CSS**
 ![HTML-CSS102Fig22](https://github.com/user-attachments/assets/d10c86e8-7273-455b-91ab-013bd6a7aaca)

 The web supports these three types of image formats
 <li>GIF: Has limited colors but could include transparency and animation.</li>
 <li>PNG: Has more colors and transparency but no animation. GIF and PNG are suitable for illustrations such as logos or cartoons. </li>
 <li>JPG: Stands for Joint Photographic Experts Group, optimized for photographs and supported millions of colors but lacked transparency and animation.</li>
 <li>WebP: A new image format that has emerged. It can be used for any image type and offers high  compression for smaller file sizes, resulting in faster website loading times</li>
 <li>Choosing the correct image format is vital to prevent color loss and potential large size</li>
 <li>CSS allows the insertation of background images</li>
 <li>Shorthand property is used for more flexibility on background by simply adding "repeat-X," the image will repeat only horizontally.</li>
 <li>Use "repeat-Y" to repeat it vertically.</li>
 <li>To control where the background image starts, specify values like "center," "right," or "left.</li>
 <li>Additionally, you can use "bottom" to push the image to the bottom of the page.</li>
 <li>Depending on the background image one is using, a percentages can be used to adjust where these images appear on the page, making it good</li>
</ul>

**Understanding Type in CSS**
<ol>
  **COMMON TYPE OF FONTS**
  <li>Serif: Have small lines at the end of the letters called serifs. They were used for print materials with long text blocks in the past. They helped with connecting letters that seemed to never align when printed, making the text easier to read</li>
  <li>Sans Serif: Have a more modern appearance than serifs. Used for extended text because they look clean and easy to read</li>
  <li>Common Fontt Stack: is Arial, Helvetica, sans serif. Arial is commonly available on PCs, Helvetica on Macs, and sans serif is a fallback that requests the device's default sans serif font if Arial or Helvetica are not available.</li>
</ol>

**Applying Type Formatting with CSS**
<ul>
<li>A "font-family" property is added to the body element</li>
<li>One should install fonts that they want to use otherwise the computer will set the default font which is Sans Serif.</li>
</ul>

**Types of Sizing**
<ol>
  <li>Absolute: are sizes such as points or pixels, they remain the same regardless of the screen size</li>
  <li>Relative: are relative units like percentages or R-E-M (pronounced "rem") can adjust based on the page size. So whenever someone zoom in, the font size uses relative units scale proportionally with the rest of the page</li>
</ol>

**The Box Model in CSS**
<ul>
  The below is a boc model
  ![HTML-CSS102Fig36](https://github.com/user-attachments/assets/55123db4-8434-4ff6-8876-d49d9279795f)
  <li></li>
</ul>

