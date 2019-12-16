# HTML標籤(Tag)
```
https://www.w3schools.com/tags/tag_html.asp
https://www.runoob.com/html/html5-intro.html
```
#  HTML程式格式 xxx.html
```
<!DOCTYPE HTML>
<html>
<head>
<title>Title of the document</title>
</head>

<body>
The content of the document......
</body>

</html>
```

# 十大HTML必考標籤
### <!DOCTYPE HTML>
```
<!DOCTYPE HTML>宣告必須是html中第一行
宣告這個檔案是html格式
```
```
<!DOCTYPE html>
<html>
<head>
<title>Title of the document</title>
</head>

<body>
The content of the document..
</body>

</html>
```
### title
```
<title> </title>
裡面的文字將會是這個檔案的標題
```
```
<!DOCTYPE html>
<html>

<head>
  <title>HTML Reference</title>
</head>

<body>
The content of the document......
</body>

</html>
```
### h1~h6
```
<h1></h1>
用於改變裡面文字的大小
h1最大 h6最小
```
```
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```
### 超連結
```
HTML使用標籤<a>來設置超文字連結
<a href="網址">文字</a>
```
```

<a href="https://www.w3schools.com">Visit W3Schools.com!</a>

```
### 表格
```
https://www.w3schools.com/tags/tag_table.asp
<table border="1">
    <tr>
        <td>row 1, cell 1</td>
        <td>row 1, cell 2</td>
    </tr>
    <tr>
        <td>row 2, cell 1</td>
        <td>row 2, cell 2</td>
    </tr>
</table>
```
### img
```
<img src="smiley.gif" alt="Smiley face" height="高" width="寬">
將圖片放入網頁裡面
```
```
<!DOCTYPE html>
<html>
<body>

<img src="smiley.gif" alt="Smiley face" width="42" height="42">

</body>
</html>
```
### audio
```
<audio  一堆屬性> </audio>
https://www.w3schools.com/tags/tag_audio.asp
```
```
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
```
### video
```
<video  一堆屬性>   </video>
https://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_video
```
```
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```
### artice
```
artice用來標示網頁裡面的本文或者是獨立出來的內容
```
```
<article>
  <h1>Google Chrome</h1>
  <p>Google Chrome is a free, open-source web browser developed by Google, released in 2008.</p>
</article>
```

###  section
```
section用來將本文切同的主題區段，或將一篇文章切割為不同的章節或段落
```
```
<section>
  <h1>WWF</h1>
  <p>The World Wide Fund for Nature (WWF) is....</p>
</section>

```
