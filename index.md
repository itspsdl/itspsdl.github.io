# ソフトウェア開発演習 (IT特別教育プログラム科目)

## お知らせ
* スライドは [http://github.com/itspsdl/slides](http://github.com/itspsdl/slides) で配布します．これはプライベートリポジトリなのでorganizationに参加していないとアクセスできません．(4/12)
* 演習中はインターネット接続が必要になります．開発用のラップトップPCで学内無線LAN接続サービスを利用できるように設定しておいてください．(4/10)
* 教材(Androidタブレット)貸与時に渡した資料にしたがって初期設定を済ませておいてください．(4/10)
* 初回は4月13日(金) 5-8限にW371講義室で行います．(4/2)

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
* 本演習のGithubアカウント: [http://github.com/itspsdl/](http://github.com/itspsdl/)
* IT特別教育プログラム(ITSP): [http://www.itpro.titech.ac.jp/](http://www.itpro.titech.ac.jp/)
* Android Developers: [http://developer.android.com/](http://developer.android.com/)
* Android Open Source Project: [https://source.android.com/](https://source.android.com/)
* Pro Git: [http://git-scm.com/book/ja/v2/](http://git-scm.com/book/ja/v2/)
