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
