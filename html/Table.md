# Table (continuation)

Header for mutliple columns (use colspan with th attribute)
```
<th colspan="2"> table_content <th>
```
<hr>

## Table captions

We can use the `<caption>` inside the `<table>` to give a caption to a table.
<hr>

## Table padding and spacing

cell padding is the space between the cell edge and cell content (inside part). 0 by default.
```
th, td{
    padding: 15px;
}
```
we can specify padding areas using  `padding-top`, `padding-bottom`, `padding-left` and `padding-right`.
<br>
<br>
Cell spacing is the space between each cell of the table.
By default is set at 2px.
```
table {
    border-spacing: 20px;
}
```
we use the border-spacing on table attribute to change the border-spacing.
<hr>

## Table colspan and rowspan

to make a cell span over multiple columns we use `<colspan="">` with the `<th>` attribute.
<br>
<br>
To make a cell span over mutliple rows, we use  `<rowspan="">` 
<hr>

## Table styling

we can achieve a zebra stripes effect by doing this:
``` 
tr:nth-child(even){
    background-color: color_name;
}
```
this is color ever even row with the color_name that is specified
<br>
<br>
To get the table columns to be zebra striped we have to use the `:nth-child(even)` with `td` and `th` instead of  `tr`.
```
td:nth-child(even), th:nth-child(even){
    background-color: color_name;
}
```
Combing vertical and horizontal zebra stripes can be done with using the combination of the two examples above:
```
tr:nth-child(even){
    background-color: rgba(values);
}
th:nth-child(even), td:nth-child(even){
    background-color: rgba(values);
}
```
if we use rgba we can define the transparency of the color which allows for an overlapping effect.
<br>
<br>
Horizontal Dividers:
<br>
by using `border-bottom` property to all `tr` elements we can get horizontal dividers.
``` 
tr{
    border-bottom: 1px solid #ddd;
}
```

Hoverable table - 
<br>
the usage of `:hover` on `tr` highlights the table row when mouse it brought over it.
```
tr:hover {
    background-color: color_name;
}
```
P.S - css is added in the head part of the code. (for internal css).
<br>
<br>
Colgroup - colgroup is used with a column element which spans over a set number of columns to define a style for the columns.
```
<colgroup>
  <col span="2" style="background-color: #D6EEEE">
</colgroup>
```
only a very limited selection of CSS properties are allowed to be used in the colgroup:

- width property 
- visibility property
- background properties
- border properties

all other css properties don't have any effect on tables.
<br>
<br>
<u>Multiple col elements</u><br>
To style more columns with different syles we can give more `<col>` elements inside colgroup.
```
<colgroup>
    <col span="2" style="background-color: color_name;">
    <col span="3" style="background-color: color_name;">
</colgroup>
```
to style colgroups in the middle of the table insert "empty" `<col>` elements (with no style) for the columns before the desired colgroup.


we can hide the columns with `visibility: collapse`  propertiy inside the `<colgroup>` attribute.
