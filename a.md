# HTML-CSS_note
### divタグで基本的な構造設計
```php
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="div" content="div", initial-scale=1.0">
  <title>"divタグで基本的な構造設計"</title>
</head>
<body>
  <div style="width: 100%; height: 500px;">
    <div style="background-color: red; width: 100%; height: 10%;">ヘッダー</div>
    <div style="display:flex; width: 100%; height: 80%;">
      <div style="background-color: pink; width: 20%; height: 80%;">メニュー</div>
      <div style="background-color: yellow; width: 80%; height: 100%;">コンテンツ</div>
    </div>
    <div style="background-color: green; width: 100%; height: 10%;">フッター</div>
  </div>
</body>
</html>
```
![img](https://blog.nijibox.jp/wp-content/uploads/2022/08/%E5%9B%B3%E8%A1%A83.png)
### シングルカラムレイアウト1
```php
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="div" content="div", initial-scale=1.0">
  <title>"シングルカラムレイアウト"</title>
</head>
<body>
  <div style="width: 100%; height: 500px;">
    <div style="background-color: red; width: 100%; height: 10%;">ヘッダー</div>
    <div style="background-color: pink; width: 100%; height: 20%;">コンテンツ</div>
    <div style="background-color: yellow; width: 100%; height: 30%;">タイトル</div>
    <div style="background-color: green; width: 100%; height: 40%;">コンテンツ</div>
  </div>
  <div style="background-color: red; width: 100%; height: 100px;">
    サブコンテンツ1
  </div>
  <div style="background-color: blue; width: 100%; height: 100px;">
    サブコンテンツ2
  </div>
</body>
</html>
```
### シングルカラムレイアウト2
```php
 <html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="div" content="div", initial-scale=1.0">
  <title>"シングルカラムレイアウト2"</title>
</head>
<body>
  <div style="width: 100%; height: 500px;">
    <div style="background-color: red; width: 100%; height: 10%;">ヘッダー</div>
    <div style="background-color: pink; width: 40%; height: 20%; margin-left: 30%; margin-right: 30%;">コンテンツ</div>
    <div style="background-color: yellow; width: 80%; height: 30%; margin-right: 20%;">タイトル</div>
    <div style="background-color: green; width: 100%; height: 20%; margin-bottom: 20%">コンテンツ</div>
  </div>
  <div style="background-color: red; width: 100%; height: 100px;">
    サブコンテンツ1
  </div>
  <div style="background-color: blue; width: 100%; height: 100px;">
    サブコンテンツ2
  </div>
</body>
</html>
```
