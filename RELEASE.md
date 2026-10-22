v0.1.7では、**ネットワーク共有の走査を高速化**しました。

- ネットワーク共有のファイル情報を効率よく取得し、スキャンの待ち時間を短縮します。
- 共有先が対応しない問い合わせを繰り返さず、アクセス拒否や一時的な失敗は別に扱います。

### 計測結果と対応範囲

同じPC上のWindows SMB共有で1,131項目を各5回計測した中央値は、v0.1.6の712.8 msから567.9 msへ約20%短縮しました。実NASの改善率は未測定です。

速度は共有先・回線・ファイル構成に依存します。実NAS、Samba固有の挙動、DFS・WebDAV・NFS、別ユーザー認証は未確認です。

**必要環境:** Windows 11 x64 / .NET 10 Desktop Runtime x64（非同梱）。日本語UI・オフライン計測。

- `DiskHeatMap-v0.1.7-win-x64.zip`：単一EXEと日本語の使い方.html。
- `DiskHeatMap-v0.1.7-win-x64.zip.sha256.txt`：上記ZIPだけのSHA-256。

更新時はアプリを終了し、既存の `DiskHeatMap.settings.json` を残してEXEと使い方を置き換えてください。管理者チェックは起動ごとにONへ戻ります。ネットワーク先は通常権限で走査します。

[使い方HTMLを単体で保存](https://github.com/mezon-web/DiskHeatMap-Releases/raw/refs/heads/main/manual.html)して、オフラインでも読めます。

GitHubが自動生成する**「Source code」は公開資料リポジトリの内容**で、アプリ本体やアプリケーションのソースコードではありません。アプリは `win-x64.zip` をダウンロードしてください。
