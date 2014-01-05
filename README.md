# SlickExcel 
( Extended SlickGrid )

### 機能概要

Webベースで動作する多機能なグリッド、表計算ライブラリです。Webベースで業務系システムを作っていると必ず要望に挙がるのがリッチな表計算（グリッド）表示ライブラリです。こちらは通常の表示。縦横スクロール対応。入力方式の設定や、行を選択してといった機能はExcelにもないので便利ではないでしょうか。また、プラグインによってExcelとコピー&ペーストでデータの授受もできるようになっています。SlickGridはJavaScript製、MIT Licenseのオープンソース・ソフトウェアです。

### 主な改良箇所
* Excelと同様のフィルタリング、ソート（昇順・降順）
* 表示行数カウント表示
* フィルタリングしたデータのみを抽出、外部出力(CSV)
* 列における各値のユニークカウント (拡張中。5000件程度が限度）
* コピペ。Copy and Paste (slickexcel's Cell copy >> other Application(ex:Excel's sheet , simpletext, any Application))
* ベースとなるライブラリの連携調整
* ソート処理の調整(dataview.js)


### Extended code
* "Paste from Excel to SlickGrid" : (Nereo Labs) http://labs.nereo.com/slick.html
* "slickgrid-spreadsheet-plugins" : https://github.com/danny-sg/slickgrid-spreadsheet-plugins
* "SlickGrid-Export-CSV" : https://github.com/BethelBoy/SlickGrid-Export-CSV

### ToDo (ヒマだったらやる）
* ユニーク抽出したものをGoogleChartと連携した表示
* ユニークカウントのON/OFF指定
* Sampleの用意

MTHD (individual.lab)



## About SlickGrid

### SlickGrid is an advanced JavaScript grid/spreadsheet component

Find documentation and examples in [the wiki](https://github.com/mleibman/SlickGrid/wiki).

Some highlights:

* Adaptive virtual scrolling (handle hundreds of thousands of rows with extreme responsiveness)
* Extremely fast rendering speed
* Supports jQuery UI Themes
* Background post-rendering for richer cells
* Configurable & customizable
* Full keyboard navigation
* Column resize/reorder/show/hide
* Column autosizing & force-fit
* Pluggable cell formatters & editors
* Support for editing and creating new rows.
* Grouping, filtering, custom aggregators, and more!
* Advanced detached & multi-field editors with undo/redo support.
* “GlobalEditorLock” to manage concurrent edits in cases where multiple Views on a page can edit the same data.
* Support for [millions of rows](http://stackoverflow.com/a/2569488/1269037)
