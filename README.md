# SlickExcel 

### 機能・改良点
* Excelと同様のフィルタリング、ソート（昇順・降順）
* フィルタリングしたデータのみを抽出、外部出力(CSV)
* フィルターメニューにて各値のユニークカウント表示
* Drag and Dropで列並びの編集。編集した状態でのCSV出力
* Copy and Paste (slickexcel上で任意をコピー → ExcelやTextなど外部アプリケーションにペースト(tab区切り))
* データ表示時、フィルター抽出時での件数カウント
* 各ライブラリの連携調整
* データ処理関連の調整

### 概要
* MIT Licenseのオープンソース・ソフトウェア「SlickGrid」の拡張と改良。
* Webベースで動作するExcelライクな表計算（グリッド）表示ライブラリ。
* 大量のデータを高速に表示処理することが可能（50万行程度のデータなど）

### Sample File
http://okashira.github.io/slickexcel/slickexcel_example01.html

### Extended code
* "Paste from Excel to SlickGrid" : (Nereo Labs) http://labs.nereo.com/slick.html
* "slickgrid-spreadsheet-plugins" : https://github.com/danny-sg/slickgrid-spreadsheet-plugins
* "SlickGrid-Export-CSV" : https://github.com/BethelBoy/SlickGrid-Export-CSV

### ToDo (ヒマだったらやる）
* GoogleChart連携機能
* 列ごとのフィルター・カウント機能のON/OFF
* Sample Fileの作成


OKASHIRA (individual.lab)

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
