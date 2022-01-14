# IMAGES:
Normal Images - 

<img src="https://www.myinstants.com/media/instants_images/jontron.png" alt="jon tron" style="width:100px;height:50px;">

```
<img src="https://www.myinstants.com/media/instants_images/jontron.png" alt="jon tron" style="width:100px;height:50px;">
```

<hr>

Gifs -

<img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="gif" style="width:300px;height:200px;">

same kind of code as the one for normal images 😸

<hr>

Image Floating - 

```
<p><img src="https://www.myinstants.com/media/instants_images/jontron.png" alt="jon tron" style="float:left;width:100px;height:50px;">This image probably is floating to the right of the text.</p>
```

<p><img src="https://www.myinstants.com/media/instants_images/jontron.png" alt="jon tron" style="float:left;width:100px;height:50px;">This image will float to left of the text.</p>
<hr>

Common Image  Formats - 

```
Abbreviation	File Format	File                      Extension
APNG	        Animated Portable Network Graphics	  .apng
GIF	          Graphics Interchange Format	          .gif
ICO	          Microsoft Icon	                      .ico, .cur
JPEG	        Joint Photographic Expert Group image	.jpg, .jpeg, .jfif, .pjpeg, .pjp
PNG	          Portable Network Graphics	            .png
SVG	          Scalable Vector Graphics	            .svg
```

Create Image Maps - 

`add maps and then give coordinates to the points try this out later....`

<hr>
# Favicon -

small image, to use this save your favicon image to the root directory of your webserver, or create a folder in the root directory called images, and save your favicon image in this folder. 
``` 
<link rel="icon" type="image/x-icon" href="/images/favicon.ico">
``` 
this link should display favicon image to the left of the page title.
<hr>

# Tables

```
<table> to start a table.
<tr> to define a table row.
<th> for table heading.
<td> for table data. (table cells)
```

## Adding border using css:

```
table, th, td{
 border: 1px solid black;
}
```

collapsed table border - 

``` 
with the above example just add border-collapse: collapse;
```
  
round table borders - 
``` 
table, th, td{
  border: 1px solid black; 
  border-radius: 10px;
 }
 ```
 P.S - to skip the border around the table, we can just leave the table from the css selector.
   
`We can choose the border-style of the table to change the appearance of the table border.`
 
border color - to change border color.
