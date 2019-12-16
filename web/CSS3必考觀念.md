# Cascading Style Sheets
```
階層式樣式表（CSS；又稱串樣式列表、級聯樣式表、串接樣式表、層疊樣式表）
使用CSS階層樣式表可以達到[快速]美化效果
```
```
https://www.w3schools.com/css
```
# CSS3 基本格式
```
https://www.w3schools.com/tags/tryit.asp?filename=tryhtml_style
```

```
<!DOCTYPE html>
<html>
<head>
<style>
h1 {color:red;}
p {color:blue;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
# CSS3十大必考標籤
### One
```
https://www.w3schools.com/css/tryit.asp?filename=trycss_syntax1
```
```
p {
  color: red;
  text-align: center;
}

所有<p>元素的字體將呈現為紅色並且置中對齊
```
```
<!DOCTYPE html>
<html>
<head>
<style>
p {
  color: red;
  text-align: center;
} 
</style>
</head>
<body>

<p>Hello World!</p>
<p>These paragraphs are styled with CSS.</p>

</body>
</html>
```

### Two
```
https://www.w3schools.com/css/tryit.asp?filename=trycss_syntax_id
```
```
#x1 {
  text-align: center;
  color: red;
}

id是x1的元素字體將呈現為紅色並且置中對齊
```
```
<!DOCTYPE html>
<html>
<head>
<style>
#x1 {
  text-align: center;
  color: red;
}
</style>
</head>
<body>

<p id="x1">Hello World!</p>
<p>This paragraph is not affected by the style.</p>

</body>
</html>
```
### Three
```
https://www.w3schools.com/css/tryit.asp?filename=trycss_background-color_elements
```
```
h1 {
  background-color: green;
}

div {
  background-color: lightblue;
}

p {
  background-color: yellow;
}

h1、div、p元素有三種不同的顏色
```
```
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  background-color: green;
}

div {
  background-color: lightblue;
}

p {
  background-color: yellow;
}
</style>
</head>
<body>

<h1>CSS background-color example!</h1>
<div>
This is a text inside a div element.
<p>This paragraph has its own background color.</p>
We are still in the div element.
</div>

</body>
</html>
```
### Four
```
https://www.w3schools.com/css/tryit.asp?filename=trycss_icons_fa
```
```
無需下載，快速套用[小圖案]icon
```
```
<!DOCTYPE html>
<html>
<head>
<script src="https://kit.fontawesome.com/a076d05399.js"></script>
</head>
<body>

<i class="fas fa-cloud"></i>
<i class="fas fa-heart"></i>
<i class="fas fa-car"></i>
<i class="fas fa-file"></i>
<i class="fas fa-bars"></i>

</body>
</html>
```
### Five
```
https://www.w3schools.com/css/tryit.asp?filename=trycss_link
```
```
/* 尚未按下的連結樣式 */
a:link {
  color: red;
}

/* 按下後的連結樣式 */
a:visited {
  color: green;
}

/* 滑鼠移過的連結樣式 */
a:hover {
  color: hotpink;
}

/* 選中時的連結樣式 */
a:active {
  color: blue;
}
```
```
CSS也有[超連結]，系分為以下四種：
1. a:link - 尚未按下的連結樣式
2. a:visited - 按下後的連結樣式
3. a:hover - 滑鼠移過的連結樣式
4. a:active - 選中時的連結樣式
```
```
<!DOCTYPE html>
<html>
<head>
<style>
/* unvisited link */
a:link {
  color: red;
}

/* visited link */
a:visited {
  color: green;
}

/* mouse over link */
a:hover {
  color: hotpink;
}

/* selected link */
a:active {
  color: blue;
}
</style>
</head>
<body>

<p><b><a href="default.asp" target="_blank">This is a link</a></b></p>
<p><b>Note:</b> a:hover MUST come after a:link and a:visited in the CSS definition in order to be effective.</p>
<p><b>Note:</b> a:active MUST come after a:hover in the CSS definition in order to be effective.</p>

</body>
</html>
```
### Six
```
https://www.w3schools.com/css/tryit.asp?filename=trycss_list-style-type_ex
```
```
清單式樣式，可分成許多階層、圖案、樣式
```
```
<!DOCTYPE html>
<html>
<head>
<style>
ul.a {
  list-style-type: circle;
}

ul.b {
  list-style-type: square;
}

ol.c {
  list-style-type: upper-roman;
}

ol.d {
  list-style-type: lower-alpha;
}
</style>
</head>
<body>

<p>Example of unordered lists:</p>
<ul class="a">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ul>

<ul class="b">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ul>

<p>Example of ordered lists:</p>
<ol class="c">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ol>

<ol class="d">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
</ol>

</body>
</html>
```
### Seven
```
https://www.w3schools.com/css/tryit.asp?filename=trycss_table_color
```
```
自訂表格內部樣式、框線、位置、顏色等等
```
```
<!DOCTYPE html>
<html>
<head>
<style>
table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  text-align: left;
  padding: 8px;
}

tr:nth-child(even){background-color: #f2f2f2}

th {
  background-color: #4CAF50;
  color: white;
}
</style>
</head>
<body>

<h2>Colored Table Header</h2>

<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
    <td>$150</td>
  </tr>
  <tr>
    <td>Joe</td>
    <td>Swanson</td>
    <td>$300</td>
  </tr>
  <tr>
    <td>Cleveland</td>
    <td>Brown</td>
    <td>$250</td>
</tr>
</table>

</body>
</html>
```
### Eight
```
https://www.w3schools.com/css/tryit.asp?filename=trycss_position_absolute
```
```
設定元素出現的位置
```
```
<!DOCTYPE html>
<html>
<head>
<style>
div.relative {
  position: relative;
  width: 400px;
  height: 200px;
  border: 3px solid #73AD21;
} 

div.absolute {
  position: absolute;
  top: 80px;
  right: 0;
  width: 200px;
  height: 100px;
  border: 3px solid #73AD21;
}
</style>
</head>
<body>

<h2>position: absolute;</h2>

<p>An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed):</p>

<div class="relative">This div element has position: relative;
  <div class="absolute">This div element has position: absolute;</div>
</div>

</body>
</html>
```
### Nine
```
https://www.w3schools.com/css/tryit.asp?filename=trycss_dropdown_image
```
```
圖片預覽功能，滑鼠移動到圖片上方，出現較大圖片
```
```
<!DOCTYPE html>
<html>
<head>
<style>
.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.desc {
  padding: 15px;
  text-align: center;
}
</style>
</head>
<body>

<h2>Dropdown Image</h2>
<p>Move the mouse over the image below to open the dropdown content.</p>

<div class="dropdown">
  <img src="img_5terre.jpg" alt="Cinque Terre" width="100" height="50">
  <div class="dropdown-content">
  <img src="img_5terre.jpg" alt="Cinque Terre" width="300" height="200">
  <div class="desc">Beautiful Cinque Terre</div>
  </div>
</div>

</body>
</html>
```
### Ten
```
https://www.w3schools.com/css/tryit.asp?filename=trycss_image_opacity
```
```
設定圖片透明度
```
```
<!DOCTYPE html>
<html>
<head>
<style>
img {
  opacity: 0.5;
  filter: alpha(opacity=50); /* For IE8 and earlier */
}
</style>
</head>
<body>

<h1>Image Transparency</h1>
<p>The opacity property specifies the transparency of an element. The lower the value, the more transparent:</p>

<p>Image with 50% opacity:</p>
<img src="img_forest.jpg" alt="Forest" width="170" height="100">

</body>
</html>
```
