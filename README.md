# Tech10_PHP4

# ①課題番号-プロダクト名

VideoCentral(AmazonPrimeビデオのCMS)用Availsシート管理DB ログイン機能付き
- 業務で使う用
- AmazonPrimeビデオで提供する作品のライセンス情報を管理するDB
- 作品ごとに登録された最新のライセンスを参照できる
- ↑にログイン機能を追加

## ③DEMO

https://docomo-tech-tkn.sakura.ne.jp/10_PHP4/login.php

## ④作ったアプリケーション用のIDまたはPasswordがある場合

- ID：test1
- PW：test1
- 
- 入力サンプルファイルで動作確認可能です
  - ※キー：AQ列のALID
  - 新規登録：DBにALIDが存在しない & G列EntryType＝Full Extract
  - 更新　　：DBにALIDが存在する & G列EntryType＝Full Extract
  - 削除　　：DBにALIDが存在する & G列EntryType＝Full Delete
  
## ⑤工夫した点・こだわった点

- ログインユーザ名を画面に表示させたところ
 
## ⑥難しかった点・次回トライしたいこと(又は機能)

- ユーザ権限ごとにできる作業とできない作業を区別したかった
