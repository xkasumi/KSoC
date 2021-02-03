# メディアで人気記事リストを出したい

## 背景

メディアの記事数が増えてきたので、読むきっかけとなる導線を増やしたい。  
その一環として、よく読まれている記事を出して 1 人あたりの読む記事数を増やす。

## 実装イメージ

[WordPress Popluar Posts](https://ja.wordpress.org/plugins/wordpress-popular-posts/)のように、人気記事をリストとしてサイドバーかどこか（要検討）に配置するイメージ

## 考えられる実装方法

- 自前で PV カウンタを用意し、PV 数を保管集計する
- Google Analytics API で集計する
