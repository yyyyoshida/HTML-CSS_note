### HTML
```php
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1 id="title" class="a b c d e f g h i j k">しまぶーのIT大学</h1>
  <nav>
    <ul>
      <li>リンク → <a href="https://www.yahoo.co.jp">Yahoo</a></li>
      <li>リンク → <a href="https://google.com">Google</a></li>
      <li>リンク → <a href="https://youtube.com">Youtube</a></li>
      <li>リンク → <a href="https://apple.com">Apple</a></li>
    </ul>
  </nav>
</body>
</html>
```
### カスケード：CSSの順序
```php
h1 {
  color: red;
}
h1 {
  color: blue;
}
h1 {
  color: green;
}
/*奥が深い概念
```
### 詳細度
[参考サイト](https://developer.mozilla.org/ja/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance#specificity_2){:target="_blank"}
```php
h1 {
  color: red;
}
.a {
  color: blue;
}
h1 {
  color: green;
}
```
```php
#title {
  color: red;
}
.a {
  color: blue;
}
h1 {
  color: green;
}
```
