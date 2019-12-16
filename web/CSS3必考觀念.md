# Cascading Style Sheets
```
階層式樣式表（CSS；又稱串樣式列表、級聯樣式表、串接樣式表、層疊樣式表）
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
https://www.w3schools.com/css/tryit.asp?filename=trycss_howto_external
```
##### text.css
```
body {
  background-color: lightblue;
}

h1 {
  color: navy;
  margin-left: 20px;
}
```
```
使用外部的CSS標籤(test.css)，需再head中以link定義
```
```
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" type="text/css" href="test.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
### Four
```

```
```

```
###
```

```
```

```
###
```

```
```

```
###
```

```
```

```
###
```

```
```

```
###
```

```
```

```
###
```

```
```

```
