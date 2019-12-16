# Cascading Style Sheets
```
階層式樣式表（CSS；又稱串樣式列表、級聯樣式表、串接樣式表、層疊樣式表）
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
無需下載，快速套用小圖案
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

```
```

```
### Seven
```

```
```

```
### Eight
```

```
```

```
### Nine
```

```
```

```
### Ten
```

```
```

```
