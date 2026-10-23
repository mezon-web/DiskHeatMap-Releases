DiskHeatMap v0.1.7では、ネットワーク共有の走査を高速化しました。速度は共有先・回線・ファイル構成によって変わります。実NAS、Samba固有の挙動、DFS・WebDAV・NFS、別ユーザー認証は未確認です。

**必要環境:** Windows 11 x64 / .NET 10 Desktop Runtime x64（非同梱）。日本語UI・オフライン計測。

- `DiskHeatMap-v0.1.7.zip`：展開すると `DiskHeatMap-v0.1.7` フォルダができます。単一EXEと日本語の使い方.htmlを収録しています。
- `DiskHeatMap-v0.1.7.zip.sha256.txt`：上記ZIPだけのSHA-256。

更新時はアプリを終了し、既存の `DiskHeatMap.settings.json` を残してEXEと使い方を置き換えてください。管理者チェックは起動ごとにONへ戻ります。ネットワーク先は通常権限で走査します。

[使い方HTMLを単体で保存](https://github.com/mezon-web/DiskHeatMap-Releases/raw/refs/heads/main/manual.html)して、オフラインでも読めます。

GitHubが自動生成する**「Source code」は公開資料リポジトリの内容**で、アプリ本体やアプリケーションのソースコードではありません。アプリは `DiskHeatMap-v0.1.7.zip` をダウンロードしてください。
