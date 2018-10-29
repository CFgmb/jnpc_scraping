# JNPC 2018-11-10

2018年11月10日の勉強会資料置き場です。右上の｢Clone or download｣から｢Download ZIP｣を選んで下さい。今回はまずインストールマニュアルです。事前勉強用の素材は、後日改めてアップします。

---

### 事前準備について
前回(10月)に参加された方は「OpenRefine」のみ新規インストールが必要です。最下部のリンク集とマニュアルを参照してください。初参加の方は「R、Rstudioについて」以下をご覧ください。

当日は「Excel」など表計算ソフトも使用します。Excelでなくて「Open Office」でも大丈夫ですが、汎用性を考えてExcelで講義します。「Open Office」の場合は画面表示や操作法は異なります。

また「R」「RStudio」は前回インストールして多少使えたのであれば、そのままで問題ありません。

そして１、２回目の講座でも紹介した「Googleスプレッドシート」も積極的に活用します。初参加の方や、使えるかどうか分からない、という方は、下記のリンクで試してみて下さい。新しいスプレッドシートを作れるようならＯＫです。

#### ◆Googleスプレッドシート

使えるかどうか、以下のリンクで確認を  
[sheets.google.com](https://sheets.google.com)

使えない場合のみ、こちらの手順で設定を  
https://support.google.com/docs/answer/6000292

#### ◆XPath Helper
ブラウザはChrome利用をお勧めします。さらに拡張機能の「XPath Helper」をぜひ追加してください。下記リンクをクリックすれば、インストールできます。
https://chrome.google.com/webstore/detail/xpath-helper/hgimnogjllphhhkhlmebbmlgjoejdpjl


---

### OpenRefineについて
表記ゆれなど汚いデータを「洗浄」するためのソフトです。ブラウザで操作を行います。現在の最新版は3.0です。過去の勉強会でインストールした経験がある方は、バージョンをご確認ください。もし古いバージョンの場合は、最新版を再度ダウンロードしてください。

#### ◆インストール
マニュアルをご覧ください。Windows用とMac用に分かれています。ダウンロードには環境によっては5分ほどかかります。
http://openrefine.org/download.html

---

### R、Rstudioについて

#### ◆インストール

RとRStudioのインストールについては、川上さんと私が昨年作成したPDFをご覧下さい。Windows用とMac用に分かれています。Windows用は10ページまで、今回はMeCabは不要です。
また、こちらのサイトも参考になります。  
https://qiita.com/daifuku_mochi2/items/ad0b398e6affd0688c97

「R_script」フォルダにRのスクリプト一式が入っています。データはExcel用と同じdataフォルダから読み込みます。初めてRStudioを起動したときのみ、以下の手順で、このフォルダ用の初期設定を走らせて下さい。すでにRをお使いの方の基本環境には悪さをせずに、このフォルダ内に限って、挙動を揃えます。

1. 「R_script.Rproj」ファイルをダブルクリックして下さい。プロジェクトが設定されます。コードやデータを読み込むときの「現在地」になります
1. 「RStuidio」の右上角に、このプロジェクト名が表示されていればOKです。コードを実行したときに、データの読み込みに失敗するようなら、ここを見て確認して下さい
1. 最初の１度だけ、「make_dot_RProfile_in_WD.R」ファイルを実行して下さい。RStudioの左上、３番目のボタンでファイル選択画面が開くので、そこで選んで下さい。開いたら、真ん中上（左上のエディターペインの右上あたり）の「Source」ボタンを押す
1. Rをいったん終了し、再起動して下さい
1. 「preparation.R」ファイルを開いて実行して下さい

２回目以降は、RStudioのアイコンをクリックするだけで大丈夫です。「R_script.Rproj」ファイルのダブルクリックでも、RStudioが立ち上がります。  
先ほどの「make_dot_RProfile_in_WD.R」や「preparation.R」がまだ開いていたら、閉じてしまって構いません。  
「make_dot_Profile_in_WD.R」は、２回目以降は実行は不要です。  

---

#### ◆統計処理用のプログラム言語「R」

ダウンロードはこちらから。  
https://cran.r-project.org/

Rのインストールが済んでから、次の「RStudio」に進んで下さい。

#### ◆Rを使いやすくする必須ソフト「RStsudio」

ダウンロードはこちら。公式ページの「Dowload」をクリックすると製品一覧が表示されます。「RStudio Desktop」とサーバー版があるので、「無料（FREE）」のデスクトップ版を選んで下さい。  
https://www.rstudio.com/products/rstudio/download/#download

#### ◆R + RStsudioのクラウド版

インストールが制限されている方のみこちらを。誰でも使えますが、アカウントを作る必要があります。  
https://rstudio.cloud

