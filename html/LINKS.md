# HMTL Links 
They are just hyperlinks that jump to another document when clicked.

```
Absolute URLs VS Relative URLs

-> Absolute URLs are links to another webpage with a full web address.
-> Relative URLs are liks to pages within the same website ... like a local link(don't need the "https://www" part)
```
<hr>

## Images as link

<a href="https://www.google.com/search?q=cat+images&sxsrf=AOaemvKv1BuwIyTJXfJRq8oPFS5uc_IpJA:1641811806923&source=lnms&tbm=isch&sa=X&sqi=2&ved=2ahUKEwjJ_afMgaf1AhW8GbkGHcZBDwAQ_AUoAXoECAEQAw&biw=718&bih=821&dpr=1"><img src="https://i.pinimg.com/736x/33/32/6d/33326dcddbf15c56d631e374b62338dc.jpg" alt="Image with a link" style="width:42px;height:42px;"></a><br>click at this cat to see more cats 😼
<hr>

## Links to Email

<a href="mailto:pranavk0217@gmail.com">Wanna send mail? </a>👀

```
<a href="mailto:pranavk0217@gmail.com">Wanna send mail? </a>👀
```
<hr>

## Button as link 🤯
```
<button onclick="document.location='https://www.w3schools.com/html/html_links.asp'">click moi</button>
```
something like this can be made to make buttons that act as hyperlinks.
<hr>

## Link titles

these are mostly title attributes so that when the mouse moves over the link, it shows a small description about the link!
<br> Like this link - <a href="https://www.youtube.com/watch?v=46pra8NwhzU" target="_blank" title="Professor explaining theory of relativity">Click moi</a>
<hr>

p.s. - take a look at more of the absolute URL and relative URL stuff later...

<hr>

## Bookmark in HTML
for very long web pages... we can use bookmarks, for this we first create the bookmark and then link it.
<br>
<br>
when the link is clicked the page will scroll up or down to the location of the bookmark.
```
<h2 id="C4">Chapter 4</h2> <!--Creates the bookmark-->
<a href="#C4">Jump to chapter 4</a> <!--Adding the link-->
<a href="some_other_page.html#C4">Jump to chapter 4</a> <!--Go to bookmark on another page-->
```
- id attribute (id="value") <- defines a bookmark
- href attribute (href="#value") <- link to the bookmark
<hr>

# WITH CSS USE : NOT =
