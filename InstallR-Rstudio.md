<!-- R/ RStudioインストールガイド（日本語）-->
<!-- Install guide for R/ RStudio (Japanese)-->
## R/ RStudioをインストールしよう、ワークショップ参加の準備をしよう
**目次**    
0. とくにWindowsユーザーのための注意事項    
[1. Rをインストールしよう](#1)    
[2. RStudioをインストールしよう](#2)    
[3. RStudioでRを使ってみよう](#3)    
[4. ワークショップ資料をダウンロードしよう](#4)    
* なおRの使い方についてはこちらも参考になります：石井淳平「考古学のためのデータビジュアライゼーション」[『デジタル技術による文化財情報の記録と利活用2』奈良文化財研究所研究報告24](https://sitereports.nabunken.go.jp/ja/69974)    

***
### **0. とくにWindowsユーザーのための注意事項**
* **【重要】**WindowsでRおよびRStudioをインストールし、使用する場合、インストール先やデータの保存先となるフォルダにマルチバイト文字（日本語等の全角文字）を使用しないこと   
    **RおよびRStudioが正常に動作せず、データの保存等ができなくなる場合があります**
    * 例1）Windowsにログインするアカウント名にひらがな・カタカナ・漢字を使っている    
    * 例2) プログラムのインストール先、またはデータの保存先にひらがな・カタカナ・漢字を含むフォルダ名を使用している    
    ＞ 対処方法：アカウント名、フォルダ名はすべて半角英数字のみとしてください。アカウント名の変更が困難な場合は、別途半角英数字のみのアカウントをワークショップ用に作成してください    
    **今後もRやその他のオープンソースソフトウェアを使用する予定のある方は、この際に変更しておくことを推奨します**
    **ワークショップのデータや成果を保存する際にも、ファイル名は半角英数字のみを使用しましょう**

* **【重要】**RおよびRStudioのインストールと実行は、必ず**管理者権限**のアカウントで行なってください
    ![Rmd07](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/RStudio07.png)    
    * 例）RStudioの起動時に上掲画像のようなメッセージが出るのは管理者権限がないためです    
    
    ＞ 【参考】[Windows環境で「R」を導入するための絶対確実な方法](https://r-statistiker.hatenadiary.org/entry/20141112/1415799972)    

***
###### 1
### **1. Rをインストールしよう**
Rは、統計解析向けのプログラミング言語、実行環境です。オープンソースです。無料でインストール・利用できます。[日本語版ウィキペディア](https://ja.wikipedia.org/wiki/R%E8%A8%80%E8%AA%9E)    
** Rを使うメリット**
* さまざまな目的・用途に即したパッケージが開発・公開されているため、プログラミングについて習熟していなくても、多くの統計解析を実行することができます
* きれいなグラフなどを作成するパッケージもあり、分析から図表作成までカバーできます    

1. Rのインストールは[こちら](https://www.r-project.org/)から
![Rinstlation01](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/R01.png)
2. ご使用のOSを選択します
![Rinstlation02](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/R02.png)
3. Windowsの場合、次の画面で「base」を選択します
![Rinstlation03](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/R03.png)    
4.2020/5/5現在、*最新バージョンは4.0.0*です
![Rinstlation04](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/R04.png)
5. Mac-OSの場合、こちらでOSのバージョンなど必要条件を確認してください
![Rinstlation05](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/R05.png)
6. 以下、Windowsの場合について案内します。とくに指定がなければ、デフォルトの設定でインストールを進めます
![Rinstlation06](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/R06.png)
7. Windowsが64bit版ならば、32bit版のインストールは不要です    
![Rinstlation07](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/R07.png)
8. 以降の設定は、すべてデフォルトでOKです

***

###### 2
### **2. RStudioをインストールしよう**
RStudioは、Rの統合開発環境です。オープンソースです。Rのソースコード、コマンドを入力し結果を確認するコンソール、読み込んだパッケージやデータ・実行履歴、実行結果のグラフやコマンドのヘルプなどが表示されるため、コマンドライン・ベースよりも見て分かりやすくRを操作することができます。RStudio社の製品ですが、無料版でも十分な機能を有しています。本ワークショップでは無料版でOKです。   
ただし**メニューは英語のみ**です。    

1. RStudioのインストールは[こちら](https://rstudio.com/products/rstudio/download/)から    
![RSinstlation01](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/RStudio01.png)
2. RStudio Desktopの無料版 **RStudio Desktop Free** を選択します
![RSinstlation02](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/RStudio02.png)
3. 使用しているOS用のインストーラーが表示されるので、ダウンロード、実行します
![RSinstlation03](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/RStudio03.png)
4. もし使用しているOSが表示されない場合は、スクロールして必要なインストーラーをダウンロード、実行します
![RSinstlation04](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/RStudio04.png)

5. R/ RStudioのインストールについては[こちら](https://qiita.com/hujuu/items/ddd66ae8e6f3f989f2c0)もご参照ください    
6. 参考書籍等
* [Rによるやさしい統計学](https://amzn.to/3dgxdkO)／[Kindle版](https://amzn.to/2W60tVG)    
* [はじめてのRStudio](https://amzn.to/3c8pDsa)／[kindle版](https://amzn.to/3c9NIPE)    
* [RユーザのためのRStudio［実践］入門](https://amzn.to/2L42mf6)／[Kindle版](https://amzn.to/2W9zDw5)    
***
###### 3
### **3. RStudioでRを使ってみよう**   
RとRStudioをインストールしたら、インストールが問題なくできているか、設定に問題はないか確認する意味も含めて使ってみましょう。

* RStudioの画面は基本的に以下のような構成になっています。設定によっては表示が異なる場合がありますが、見えていない枠（ペインと呼びます）があったら、メニューバーの「Tool」→「Show ～」で必要なペインを表示しましょう。
![RSinstlation08](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/RStudio08.png)
1. Source（ソース）：コードを書いたり実行したりする場所です。ワークショップの資料もここに表示されます。**必須**    
2. Console（コンソール）：ソースの実行結果が表示されます。起動時にはRのバージョンが表示されています    
    * ここに直接コードを入力して実行させることもできます    
    * **【練習1】** > の後に `1 + 1` と入力してみましょう（結果はすぐに表示されます）     
    * **【練習2】** > の後に `x <- 2` と入力してみましょう。続いて 'x' と入力してみましょう    
    * **【練習3】** 練習2に続いて > の後に `y <- 4` と入力してみましょう    
    * **【練習4】** 練習3に続いて > の後に `x + y` と入力してみましょう。また `x * y`、`x / y`も入力してみましょう    
    * **【練習5】** 練習3に続いて > の後に `sqrt(2)` と入力してみましょう。また `sqrt(x)` と入力してみましょう    
    * ※ `sqrt()` は平方根を計算する関数です。Excelと共通です
    * **【練習6】** 練習3に続いて > の後に `z <- x + y` と入力してみましょう。続いて `mean(z)` と入力してみましょう    
    * ※ `mean()` は平均値を計算する関数です    
3. (1) Environment（環境）：入力したデータなどが表示されます。たとえば練習2～6を実行すると下図のような結果が表示されます    
    ![RSinstlation11](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/RStudio11.png)
    (2) History（履歴）：これまでに実行したコードが表示されます    
4. (1) Files（ファイル）：作業ディレクトリ（フォルダ）内のファイルが表示されます    
    (2) Plots（プロット）：グラフなどの作図結果が表示されます    
    (3) Packages（パッケージ）：読み込み済み、あるいは追加できるパッケージが表示されます    
    (4) Viewer（ビューワー）：プロットには表示されないグラフそのほかが表示されます    

* **設定**    
    * メニューバーの「Tool」→「Global options」から各種設定を変更できます   
    * とりあえず設定しておくべきこと    
        1. 左側「General」→Default working directory：ソースコードなどを保存するフォルダの指定。半角英数字だけ使うこと
        2. 左側「Code」→上側「Saving」→Default coding： **UTF-8** に設定   
* 参考：[R初心者の館（RとRStudioのインストール、初期設定、基本的な記法など）](https://das-kino.hatenablog.com/entry/2019/11/07/125044)
        
   
***
###### 4
### **4. ワークショップ資料をダウンロードしよう**
ワークショップの資料（Rのコードと解説）は、**RMarkdown(.Rmd)** という形式で提供されます。
1. Rマークダウンて何だろう？
* Rは統計解析向けのプログラミング言語 ＞文書も作成できたら便利じゃない？
* ＞マークダウン形式の文書を扱えるようにしよう (ちなみにこのページもマークダウン形式で書かれています）
* Rマークダウンでは、文章とRの実行コードを一緒に扱えます
![Rmd01](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/Rmd01.png)
    * RStudioで表示すると、文章部分と、Rの実行コード部分（コードチャンク）が区別されています
    * コードチャンクは背景がグレー、コードを実行するボタンが表示されます（赤丸）
![Rmd02](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/Rmd02.png)
    * コードを実行すると、結果が表示されます    
![Rmd03](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/Rmd03.png)    
    * Rマークダウン文書全体を、HTML、PDF、.docxなどに書き出すことができます(knit)    
    * **HTML, PDF, .docx** ファイルもリポジトリにあります

1. ワークショップ資料のダウンロード
* 資料は、クリスチャンのGitHubリポジトリからダウンロード可能です
![Rmd04](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/Rmd04.png)
    * 緑色の **"Clone or download"** ボタン→ **Download ZIP** をクリックするとリポジトリ全体を.zip形式でダウンロードできます
    * .zipフォルダを解凍、"workshop02"フォルダ内の"gmm-markdown.Rmd"ファイルをRStudioで開くと準備完了です
    * **【重要】リポジトリ内のgmm-markdown.Rmdをダイレクトに保存(Windowsの場合:右クリック→名前を付けてリンク先を保存)では正しくダウンロードできません**    
    ![Rmd05](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/Rmd05.png)
* GitHubをすでに使い慣れている人は、各自のリポジトリにクローンしてください    

2. ワークショップ資料のRStudioへの読み込み
* RStudioを起動します
* File→Open File→資料を保存したフォルダから、gmm-markdown.Rmdを開きます    
![Rmd05](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/RStudio05.png)    
![Rmd06](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/RStudio06.png)    
    * gmm-markdown.Rmdというタブが開き、資料の内容が表示されます

3. ワークショップ資料の確認
* ソース・ペイン右上の「Run」をクリック→「Run all」を選択すると、資料中のすべてのコードチャンクが実行されます    
    ![Rmd07](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/Rmd06.png)    
* ソースの意味、実行結果はワークショップで詳しく説明します。ここではエラーメッセージが出ずに最後まで実行できるかだけを確認してください
* エラーが出た場合は、エラーメッセージの内容をメモし、またはスクリーンショットで記録し、Slackの「質問」チャンネルまで!!

4. ワークショップ資料を印刷する・文書として閲覧する
* GitHubリポジトリのworkshop02フォルダ内には、.Rmdと同じ内容のHTML, PDF文書も公開されています
* これらは、インターネットブラウザ、PDFリーダーなどで表示し、印刷することができます
* Rマークダウンは文章と実行可能なコードを併記することを主眼としたものです。人間が見て読みやすいものではありません
* 必要に応じてHTML、PDFもご利用ください

***
