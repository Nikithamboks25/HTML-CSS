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







