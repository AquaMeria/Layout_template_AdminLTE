# Template Layout AdminLTE


## 本レイアウトについて  
AdminLTEをベースにしたスターターレイアウト。  

![スクリーンショット](http://aquanation.heteml.jp/demo/layout/AdminLTE.png "AdminLTE")

 ```html
 構成要素
　├ [ヘッダー] - 設定などの固定メニュー
　├ [サイドメニュー] - 左固定メニュー(ハンバーガーメニュー)  
　└ [コンテンツ] - コンテンツエリア   
　※( )内はSP時  
```


## 対応ブラウザ  
|| **Windows** | **Mac** | **スマートフォン・タブレット** |
|:----- |:-----:|:-----:|:-----:|
|InternetExplorer 11|○|×|×|
|Safari 最新版|×|○|○|
|GoogleChrome 最新版|○|○|○|
|Firefox 最新版|○|○|×|
|iOS 10~|×|×|○|
|AndroidOS 5.0~|×|×|○| 

 
 
## ディレクトリ構造  
 
```html 
 ルート  
　├ [css] … サイトで使われるCSSファイルを全て格納する    
　│　├ common.css … 共通パーツで使用するCSS(ヘッダー・フッター)  
　│　├ module.css … 全ページで共通で使用するパーツCSS(無記入)   
　│　└ pagename.css …  各ページでのみ使用するCSS(無記入)  
　│   
　├ [js] … サイトで使われるJavaScriptを全て格納する    
　│　├ common.js … 共通パーツで使用するJS(ページスクロール)  
　│　├ module.js … 全ページで共通で使用するパーツJS(無記入)   
　│　└ pagename.js …  各ページでのみ使用するJS(無記入)  
　│ 
　├ [framework] … サイトで使用したフレームワーク(bootstrap)のファイルを格納 
　│  ├ bootstrap.min.css … Bootstrapの標準CSS    
　│  └ bootstrap.min.js … Bootstrapの標準JS
　│
　├ [template] … サイトで使用したテンプレート(AdminLTE)のファイルを格納 
　│  ├ AdminLTE.min.css … AdminLTEのCSS    
　│  ├ app.min.js … AdminLTEのJS
　│  └ [skins] … カラーを変更するCSSファイル一覧
　│ 
　├ [plugin] … サイトで使われるプラグインを全て格納する   
　│　└ [directory] …  各プラグイン  
　│     
　└ index.html  
```