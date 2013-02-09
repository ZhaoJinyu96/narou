Narou.rb ― 小説家になろうダウンローダ＆縦書用整形スクリプト
============

説明
------------

小説家になろうから小説をダウンロードして、縦書で読みやすいようにテキストを整形し、AozoraEPUB3を使ってEPUB化します。
小説の更新管理もできます。

超絶開発中なため、触れるな危険。

必須ツール
------------
* Ruby 1.9.3以上
* AozoraEpub3 1.1.0系
* Java 6以降（AozoraEpub3で必須）
* kindlegen（できるだけ最新版）

使い方
------------
```
 Usage: narou <command> [arguments...] [options...]

 コマンドの簡単な説明:
   download     指定した小説をダウンロードします。
   update       指定した小説を更新します。
                指定がない場合、すべての小説が対象になります。
   list         現在管理している小説の一覧を表示します。
   convert      小説を整形します。管理小説以外にテキストファイルも変換可能
   help         このヘルプを表示します。
   version      バージョンを表示します。

  各コマンドの詳細は narou <command> --help を参照してください。
  各コマンドは頭文字の一文字のみでも指定できます。
  (e.g. 'narou d n4259s')
```