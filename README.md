# DiskGuard & DriveMover - Auto-Update Repository

このリポジトリは **DiskGuard & DriveMover**（Windows スタンドアロン版）の**自動アップデート配信専用リポジトリ**です。

- アプリケーション本体およびセットアップインストーラー（`DiskGuard_Setup.exe`）はセキュリティおよび配布管理のため本リポジトリでは公開しておりません。
- インストール済みのクライアントアプリが起動時および定期チェック時に [`updates/version.json`](updates/version.json) と [`updates/update_patch.zip`](updates/update_patch.zip) を参照し、SHA-256 整合性検証を行った上で自動アップデートを適用します。
