# LUCKY DARUMA ASAKUSA SEOメモ

## 今回入れた対策

- 日本語・英語それぞれの検索タイトルと説明文
- `canonical`、`hreflang`、`robots`、OGP、X向け共有タグ
- 店舗、所在地、料金、所要時間、英語対応、体験内容のJSON-LD構造化データ
- URLの `?lang=en` / `?lang=ja` と言語切替の連動
- 画像の幅・高さ、遅延読込、説明文を設定して表示安定性を改善
- Google Mapsへの導線と位置情報を構造化データへ反映

## 外国人旅行者向けの主要検索意図

検索結果に繰り返し現れる表現を、読みやすい文章の中へ自然に反映しています。

- things to do in Asakusa
- Japanese cultural experience in Tokyo / Asakusa
- daruma painting experience / daruma painting workshop
- Japanese calligraphy workshop in Asakusa
- calligraphy workshop in English
- small-group workshop
- 60-minute cultural experience
- make your own daruma / take-home souvenir
- family-friendly / beginner-friendly activity

## 公開後に必ず行うこと

1. GitHub Pagesの本番URLが決まったら、`index.html` の `canonical` と `hreflang` を絶対URLに変更します。
2. Google Search Consoleへ本番URLを登録し、URL検査からインデックス登録を依頼します。
3. GoogleビジネスプロフィールのサイトURLを本番URLへ合わせます。
4. Search Consoleで実際に表示された検索語を月1回確認し、タイトルや本文を調整します。
5. 予約サービスのURLが決まったら、現在ページ内に留まる予約ボタンへ正式URLを設定します。

## 調査で確認した代表的な検索結果

- Google検索では「Asakusa daruma painting experience」「Japanese calligraphy workshop in Asakusa」「English」「small-group」「beginners」「take home」などの表現が体験予約ページで繰り返し使われています。
- Google Search Centralは、多言語ページに別URLと `hreflang` を推奨しています。今回は1ファイルで運用できるよう `?lang=en` と `?lang=ja` を付けています。
- 店舗情報はGoogle Mapsの登録地点と一致する緯度経度を使用しています。

参考:

- https://developers.google.com/search/docs/specialty/international/managing-multi-regional-sites
- https://developers.google.com/search/docs/appearance/structured-data/local-business
- https://developers.google.com/search/docs/appearance/title-link

## 補足

SEOは公開しただけで順位が保証されるものではありません。Googleビジネスプロフィール、予約サイト、SNS、旅行者の口コミで店名・住所・体験名の表記を揃えることが重要です。
