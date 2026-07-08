# Nsight WBS Dashboard

社内プロジェクトWBSの横断ダッシュボード（静的サイト）。

- `index.html` — パスワードゲート付きUI。WebCrypto(PBKDF2-SHA256 200k + AES-256-GCM)でブラウザ内復号
- `data.enc.json` — 暗号化済みプロジェクトデータ（EC2の `wbs_publish.py` が自動更新）

平文データはリポジトリに含まれません。
