# AceLink Video Assets (public)

AceLinkのInstagram自動投稿（Instagramログイン方式）で使う、`video_url`フェッチ用の公開動画ホスティング専用リポジトリ。

- Instagram APIのInstagramログイン方式は動画バイナリの直接アップロードに対応せず、`video_url`（公開URL）からのフェッチのみ対応する。
- ここに置いた動画のraw URLを `acelink-instagram-poster/data/queue.tsv` の `video_url` 列に指定する。
- 個人情報・秘密情報は置かない。作例・投稿予定の動画のみ。
