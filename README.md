# Who are you?
[動画のリンク先](https://drive.google.com/drive/folders/12sfFwGB98a76Ub2LPS8PLfxKcxiJzxH8?usp=sharing)
[![IMAGE ALT TEXT HERE](https://jphacks.com/wp-content/uploads/2021/07/JPHACKS2021_ogp.jpg)](https://www.youtube.com/watch?v=LUPQFB4QyVo)

## 製品概要
### 背景(製品開発のきっかけ、課題等）
- コロナも収束に向かっていく中、対面でのコミュニケーションが増えていくと思います。オンラインだと小さく名前が表示されていますが、対面だとそんな機能はありません。
- そこで、対面であっても相手の基本情報を知ることができれば、話しかけるハードルもかなり下がるのではないかと考えました。

### 製品説明（具体的な製品の説明）
### 特長
#### 1. 特長1
- 顔画像を登録できる
#### 2. 特長2
- 顔認証により、登録した情報をカメラに表示できる

### 解決出来ること
- コミュニケーションコストを下げる！
### 今後の展望
- コミュニティごとに情報を登録する
- スマホでカメラの起動/情報の登録をできるようにする
### 注力したこと（こだわり等）
* 顔画像を登録する際、画像そのものではなく、特徴量化したものを保存することで、データベースに保存出来るようにした
* 

## 開発技術
### 活用した技術
#### フレームワーク・ライブラリ・モジュール
* flask
* cv2
* face_recognition
* numpy
* flask_sqlalchemy
* werkzeug.utils

#### デバイス
* pc

### 独自技術
#### ハッカソンで開発した独自機能・技術
* 一からアプリを作りました。

#### 製品に取り入れた研究内容（データ・ソフトウェアなど）（※アカデミック部門の場合のみ提出必須）
* face_recognition