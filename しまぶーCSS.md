### HTML
```php
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>しまぶーのIT大学</h1>
    <h2>プログラミング講座CSS編</h2>
    <nav>
      <ul>
        <li><a href="https://www.yahoo.com">Yahooの本家</a></li>
        <li><a href="https://www.yahoo.co.jp">Yahoo日本</a></li>
        <li><a href="https://google.com">Google本家</a></li>
        <li><a href="https://www.google.co.jp">Google日本</a></li>
        <li><a href="https://apple.com">Apple</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>記事の一覧</h1>
    <article>
      <h1>記事のタイトル</h1>
      <p>ダミー文章: Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolor inventore, velit ut deserunt error suscipit, at voluptatum recusandae quo atque ab nam, totam eum asperiores similique ea eligendi laudantium excepturi!</p>
      <p>ダミー文章: Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolor inventore, velit ut deserunt error suscipit, at voluptatum recusandae quo atque ab nam, totam eum asperiores similique ea eligendi laudantium excepturi!</p>
      <p>ダミー文章: Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolor inventore, velit ut deserunt error suscipit, at voluptatum recusandae quo atque ab nam, totam eum asperiores similique ea eligendi laudantium excepturi!</p>
    </article>
  </main>
</body>
</html>
```
# 属性によるセレクター
### aタグでhref属性を持ってるものに対して
```php
a[href] {
  color: red;
}

```
### 部分文字列一致セレクター
```php
a[href="https://www.yahoo.com"]
{
  color: red;
}
```
### 前方一致
```php
a[href^="https://www"]
{
  color: red;
}
```
### 部分一致
```php
a[href*='google'] {
  color: red;
}
```
### 後方一致
```php
a[href$='.co.jp'] {
  color: red;
}
```
# 疑似クラスおよび疑似要素によるセレクター
### 疑似クラス :first-child, :first-of-type
```php
article p:first-of-type {
  color: red;
}
```
```php
article p:first-child {
  color: red;
}
```
### 疑似クラス :last-of-type, last-child
```php
article p:last-of-type {
  color: red;
}
```
```php
article p:last-child {
  color: red;
}
```
### 疑似クラス :nth-of-type(), :nth-child() 順番指定
```php
article p:nth-of-type(2) {
  color: red;
}
```
### 疑似クラス :not
```php
article p:not(:first-of-type) {
  color: red;
}
```
### 疑似クラス :hover
```php
p:hover {
  background-color: pink;
}
p:not(:hover) {
  background-color: pink;
}
```
### 疑似要素 ::after, ::before
```php
h1::after {
  content: '!!!!';
}
```
```php
h1::before {
  content: '!!!!';
}
```
### 疑似クラス ::first-line, ::first-letter
```php
p::first-line {
  color: red;
}
```
```php
p::first-letter {
  color: red;
}
# 結合子
```
