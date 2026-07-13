NINJA AIRS Basketball Stats V25 完成版

【構成】
index.html                 GitHub Pages用アプリ本体
manifest.json              PWA設定
sw.js                      オフラインキャッシュ
icons/                     アプリアイコン
google_apps_script_code.js Googleスプレッドシート連携コード

【V25変更内容】
・OR、DR、AST、STL、TO、PFの画面表示を中学生向けの日本語表記に変更。
・2P、3P、FTを各1ボタンに統合。
・シュートボタンは「タップ＝成功」「左フリック＝不成功」。
・選手カードにリアルタイムEFFを表示。
・試合途中、試合終了、保存済み試合のスタッツにEFFと合計リバウンドを追加。
・通算成績に平均EFF、最高EFF、EFF順位を追加。
・Googleスプレッドシートの試合別シートと通算スタッツにもEFFを追加。

【EFF計算式】
得点＋オフェンスR＋ディフェンスR＋アシスト＋スティール
－2P不成功－3P不成功－FT不成功－ターンオーバー

【更新手順】
1. GitHub Pages側のファイルを、このフォルダ内のファイルへ入れ替えます。
2. iconsフォルダもそのままアップロードします。
3. Google Apps Scriptは google_apps_script_code.js の内容へ差し替えます。
4. Apps Scriptを新しいバージョンとして再デプロイします。
5. ウェブアプリURLが変わった場合は、アプリの設定画面で新URLへ更新します。
6. iPadでは一度アプリを閉じ、再度開いてV25を読み込みます。
