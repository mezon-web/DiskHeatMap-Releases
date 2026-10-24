DiskHeatMap v0.2.1では、スキャン中も［空き領域］をON/OFFできるようになりました。

- ヒートマップ・アイシクル・サンバーストの3方式に対応。取得済みの情報で表示を更新し、再スキャンせず切り替えられます。
- 途中更新や素早い連続切替でも、最後に選んだON/OFFと選択項目を保持します。変更した設定は再起動後も復元します。
- 空き枠は、全体容量を取得できるローカルドライブ全体の表示で利用できます。フォルダー・ネットワーク先・全体容量不明の場合は無効表示です。アイシクル／サンバーストの通常ファイルサイズ表示では空き枠を表示しません。

**必要環境:** Windows 11 x64 / .NET 10 Desktop Runtime x64（非同梱）。日本語UI・オフライン計測。

- `DiskHeatMap-v0.2.1.zip`：展開すると `DiskHeatMap-v0.2.1` フォルダーができます。単一EXEと日本語の使い方.htmlを収録。
- `DiskHeatMap-v0.2.1.zip.sha256.txt`：上記ZIPだけのSHA-256。

更新時はアプリを終了し、既存の `DiskHeatMap.settings.json` を残してEXEと使い方を置き換えてください。

[使い方HTMLを単体で保存](https://github.com/mezon-web/DiskHeatMap-Releases/raw/refs/heads/main/manual.html)して、オフラインでも読めます。

GitHubが自動生成する**「Source code」は公開資料リポジトリの内容**で、アプリ本体やアプリケーションのソースコードではありません。アプリは `DiskHeatMap-v0.2.1.zip` をダウンロードしてください。
