# PyCon JPとは

PyCon JPは日本国内外のPythonユーザーが一堂に会し、互いに交流を深め、知識を分け合い、新たな可能性を見つけられる場所として毎年9月中旬に開催されるカンファレンスです。

PyCon JP 2019は2019年9月14日にHENNGE株式会社で行われたスプリントから始まり、9月15日チュートリアルと9月16日〜17日のカンファレンスを大田区産業プラザPiOで行いました。来場者は4日間で約1160人と大盛況でした。ご参加いただいた皆様、本当にありがとうございました。

ここでは16〜17日に行われたカンファレンスのなかから、選りすぐりの注目セッションやイベントをレポートしていきます。

# 1日目基調講演

@ussy

![写真タイトル](./_static/hogehuga.jpg)

### 資料リンク

* [動画]()
* [スライド]()

# ビギナーズセッション 「Python開発を円滑に進めるためのツール設定」- Atsushi Odagiri

(横山直敬)

Atsushi Odagiri氏によるビギナーズセッション「Python開発を円滑に進めるためのツール設定」をレポートします。

ビギナーズセッションとは、Pythonの初心者が次のステップに踏み出すきっかけづくりを提供するセッションです。i

「Python開発を円滑に進めるツール」を使うことの意義はつまらないミスを減らすことにあると小田切氏は言います。
ツールを実行するだけで今まで60%だった品質が80%にまで上がることもあるのです。
また、ツールによるチェックを経たコードはより本質的なコードレビューに繋がります。

Python開発を支えるツールには大きく分けて3つの種類があります。

1. linterツール: コーディング規約に沿ったコードになっているかチェックするツール

    - 例. flake8, black

2. 型アノテーションツール: Pythonは動的型付け言語ですが、型アノテーションツールを使うことで変数や戻り値に想定外の型のデータが使われていないかチェックすることができます。

    - 例. mypy

3. テストツール: ユニットテストを実行するツール。複数のPythonバージョンを指定できるツールもある。

    - 例. pytest, tox

ビギナーセッションでは以下のツールの使い方・おすすめの設定が解説されました。

- flake8

- black

- mypy

- pytest

- tox

各ツールの使い方・設定の詳細についてはセッションの動画をご覧ください。

ツールはCI時に実行したり、Gitのpre-commitに設定してコミット前に実行することもできますが、最も望ましいのはエディタ上で自動実行することです。
コードの編集や保存時にツールからの警告が出たり、コードのフォーマットが自動に行われるように設定することができます。
エディタ上で自動実行されることの利点はツールからの警告をすぐにコードに反映できることにあります。
Visual Studio Code, emacs, vim, PyCharmといった主なエディタはツールの自動実行に対応しています。

特に設定しておくと良いのは、以下の3つです。

- 編集中のlinterツール(flake8やmypy)の警告を出す

- コードの保存と同時にblackでフォーマッティング

- テスト実行結果からエラー箇所へのジャンプ

最後に「退屈なこと(コーディング規約や型アノテーションのチェック)は機械(ツール)がやってくれる。ツールを活用してレビュアーが本質的なレビューに集中できるようにすることが開発の効率化につながる」と小田切氏は述べました。
また、豊富なアドオンがあるテストツールpytestについて各自のプロジェクトに導入できそうなアドオンを調べ、CIに導入してみることを提案しました。

![ビギナーズセッションを行う小田切氏](./_static/aodag_beginners_session.jpg)

- [動画](https://www.youtube.com/watch?v=1FcLwOpXuAI)

- [スライド](https://www.slideshare.net/aodag/python-172432039) 

# トークセッション（1）

@ussy

![写真タイトル](./_static/hogehuga.jpg)

### 資料リンク

* [動画]()
* [スライド]()

# トークセッション（2）

@ussy

![写真タイトル](./_static/hogehuga.jpg)

### 資料リンク

* [動画]()
* [スライド]()

# トークセッション（3）

@HiraoMotoki

![写真タイトル](./_static/hogehuga.jpg)

### 資料リンク

* [動画]()
* [スライド]()


# トークセッション（4）

@nikkie

![写真タイトル](./_static/hogehuga.jpg)

### 資料リンク

* [動画]()
* [スライド]()

# 1日目ライトニングトーク

説明 @ksugahara

## 1つ目タイトル

@ussy

![写真タイトル](./_static/hogehuga.jpg)


## 2つ目タイトル

@nikkie

![写真タイトル](./_static/hogehuga.jpg)


## 1日目ライトニングトーク一覧

@ussy

今回ご紹介しきれなかったものも含め、1日目のライトニングトークの一覧はこちらです。また、Pythonの公式アカウントに[ライトニングトークの動画]()がアップロードされています。



# 次回は

@nikkie

1日目のカンファレンスレポートは以上です。今回紹介できなかったセッションも多数あるのですが、それらは下記のリンクから見ることができます。みなさまの気になるセッションやトークは見つかりましたか？

* [Youtube PyCon JP公式アカウント](https://www.youtube.com/channel/UCxNoKygeZIE1AwZ_NdUCkhQ)

2日目のレポートも後日、公開しますので楽しみにしてください！