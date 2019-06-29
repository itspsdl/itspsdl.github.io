---
layout: default
---
# ソフトウェア開発演習（CSC.T424）

* IT特別教育プログラム科目

## お知らせ

* 演習中はインターネット接続が必要になります．開発用のラップトップPCで学内無線LAN接続サービスを利用できるように設定しておいてください．(4/5)
* 教材（Android端末）貸与時に渡した資料に従って，初期設定を済ませておいてください．(4/5)
* 初回は4月12日（金）7-10限にW371講義室で行います．(4/5)

## 担当

* 林 晋平（情報理工学院）

## 講義時間・講義室

* 金曜日 7-10限（15:05-18:20）
* W371講義室

## 講義の概要とねらい

本演習では，モバイルアプリケーションの設計，開発，デバッグ，デプロイメントについて学ぶ．
具体的には，モバイルUIフレームワーク，ネットワーキング，位置情報，センサ，グラフィックスおよびセキュリティ等のトピックを扱う．

演習を通して，モバイルアプリケーション開発に関する知識・技術のみならず，ソフトウェア開発に必要なツールやグッドプラクティスについて身につけることを目標とする．

## 到達目標

* Androidアプリケーションの設計，実装，デバッグ，デプロイメントができるようになること．

## 関連科目・履修条件等

* システム開発プロジェクト基礎第一・第二
* システム開発プロジェクト応用第一・第二
* チーム開発集中演習

IT特別教育プログラム科目の学生を対象とする．

## 成績

* 演習課題
* 個人プロジェクト

## 個人プロジェクト発表会（デモ）

以下の日程で個人プロジェクト発表会を行います．
* 日時：2019年7月1日(月) 16:50-，7月2日(火) 16:50-
* 場所：情報工学系会議室（大岡山西8号館E棟10階）
* [プログラム](https://github.com/itspsdl/Demo2019)

当日は，各自7分程度で製作物について以下の内容のプレゼンテーションを行っていただきます．
* 概要：何をするアプリケーションか，どう便利なのか等
* 技術：用いているテクノロジ，実装上の工夫等
* デモ：実際に動作させてみてアピール

## 講義資料

スライド等の資料，例題等は全て本GitHubグループ（itspsdl）を通して配布する．
GitおよびGitHubの簡単な使い方については演習中で説明するが，ある程度参考書やサイトで学んでおくことが望ましい．
講義スライドを含む一部のリポジトリは非公開としている．
これらにアクセスするためにはGitHubグループitspsdlのメンバであるGitHubアカウントが必要である．

### 講義スライド

講義スライドのコピーを入手するには以下のように`git clone`コマンドを使う．

    git clone https://github.com/itspsdl/slides.git

GitHubのログインに二段階認証を用いている場合は，個別パスワードを生成するか，ssh経由でcloneを行う．
この場合，`git clone`コマンドの引数は以下のようになる．

    git clone git@github.com:itspsdl/slides.git

以上でカレントディレクトリに`slides`というサブディレクトリが作成される．
ディレクトリ名を自分で指定したい場合は，例えば以下のようにする．

    git clone https://github.com/itspsdl/slides.git sdl_slides

`git clone`コマンドの後でディレクトリ名を変えたり，別の場所に移動してもよい．

新しいスライドが付け加えられたときやスライドに修正があったときの更新は，以下のように`git pull`を実行する．

    cd /path/to/slides
    git pull

## 関連・参考サイト

* 本演習のGithubアカウント: [https://github.com/itspsdl/](https://github.com/itspsdl/)
* IT特別教育プログラム(ITSP): [http://www.itpro.titech.ac.jp/](http://www.itpro.titech.ac.jp/)
* Android Developers: [https://developer.android.com/](https://developer.android.com/)
* Android Open Source Project: [https://source.android.com/](https://source.android.com/)
* Pro Git: [https://git-scm.com/book/ja/v2/](https://git-scm.com/book/ja/v2/)
* Androidアプリのセキュア設計・セキュアコーディングガイド: [https://www.jssec.org/report/securecoding.html](https://www.jssec.org/report/securecoding.html)
