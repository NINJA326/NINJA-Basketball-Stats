NINJA AIRS Basketball Stats V21 正式版

【構成】
index.html                 GitHub Pages用アプリ本体
manifest.json              PWA設定
sw.js                      オフラインキャッシュ
icons/                     アプリアイコン
google_apps_script_code.js Googleスプレッドシート連携コード
SETUP.txt                  初期設定手順

データの正式保存先はGoogleスプレッドシートです。
通信できない場合のみ、端末内に一時保存し、通信回復後に再同期します。


【V21改善】
・同日・同一対戦相手の複数試合でも、試合ごとのシート名が重複しません。
・途中保存を繰り返しても、対戦相手の対戦数が重複加算されません。
・アップロードされたアイコンをそのままPWAアイコンに使用しています。
