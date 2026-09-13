# rabbit hop climber

うさぎを操作して足場を渡りながら月を目指すレースゲームです。

## デプロイ方法(Vercel)
1. このリポジトリをGitHubにpush
2. https://vercel.com で「Add New Project」からインポート
3. Framework Preset は "Other" のままでOK。設定不要でそのまま Deploy

## Google Analytics設定
`config.js` の `gaMeasurementId` を、あなたのGA4測定IDに書き換えてください。
**index.htmlを更新しても、config.jsは書き換えなくてOKです。**

計測イベント: race_start(レース開始) / race_finish(ゴール) / race_retire(リタイア)

## ファイル構成
- index.html … ゲーム本体(単一ファイル)
- config.js … GA測定IDなどの設定(更新のたびに書き換え不要)
- manifest.json / icon-512.png / icon-180.png … ホーム画面に追加した時のアプリアイコン用
