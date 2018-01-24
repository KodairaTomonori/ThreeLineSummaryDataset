# 3行要約データセット

## 概要
LivedoorNews(http://news.livedoor.com/)からクロールしてデータセットの構築を行います．
`data/`以下にあるcsvファイルにサイトの情報が記述されています．  
各列の詳細は以下，

1列目は記事の公開年  
2列目は記事の公開月  
3列目は記事のカテゴリ  
4列目は記事のID  
4列目はタイプラベル（0が並列，1が直列）  

記事IDからサイトのURLが作成できます．
3行要約が載っているURLは  
```http://news.livedoor.com/topics/detail/xxxxxxxx/```  
記事が載っているURLは  
```http://news.livedoor.com/article/detail/xxxxxxxx/```  
`xxxxxxxx`にIDを入れてください．
　
