# HTML Styles - CSS
Q - what is <q>css</q>?
<br><pre>-> Cascading Style Sheets is used to format the layout of a webpage.
It lets us control the color, font, size, spacing, position, background images and background colors + a lot more!</pre>

**Cascading means that a style applied to a parent element will also apply to all children elements with the parent**

> so if we set the color of the body text to "blue", all headings, para, and other elements will also be "blue".
<hr>

### Ways of using CSS:
```- Inline - by using style attribute inside HTML elements.
- Internal - by using a `<style>` element in the `<head>` section
- External - by using a `<link>` element to link to an external CSS file.

most common way is to keep css files in an external file. 
```
1. Inline CSS -

- An inline css is used to apply a unique style to a **single HTML element**.
- It uses the `style` attribute.

```
<h1 style="color:blue;">BLUE</h1>
<p style="color:red;">RED</p>
```
2. Internal CSS - 

- An internal css is used to define a style for a **single HMTL page**.
- It is define in the `<head>` section of an HTML page, within a `<style>` element.
```
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>
```
for the external style sheet ...it can be written in any text editor, should NOT contain any HTML code, and must be saved with a .css extension.

example:
```
########"styles.css"#########
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
```

css attributes and elements:
```
HTML style attribute for inline styling
HTML <style> element to define internal CSS
<link> element to refer to an external CSS file
<head> element to store <style> and <link> elements
CSS color property for text colors
CSS font-family property for text fonts
CSS font-size property for text sizes
CSS border property for borders
CSS padding property for space inside the border
CSS margin property for space outside the border
```

## Link to External CSS

- Using URL to link to a style sheet.
```
<link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">
```
- Style sheet located in the HTML folder on the current web site.
```
<link rel="stylesheet" href="/html/styles.css">
```
- Style sheet located in the same folder as the current page.
```
<link rel="stylesheet" href="styles.css">
```
