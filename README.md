Narou.rb ― 「小説家になろう」「小説を読もう！」ダウンローダ＆縦書用整形スクリプト
============================================================

概要 - Summary
--------------
このアプリは[小説家になろう](http://syosetu.com/)、[小説を読もう！](http://yomou.syosetu.com/)で公開されている小説の管理、
及び電子書籍データへの変換を支援します。縦書き用に特化されており、
横書き用に特化されたWEB小説を違和感なく縦書きで読むことが出来るようになります。
また、若干の校正機能もありますので、小説としての一般的な整形ルールに矯正します。（例：感嘆符のあとにはスペースが必ずくる）

[ノクターンノベルズ](http://noc.syosetu.com/)及び[ムーンライトノベルズ](http://mnlt.syosetu.com/)にも対応しています。

全てコンソールで操作するCUIアプリケーションです。

主な機能は小説家になろうの小説のダウンロード、更新管理、テキスト整形、AozoraEpub3・kindlegen連携によるEPUB/MOBI出力です。

詳細な説明やインストール方法は **[Narou.rb 説明書](https://github.com/whiteleaf7/narou/wiki)** を御覧ください。

![ScreenCapture](https://raw.github.com/wiki/whiteleaf7/narou/images/narou_cap.gif)

更新履歴 - ChangeLog
--------------------
2013/06/12 : **1.2.7**
* 追加機能もしくは仕様変更
	- 小説更新時及び `list` コマンドで新着話数があるかどうかを目視出来るようにした
		+ 更新時はタイトル横に (新着) 表示
		+ list コマンドでは当日に新着のあった小説の日付が紫になる
			- 新着表示が優先で、新着がなくて更新だけの場合は緑になる

2013/05/17 : **1.2.6**
* Bug Fix
	- `convert` コマンドで直接テキストファイルを変換時に電子書籍デバイスへ送信できなかった不具合を修正
* 追加機能もしくは仕様変更
	- `list` コマンドでその日に更新された小説の日付に色をつけてわかりやすくした
	- 電子書籍デバイスへの自動送信で Kindle Fire/HD に対応（動作未確認）

2013/05/08 : **1.2.5.1**
* fix: 新規DL時にエラーが出る可能性あったので修正

2013/05/07 : **1.2.5**
* Bug Fix
	- 連続する文頭全角空白をすべてルビ対象外に 
	- Mac OS X での動作状況を改善
* 追加機能もしくは仕様変更
	- 連続空行の改ページ化設定をデフォルトでオフに変更

----

「小説家になろう」は株式会社ヒナプロジェクトの登録商標です
