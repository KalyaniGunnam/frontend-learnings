# Header Tags (`<h1> to <h6>`):
- Header tags are used for titles or large text.
- `<h1>` defines the largest heading, and `<h6>` defines the smallest heading.
Example:
```
<h1>This is an H1 heading</h1>
<h2>This is an H2 heading</h2>
<h3>This is an H3 heading</h3>
<h4>This is an H4 heading</h4>
<h5>This is an H5 heading</h5>
<h6>This is an H6 heading</h6>
```

# Paragraph Tags (`<p>`):
- Use `<p>` tags to define a paragraph of text.
Example:
```
<p>This is a paragraph of text.</p>
```
- VS Code Shortcut:
To quickly generate placeholder text, type lorem and press Tab.

# Line Breaks (`<br>`):
- Use the `<br>` tag to insert a line break.
Example:
```
<p>This is a line of text.<br>This is a new line.</p>
```
- The `<br>` tag is self-closing, so it does not need a closing tag.

# Horizontal Rule (`<hr>`):
- The `<hr>` tag creates a horizontal line across the page.
Example:
```
<h1>Title</h1>
<hr>
<p>This is a paragraph below a horizontal line.</p>
```

# Preformatted Text (`<pre>`):
- The `<pre>` tag preserves all spaces and line breaks inside it.
```
<pre>
This text
is preformatted,
so line breaks and spaces
are preserved.
</pre>
```

# Comments:
- Comments are notes for developers and are not displayed in the browser.
Syntax:
```
<!-- This is a comment -->
```
Example:
```
<h1>My Website</h1>
<!-- This heading is the title of the webpage -->
```

# Example HTML Document:

```
<!DOCTYPE html>
<html>
  <head>
    <title>HTML Basics</title>
  </head>
  <body>
    <!-- Header Tags -->
    <h1>This is an H1 heading</h1>
    <h2>This is an H2 heading</h2>
    <h3>This is an H3 heading</h3>
    <h4>This is an H4 heading</h4>
    <h5>This is an H5 heading</h5>
    <h6>This is an H6 heading</h6>

    <!-- Paragraph with Placeholder Text -->
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

    <!-- Line Break -->
    <p>This is the first line.<br>This is the second line.</p>

    <!-- Horizontal Rule -->
    <hr>

    <!-- Preformatted Text -->
    <pre>
    Line 1
    Line 2
    Line 3
    </pre>

    <!-- Comment -->
    <!-- This is a comment and will not appear in the browser -->
  </body>
</html>
```

# Note
Till this point all the tags are called **text formatting tags**, which means *text formatting tags in HTML are used to style,structure and emphasize text content without relying on CSS. These tags help nake text bold,italic, underlined,highted,small,big, etc..*
```
<h1> to <h6> ---> Headings
<p> ---> Paragraph
<b>, <strong> ---> Bold
<i>, <em> ---> Italic
<u> ---> Underlined
<small> ---> Smaller text
<mark> ---> Highlight text
<sub> & <sup> ---> Subscript and Superscript
<pre> ---> Preformatted text
<hr> ---> Horizontal line
<br> ---> Line break
```
