## HTML

 - HTML5 does not require empty elements(`<br>`) to be closed. But if you want stricter validation, or if you need to make your document readable by XML parsers, you must close all HTML elements properly.
 - HTML tags are not case sensitive ` <P>` means the same as `<p>`.
 - The HTML5 standard does not require lowercase tags, but W3C **recommends** lowercase in HTML, and **demands** lowercase for stricter document types like XHTML.
 - **Attribute** : HTML links are defined with the `<a>` tag. The link address is specified in the `href` attribute
 - The HTML `<head>` element is a container for metadata. HTML metadata is data about the HTML document. Metadata is not displayed. `<meta charset="UTF-8">`
 - Browsers automatically add some white space (a margin) before and after a paragraph.
 - The text inside a **`<pre>`** element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.
 - Browsers display `<strong>` as `<b>`, and `<em>` as `<i>`. However, there is a difference in the meaning of these tags: `<b>` and `<i>` defines bold and italic text, but `<strong>` and `<em>` means that the text is "important".
 - Without a forward slash at the end of sub-folder addresses, you might generate two requests to the server. Many servers will automatically add a forward slash to the end of the address, and then create a new request.
 - 
**Image Tag**
 - ***In `<img>` Tag***, The `alt` attribute is required. A web page will not validate correctly without it.
 - ***In `<img>` Tag***,  Always specify the width and height of an image. If width and height are not specified, the page might flicker while the image loads.
 - ***In `<img>` Tag***, `border:0;` is added to prevent IE9 (and earlier) from displaying a border around the image (when the image is a link).

**Table Tag**
 - If the table has collapsed borders, `border-spacing` has no effect.
 - The `<caption>` tag must be inserted immediately after the `<table>` tag.

**Block**
 - A block-level element **`<div>, <address>, <h1...h6>, etc`** always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).
 - An inline element **`<span>`** does not start on a new line and only takes up as much width as necessary.
 - An HTML element can only have one unique **ID** that belongs to that single element, while a **CLASS** name can be used by multiple elements

**Script**
 - `<script>` Defines a client-side script.
 - `<noscript>` Defines an alternate content for users that do not support client-side scripts
 
**File Path**
 - Absolute File Paths : `<img src="https://www.w3schools.com/images/picture.jpg" alt="Mountain">`
 - Relative File Paths : 
		 - `<img src="/images/picture.jpg" alt="Mountain">`
		 - `<img src="images/picture.jpg" alt="Mountain">`
		 - `<img src="../images/picture.jpg" alt="Mountain">`
 - It is best practice to use relative file paths (if possible) 
	- *When using relative file paths, your web pages will not be bound to your current base URL. All links will work on your own computer (localhost) as well as on your current public domain and your future public domains.*

**When making responsive web pages, add the following `<meta>` element in all your web pages**

 - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`

**Responsive Text**

 - `<p style="font-size:5vw;">` Use the "vw" unit when sizing the text. 10vw will set the size to 10% of the view-port width.

**Computer Code**

 - The HTML `<kbd>` element represents user input, like keyboard input or voice commands.
 - The HTML `<samp>` element represents output from a program or computing system.
 - The HTML `<code>` element defines a fragment of computer code, Text surrounded by `<code>` tags is typically displayed in a monospace font.
 - The HTML `<var>` element defines a variable, Einstein wrote: <var>E</var> = <var>mc</var><sup>2</sup>.

**What is Character Encoding?**

 - ASCII was the first **character encoding standard** (also called character set). ASCII defined 128 different alphanumeric characters that could be used on the internet: numbers (0-9), English letters (A-Z), and some special characters like ! $ + - ( ) @ < > .
 - ISO-8859-1 was the default character set for HTML 4. This character set supported 256 different character codes.
 - ANSI (Windows-1252) was the original Windows character set. ANSI is identical to ISO-8859-1, except that ANSI has 32 extra characters.
 - Because ANSI and ISO-8859-1 were so limited, HTML 4 also supported UTF-8.
 - UTF-8 (Unicode) covers almost all of the characters and symbols in the world.
 - If a browser detects ISO-8859-1 in a web page, it defaults to ANSI.

**URL - Uniform Resource Locator**

 - `scheme(http/https)://prefix.domain:port/path/filename`
 - ***URL Encoding*** : 
		 - URL encoding converts non-ASCII characters into a format that can be transmitted over the Internet.
		 - URL encoding replaces non-ASCII characters with a "%" followed by hexadecimal digits.
		 - URLs cannot contain spaces. URL encoding normally replaces a space with a plus (+) sign, or %20.

**What Is XHTML**

 - XHTML stands for E**X**tensible **H**yper**T**ext **M**arkup **L**anguage
 - XHTML is almost identical to HTML
 - XHTML is stricter than HTML
 - XHTML is HTML defined as an XML application
 - XHTML is supported by all major browsers

**HTML Forms**

 - The length of a ***GET URL*** is limited (2048 characters)
 - ***POST*** has no size limitations, and can be used to send large amounts of data.
 - ***Attribute : accept-charset*** Specifies the charset used in the submitted form (default: the page charset).
 - If the `type` attribute is omitted, the input field gets the default type: "text".

