# Introduction to HTML5
- HTML5 is a core technology markup language of the internet used for structuring and presenting markup content
for the world wide web.
- Its core aims have been to improve the language with support for the latest multimedia while keeping it easily readable by humans and consistently understood by computers and browsers (web browsers, parsers, etc.).
- HTML5 is intended to subsume not only HTML4, but also XHTML1 and DOM Level 2 HTML.
- Following its immediate predecessors HTML 4.01 and XHTML 1.1, HTML5 is a response to the fact that HTML and XHTML in common
use on the world wide web are a mixture of features introduced by various specifications, along with those introduced by software products such as web broswers, those established by common practice.
- It is also an attempt to define a single markup language that can be written in either HTML or XHTML.
- It includes detailed processing models to encourage more interoperable implementations; it extends, improves, and rationalizes
the markup available for documents, and introduces markup for application programming interfaces (APIs) for complex web applications.
- For the same reasons, HTML5 is a potential candidate for cross-platform mobile applications.
- Many features of HTML5 have been built the consideration of being able to run on low-powered devices such as smartphones and tablets.
- In particular, HTML5 adds many new syntactic features. 
- These include the new < video >, < audio >, and < canvas > elements as well as the integration of scalable vector graphics (SVG) content (replacing generic < object > tags, and MathML for mathematical formulas.
- These features are designed to make it easy and include and handle mathematical and graphical content on the web without 
having to resort to proprietary plugins and APIs.
- Other new elements such as < section >, < article >, < header >, and < nav >, are designed to enrich the semantic content of 
documents. New attributes can be introduced for the same purpose, while some elements and attributes have been removed.
- Some elements, such as < a >, < cite >, and < menu > have been changed, redefined, or standardized.
- The APIs and Document Object Model (DOM) are no longer afterthoughts, but are fundamental parts of the HTML5 specification.
- HTML5 also defines in some detail the required processing for invalid documents so that syntax errors will be treated
uniformly by all conforming browsers and user agents.

#HTML5 Markup
- HTML5 introduces elements and attributes that reflect typical usage on modern websites.
<ul> 
<li>Semantic replacements for common uses of generic block (< div >) and inline (< span >) elements; for example, < nav > (website
navigation block) and < footer > (usually referring to the bottom of the webpage or to last lines of HTML code).</li>
<li>< audio > and < video > instead of the <object> tag</li>
<li>Purely presentational elements such as < font > and < center > have been dropped; Casdcading Style sheets are used instead.
</ul>
- This is also a renewed emphasis on the importance of DOM scripting (e.g. JavaScript) in Web behavior.
- It comes with a new introductory line "<!DOCTYPE html>", which triggers the standards-compliant rendering mode.


#HTML5 New APIs
- In addition to specifying markup, HTML5 specifies scripting application programming interfaces (APIs) that can be used with
JavaScript.
- Existing document object model (DOM) interfaces are extended and de facto features documented.
- There are also new APIs such as:
<ul>
<li>The canvas element for immediate mode 2D drawing.</li>
<li>Timed media playback.</li>
<li>Offline web applications.</li>
<li>Document editing.</li>
<li>Drag and drop.</li>
<li>Cross-document messaging.</li>
<li>Browser histroy management.</li>
<li>MIME type and protocol handler.</li>
<li>Microdata.</li>
<li>Web Storage, a key-value pair storage framework that provides behavior similar to cookies but with larger storage capacity and improved API.</li>
</ul>
- The W3C publishes specifications for these seperately:
<ul>
<li>Geolocation.</li>
<li>Web SQL Database (a local SQL database), no longer maintained.</li>
<li>The indexed database API, an indexed hierarchal (formerly WebSimpleDB).</li>
<li>HTML5 File API, handles the file uploads and file manipulation.</li>
<li>Directories and System, an API intended to satisfy client-side-storage use cases not well served by databases.</li>
<li>File Writer, an API for writing to files from web applications.</li>
<li>Web Audio API, a high-level JavaScript API for processsing and synthesizing audio in web applications.</li>
<li>ClassList API.</li>
</ul>
- HTML5 cannot privide animation within web pages. Additional JavaScript and CSS3 functionality is necessary for animating
HTML5 elements.

#XHTML5 (XML-serialized HTML5)
- XML documents must be served with an XML internet media type (often called "MIME type") such as application/xhtml+xml
or application/xml, and must conform to the strict, well-formed syntax of XML.
- XHTML5 is simply an XML-serialized HTML5 data (e.g. not having any unclosed tags), sent with one of XML media types.
- HTML that has been written to conform to both the HTML and XHTML specifications - and which will therefore produce the
same DOM tree whether parsed as HTML or XML - is termed as "polygot markup".

#Error Handling
- HTML5 is designed so that old browsers can safely ignore new HTML5 constructs.
- In contrast to HTML 4.01, the HTML5 specification gives detailed rules for lexing and parsing, with the intent that
different compliant browsers will produce the same result in the case of incorrect syntax.
- Although HTML5 now defines a consistent behavior for "tag soup" documents, those documents are not regarded as conforming 
to the HTML5 standard.
