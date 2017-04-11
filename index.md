# ソフトウェア開発演習 (IT特別教育プログラム科目)

## お知らせ
* 個人プロジェクト制作物発表会のプログラムを掲載しました．
  - https://github.com/itspsdl/Demo2016
* 個人プロジェクトの制作物のタイトルと概要(100字程度)を6/30までにメールで送ってください．
* 個人プロジェクト発表会を7/14(木), 7/15(金) 16:50-18:20 (9-10限)に行います．
* Android Studio 2.1.1がリリースされています．重要なセキュリティ上の修正を含んでいるので，早急にアップデートすることをおすすめします．
  - https://plus.google.com/103342515830390186255/posts/g6PVpuVxXMP
  - http://tools.android.com/download/studio/builds/2-1-1
* Android OS 6.0.1のセキュリティパッチが出ています．セキュリティパッチレベルが5月1日になるようアップデートを行っておいてください．
* Javaのアップデート（JDK 8 Update 91/92）がリリースされています．重要なセキュリティアップデートを含むのでインストールしておいてください．
  - http://www.oracle.com/technetwork/java/javase/downloads/index-jsp-138363.html
* Android Studio 2.1の正式版がリリースされました．基本的にはAndroid N（Android OSの次期メジャーバージョン）のサポート強化版ですが，いくつかマイナーなバグも取れているようなのでアップデートをお勧めします．
  - リリースノート: http://developer.android.com/intl/ja/tools/revisions/studio.html
  - ダウンロード: http://developer.android.com/intl/ja/sdk/index.html
  - Mac OS Xでは，IDEがApple提供のJRE6で実行されていないとアップデートに失敗することがあるようです．具体的にはアップデートを実行しても旧版のままになります（エラー等も出ません）．この場合，JRE6をインストールしてIDEをJRE6で実行するか，上のリンク先からダウンロードした新版を上書きすれば問題ありません．IDEがどのJREで実行されているかは，About Android Studioで表示されるスプラッシュウィンドウで確認できます．
* Android OS 6.0.1のセキュリティパッチが出ています．セキュリティパッチレベルが4月2日になるようアップデートを行っておいてください．
* 4月29日(金)は祝日（昭和の日）ですが講義は行います．
  - 参考: http://www.titech.ac.jp/enrolled/life/schedules/2016.html
* 本演習の講義室はW371です．本サイトにW933と書かれていましたがそれは間違いです．大変申し訳ありませんでした．
* 演習中はインターネット接続が必要になります．開発用のラップトップPCで学内無線LAN接続サービスを利用できるように設定しておいてください．
* 教材(Nexus)貸与時に渡した資料にしたがってNexusの初期設定を済ませておいてください．
* 初回は4月15日(金) 5-8限にW371講義室で行います．

## 担当
* 渡部卓雄 (情報理工学院・情報工学系)

## 講義時間・講義室
* 金曜日 5-8限 (13:20-16:35)
* W371講義室 

## 講義の概要とねらい
* 本演習では，モバイルアプリケーションの設計，開発，デバッグ，デプロイメントについて学ぶ．具体的には，モバイルUIフレームワーク，ネットワーキング，位置情報，センサ，グラフィックスおよびセキュリティ等のトピックを扱う．
* 演習を通して，モバイルアプリケーション開発に関する知識・技術のみならず，ソフトウェア開発に必要なツールやグッドプラクティスについて身につけることを目標とする．

## 到達目標
* Androidアプリケーションの設計，実装，デバッグ，デプロイメントができるようになること

## 関連科目・履修条件等
* システム開発プロジェクト基礎第一・第二
* システム開発プロジェクト応用第一・第二
* チーム開発集中演習

IT特別教育プログラム科目の学生を対象とする．
同プログラム以外の学生も履修は可能であるが，その場合は貸与する教材（Androidデバイス）が異なる可能性がある．．

## 成績
* 演習課題
* 個人プロジェクト

## 個人プロジェクト発表会
* 日時：7月14日(木) 16:50-18:20，7月15日(金) 16:50-18:20
* 場所：W8E-10F専攻会議室（変更するかも知れません）
* 内容：各自6分程度で，製作物について以下のような内容のショートプレゼンテーションを行う
  - 概要：何をするアプリケーションか，どう便利なのか等
  - 技術：用いているテクノロジ，実装上の工夫等
  - デモ：実際に動作させる
* 概要：6月30日までに，制作物のタイトルと概要(100字程度)をメールで送ってください．
* プログラム・制作物サマリー
  - https://github.com/itspsdl/Demo2016

## 予定
1. 4/15(金)：準備，プログラム開発環境
2. 4/22(金)：Android API概観
3. 4/29(金)：UIフレームワーク
4. 5/6(金)：ネットワーク
5. 5/13(金)：位置情報，センサ
6. 5/20(金)：クラウドの利用
7. 5/27(金)：グラフィクス
8. 6/3(金)：セキュリティ
9. 7/14(木),15(金)：個人プロジェクト発表会

## 講義資料
スライド等の資料，例題等は全て本Githubグループ(itspsdl)を通して配布する．
gitおよびGithubの簡単な使い方については演習中で説明するが，ある程度参考書やサイトで学んでおくことが望ましい．
講義スライドを含む一部のレポジトリは非公開としている．
これらにアクセスするためにはGithubグループitspsdlのメンバであるGithubアカウントが必要である．

### 講義スライド
講義スライドのコピーを入手するには以下のようにgit cloneコマンドを使う．

    git clone https://github.com/itspsdl/slides.git

Githubのログインに二段階認証を用いている場合は，個別パスワードを生成するか，ssh経由でcloneを行う．
この場合cloneコマンドの引数は以下のようになる．

    git clone git@github.com:itspsdl/slides.git

以上でカレントディレクトリにslidesというサブディレクトリが作成される．
ディレクトリ名を自分で指定したい場合は例えば以下のようにする．

    git clone https://github.com/itspsdl/slides.git sdl_slides

cloneコマンドの後でディレクトリ名を変えたり，別の場所に移動してもよい．

新しいスライドが付け加えられたときやスライドに修正があったときの更新は，以下のようにgit pullで行う．

    cd /path/to/slides
    git pull


## 関連・参考サイト
* 本演習のGithubアカウント: http://github.com/itspsdl/
* IT特別教育プログラム(ITSP): http://www.itpro.titech.ac.jp/
* Android Developers: http://developer.android.com/
* Android Open Source Project: https://source.android.com/
* Pro Git: http://git-scm.com/book/ja/v2/