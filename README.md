# LIKE A PACHISLOT Overlay — 更新情報

Twitch配信用パチスロ風演出オーバーレイ「LIKE A PACHISLOT Overlay」の
**更新情報の配信用リポジトリ**です。ソースコードや本体の配布はここにはありません。

- 本体の入手・アップデート: [BOOTH商品ページ](https://chinatsu-systems.booth.pm/items/8634744)
- アプリは起動時にこのリポジトリの [`latest.json`](latest.json) を確認し、
  新しいバージョンが公開されているときだけ設定画面にお知らせを表示します

## latest.json の形式(開発メモ)

```json
{
  "version": "0.1.3",
  "url": "案内先URL(BOOTHの商品ページなど・https必須)",
  "notes": "ひとことメモ(設定画面のバナーに表示・200文字まで)"
}
```

新しいバージョンを公開するときは、配布物のアップロード後に
`version` / `notes` を更新してプッシュするだけで、全ユーザーの
設定画面に通知が届きます(反映は各ユーザーの次回起動時または24時間ごとの確認時)。
