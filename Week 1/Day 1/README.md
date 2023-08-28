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