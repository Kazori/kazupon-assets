# kazupon-assets

「かずぽん」ブランドのキャラクターイラスト（おたつ・おうま・かずぽん）を格納する公開アセットリポジトリ。

GitHub Pagesで配信し、`https://kazori.github.io/kazupon-assets/images/<ファイル名>` の形で
`<img src>`から直接参照できる。systeme.io等の外部サービスへの手動アップロード・URL取得の
手間を避け、新しいポーズを追加する際はこのリポジトリへのcommit・pushだけで完結させる目的で作成。

## 位置づけ

- 各プロジェクト（`Systeme_Kazu-pon`・`Posts_Kazu-pon`等）から共通で参照する、ブランド単位の素材置き場。
- 個別プロジェクトのビジネスロジック・非公開情報は含まない（画像ファイルのみ）。
- 2026-08時点で`Systeme_Kazu-pon`のsysteme.io側に既にアップロード済みの画像（`order-v2.html`等、
  確定済みページに埋め込まれているCloudFront URL）はこのリポジトリへの移行対象外。今後の新規追加分から
  このリポジトリを使う運用。

## 使い方

```html
<img src="https://kazori.github.io/kazupon-assets/images/otatsu-note.png" alt="おたつ">
```

新しいポーズを追加する場合は`images/`にPNGを追加してcommit・pushするだけでよい
（GitHub Pagesは自動で反映される）。
