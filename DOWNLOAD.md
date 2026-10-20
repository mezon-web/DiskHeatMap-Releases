# ダウンロードと照合

[GitHub Releases](https://github.com/mezon-web/DiskHeatMap-Releases/releases/latest) から、同じ版の以下2ファイルをダウンロードしてください。

- `DiskHeatMap-v0.1.4-win-x64.zip`
- `DiskHeatMap-v0.1.4-win-x64.zip.sha256.txt`

PowerShellでZIPのSHA-256を計算します。

```powershell
Get-FileHash -LiteralPath .\DiskHeatMap-v0.1.4-win-x64.zip -Algorithm SHA256
Get-Content -LiteralPath .\DiskHeatMap-v0.1.4-win-x64.zip.sha256.txt
```

両方の64桁の値が一致することを確認してください。大文字・小文字の違いは問題ありません。ZIPを展開し、`DiskHeatMap.exe` を起動します。日本語の使い方も同梱しています。

必要環境はWindows 11 x64と.NET 10 **Desktop** Runtime x64です。ランタイムは同梱していません。Microsoftの [公式ページ](https://dotnet.microsoft.com/ja-jp/download/dotnet/10.0) から入手できます。

設定はEXE隣の `DiskHeatMap.settings.json` へ保存します。更新時はアプリを終了し、既存の設定ファイルを残して新しいEXEと使い方を配置してください。

GitHubの「Source code」リンクは公開資料のアーカイブです。アプリのダウンロードには上記の `win-x64.zip` を選んでください。
