First day of the 100 days of coding.

Task for the day are:

- Welcome to This Course! [Day 1]
- Stuck in the Course? We Got you Covered! [Day 1]
- How To Use The Attached Code [Day 1]
- Module Introduction [Day 1]
- How to Create a Website [Day 1]

- Creating our First HTML Page
  What Are HTML & CSS?
  HTML, HyperText Markup Language, gives content structure and meaning by defining that content as, for example, headings, paragraphs, or images. CSS, or Cascading Style Sheets, is a presentation language created to style the appearance of content—using, for example, fonts or colors.

The two languages—HTML and CSS—are independent of one another and should remain that way. CSS should not be written inside of an HTML document and vice versa. As a rule, HTML will always represent content, and CSS will always represent the appearance of that content.

With this understanding of the difference between HTML and CSS, let’s dive into HTML in more detail.

Understanding Common HTML Terms
While getting started with HTML, you will likely encounter new—and often strange—terms. Over time you will become more and more familiar with all of them, but the three common HTML terms you should begin with are elements, tags, and attributes.

**Elements**
Elements are designators that define the structure and content of objects within a page. Some of the more frequently used elements include multiple levels of headings (identified as <h1> through <h6> elements) and paragraphs (identified as the <p> element); the list goes on to include the <a>, <div>, <span>, <strong>, and <em> elements, and many more.

Elements are identified by the use of less-than and greater-than angle brackets, < >, surrounding the element name.

**Tags**
The use of less-than and greater-than angle brackets surrounding an element creates what is known as a tag. Tags most commonly occur in pairs of opening and closing tags.

An opening tag marks the beginning of an element. It consists of a less-than sign followed by an element’s name, and then ends with a greater-than sign; for example, <div>.

A closing tag marks the end of an element. It consists of a less-than sign followed by a forward slash and the element’s name, and then ends with a greater-than sign; for example, </div>.

The content that falls between the opening and closing tags is the content of that element. An anchor link, for example, will have an opening tag of <a> and a closing tag of </a>. What falls between these two tags will be the content of the anchor link.

So, anchor tags will look a bit like this:

<a>...</a>

**Attributes**
Attributes are properties used to provide additional information about an element. The most common attributes include the id attribute, which identifies an element; the class attribute, which classifies an element; the src attribute, which specifies a source for embeddable content; and the href attribute, which provides a hyperlink reference to a linked resource.

Attributes are defined within the opening tag, after an element’s name. Generally attributes include a name and a value. The format for these attributes consists of the attribute name followed by an equals sign and then a quoted attribute value. For example, an <a> element including an href attribute would look like the following:

1
2
<a href="http://shayhowe.com/">Shay Howe</a>

![Alt text](html-syntax-outline.png)

**Setting Up the HTML Document Structure**
HTML documents are plain text documents saved with an .html file extension rather than a .txt file extension. To begin writing HTML, you first need a plain text editor that you are comfortable using. Sadly this does not include Microsoft Word or Pages, as those are rich text editors. Two of the more popular plain text editors for writing HTML and CSS are Dreamweaver and Sublime Text. Free alternatives also include Notepad++ for Windows and TextWrangler for Mac.

All HTML documents have a required structure that includes the following declaration and elements: <!DOCTYPE html>, <html>, <head>, and <body>.

The document type declaration, or <!DOCTYPE html>, informs web browsers which version of HTML is being used and is placed at the very beginning of the HTML document. Because we’ll be using the latest version of HTML, our document type declaration is simply <!DOCTYPE html>. Following the document type declaration, the <html> element signifies the beginning of the document.

Inside the <html> element, the <head> element identifies the top of the document, including any metadata (accompanying information about the page). The content inside the <head> element is not displayed on the web page itself. Instead, it may include the document title (which is displayed on the title bar in the browser window), links to any external files, or any other beneficial metadata.

All of the visible content within the web page will fall within the <body> element.

Self-Closing Elements
In the previous example, the <meta> element had only one tag and didn’t include a closing tag. Fear not, this was intentional. Not all elements consist of opening and closing tags. Some elements simply receive their content or behavior from attributes within a single tag. The <meta> element is one of these elements. The content of the previous <meta> element is assigned with the use of the charset attribute and value. Other common selfclosing elements include

<br><embed><hr><img><input><link><meta><param><source><wbr>
The structure outlined here, making use of the <!DOCTYPE html> document type and <html>, <head>, and <body> elements, is quite common. We’ll want to keep this document structure handy, as we’ll be using it often as we create new HTML documents.

**To create the first html file**
**Install editor of choice (There are different types of editor <VsCode/>, <Atom/>, <Notepadd ++ />)
**then create an html file(i.e an HTML file ends wit .html )

Escape HTML
Escaping HTML characters in a string means replacing the:

less than symbol (<) with &lt;
greater than symbol (>) with &gt;
double quotes (") with &quot;
single quote (’) with &#39;
ampersand (&) with &amp;
