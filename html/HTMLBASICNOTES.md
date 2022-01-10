# HTML NOTES:

mainly used for structure of a site I.E. HOW to display the things in a webpage.

* `<!DOCTYPE HTML>` defines that it is HTML5. (document type declaration)

basics - `<html><head><title><body><p><h1>`

headings - `<h1> to <h6>`,para - `<p>`,links - `<a>`, image - `<img>` (has src, alt, width, height parameterrs)

`<br>` <-breaks 

***always close a <> with </>***

html is not case sensitive 🤓

## <u>Attributes</u>
> What is an attribute?
> - additional information about elements.
> - usually in name/value pairs.

### href attribute:
* `<a>` tag for hyperlink and `href` specifies URL of the linked page.

### src attribute: 
* src specifies the path to the image.
* alt - defines alt text.

### style attribute:
* adds styles to an elements, such as color, font, size, and more.

### lang attribute:
* should always include the `lang` attribute..... meant to assist search engines and browsers.
`<html lang = 'en'>`
<br> country codes can also be added to the language code in the `lang` attribute. eg : `<html lang='en-US'>`

### title attribute:
defines some extra info about an element. 
> value of the title attribute will be displayed as a tooltip when you mouse over the element
<br>`<p title="I'm a tooltip">This is a para</p>`
____________________

## ***BIGGER HEADINGS***
<h1 style="font-size:60px;">This is a bigger heading</h1>
* this kind of bigger heading can be done using css font-size in style of the header.
<hr>
🙄 that separation was made using <b><u>hr</u></b>.<hr>

for paras we use `p` it ignores all the line separation and also the spaces in the middle.

`br` is used for adding a line break. [if you want a line break without starting a new para]

***Use the `pre` element*** to display in preformatted text.
I.E. basically it preserves both spaces and lines.


<hr>
<h3><u>HTML STYLES</u></h3>
syntax => <pre>tagname style = "property:value"</pre>

any element + style lets you customize that specific element.

> we can change all aspects of the text like color size alignment etc. etc.
<hr>
<h2>
HTML FOMATTING ELEMENTS:</h2>
<pre> 
<b> - Bold text - b</b>
<strong> - Important text - strong</strong>
<i> - Italic text - i </i>
<em> - Emphasized text - em</em> 
<mark> - Marked text - mark</mark>
<small> - Smaller text - small</small>
<del> - Deleted text - del </del>
<ins> - Inserted text - ins </ins>
<sub> - Subscript text - sub</sub>
<sup> - Superscript text - sup</sup>
</pre>

* em is read by the screen reader with verbal stress
* strong element defines text with strong importance.

<br>
blockquote defines a section that is quoted from another source *usually this is indented*
<hr>
<br>
<q> q is used for short quotations</q> 
<br>
<br>
<hr>
<abbr title= "abbreviations">abbr</abbr> is used for abbreviations.
<br>
<br>
<hr>
<address> address element<br>
is used for<br>
giving address<br>
renders in italics</address>
<hr>
<cite>cite</cite> tag defines the title of a creative work. This too renders the text in italics.
<hr>
<bdo dir='rtl'> bdo lets the text to written from right to left</bdo>
<br>
<mark>good luck trying to read that lol</mark> {bdo}
<hr>

<!--this is the comment tag-->

<hr>

# COLOURRSSS 🖍

<p style="background-color:Tomato;">I guess this text will be tomato in colour</p>

> element style="background-color:color_name;" <----syntax

<h1 style="color:DodgerBlue;"> Hopefully this text is blue</h1>

> syntax - style="color:color_name;"

<h3> border color</h1>

> syntax = element style="border:px solid colour_name;"

we can also use colour values for very specific colours.
<hr>

## **Colouring options**
We have rgb values and rgba values ..... rgba have an extra alpha value which decides the opacity of color.
- the alpha value ranges from 0.0 to 1.0

Then we also have the hex color values: used with <pre>#rrggbb</pre>

then finally we also have the HSL and HSLA colors.
- hsl stands for hue, saturation, lightness values.
- saturation is the intinsity of a color.
- lightness of a color is the amount of light you want to give to the color.

The A is in HSLA is again for alpha i.e. the opacity of the color.
