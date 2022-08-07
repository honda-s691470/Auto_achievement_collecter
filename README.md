# Auto_achievement_collecter

The objectives of this program are as follows  
1. to extract articles published in pubmed for each research group   
2. to determine  which diseases the extracted papers are related to   
3. to output research achievements by disease  

このプログラムの目的は以下です。  
１．研究班毎のpubmedに掲載された論文を抽出する  
２．抽出した論文がどの病気の論文か判定する  
３．疾患別研究業績を出力する  


![overview](https://github.com/honda-s691470/Auto_achievement_collecter/blob/main/img/outline.png)

# preparation
This program uses python selenium. For this reason, you need to save a chromedriver in the driver folder that matches the version of google chrome you are using.  
このプログラムはpython seleniumを使用しています。このため、使用しているgoogle chromeのバージョンとマッチしたchromedriverをdriverフォルダに保存する必要があります。

How to check chorme version
chormeのバージョン確認方法
![version](https://github.com/honda-s691470/Auto_achievement_collecter/blob/main/img/chrom_driver_version.png?raw=true)

Once you have verified the version, go to the ChromeDriver (https://chromedriver.chromium.org/downloads) site, where you will find the Chrome version and download link under Current Releases.  
バージョンが確認できたらChromeDriver(https://chromedriver.chromium.org/downloads)サイトに移動します。Current ReleasesにChromeのバージョンとダウンロードリンクを確認することができます。
