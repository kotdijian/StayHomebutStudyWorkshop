<!-- R/ RStudioインストールガイド（日本語）-->
<!-- Install guide for R/ RStudio (Japanese)-->
## R/ RStudioをインストールしよう、ワークショップ参加の準備を使用
**目次**    
[1. Rをインストールしよう](#1)    
[2. RStudioをインストールしよう](#2)    
[3. ワークショップ資料をダウンロードしよう](#3)
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
### **3. ワークショップ資料をダウンロードしよう**
ワークショップの資料（Rのコードと解説）は、**RMarkdown(.Rmd)** という形式で提供されます。
1. Rマークダウンて何だろう？
* Rは統計解析向けのプログラミング言語 > 文書も作成できたら便利じゃない？
* >マークダウン形式の文書を扱えるようにしよう (ちなみにこのページもマークダウン形式で書かれています）
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
![Rmd05](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/Rmd05.png)    
![Rmd06](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/Rmd06.png)    
![Rmd07](https://github.com/kotdijian/StayHomebutStudyWorkshop/blob/master/Rinstlation/Rmd07.png)    
    * gmm-markdown.Rmdというタブが開き、資料の内容が表示されます
    * **初めて開いた時にはPackageの不足についての警告が上部に表示されますが、ワークショップ中にインストールの手順が示されます。気にしないでください**    

3. ワークショップ資料を印刷する・文書として閲覧する
* GitHubリポジトリのworkshop02フォルダ内には、.Rmdと同じ内容のHTML, PDF文書も公開されています
* これらは、インターネットブラウザ、PDFリーダーなどで表示し、印刷することができます
* Rマークダウンは文章と実行可能なコードを併記することを主眼としたものです。人間が見て読みやすいものではありません
* 必要に応じてHTML、PDFもご利用ください

***
***
