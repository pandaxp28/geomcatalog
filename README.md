# GeomCatalog - 3D Data Catalog and Thumbnail Browser for Windows

Thumbnail-centered Windows catalog software for STEP, IGES, and STL files.  
STEP・IGES・STL などの 3D データを、サムネイルで整理・検索できる Windows 向け 3D データ管理ツール。

GeomCatalog is a Windows desktop tool focused on cataloging, browsing, and organizing 3D CAD files with a thumbnail-first workflow.  
GeomCatalog は、3D CAD データをサムネイル中心で整理・検索・管理するための Windows デスクトップツールです。

[![Download Releases](https://img.shields.io/badge/Download-Releases-blue?style=for-the-badge)](../../releases)
[![Official Website](https://img.shields.io/badge/Official-Website-green?style=for-the-badge)](https://www.lwj.co.jp/)
[![License](https://img.shields.io/badge/License-See%20Below-lightgrey?style=for-the-badge)](#license--ライセンス)

---

## English

GeomCatalog is a Windows desktop application for managing 3D design data such as STEP, IGES, and STL.

If you are looking for a practical Windows tool for browsing large numbers of 3D files visually, organizing them in a local catalog, and opening selected files in StepGeomChecker for deeper inspection, GeomCatalog is designed for that workflow.

### Highlights

- Import and organize STEP / IGES / STL files in a Windows GUI
- Build a local SQLite-based catalog
- Browse files in a thumbnail-centered library view
- Use folder-based import workflows
- Choose import modes:
  - Reference
  - Copy
  - Move
- Generate thumbnails in the background
- Search and filter files by folder and metadata
- Review item details in a side panel
- Open selected items in StepGeomChecker for detailed viewing
- Designed for responsive handling of larger CAD libraries

### Typical Use Cases

- Organizing large collections of received CAD files
- Browsing old 3D models visually from thumbnails
- Finding the right model quickly from a local library
- Separating catalog management from detailed geometry inspection
- Using GeomCatalog for discovery and StepGeomChecker for verification

---

## 日本語

GeomCatalog は、STEP、IGES、STL などの 3D CAD データを、サムネイル中心で整理・検索・管理するための Windows 向けデスクトップツールです。

大量の 3D データを視覚的に探したい、ローカルカタログで整理したい、必要なときだけ StepGeomChecker で詳しく確認したい、という運用を想定して設計しています。

### 特長

- STEP / IGES / STL を Windows GUI で取り込み・整理可能
- ローカル SQLite ベースのカタログを構築
- サムネイル中心の一覧表示に対応
- フォルダ単位での取り込みに対応
- 取り込みモードを選択可能
  - Reference
  - Copy
  - Move
- バックグラウンドでサムネイル生成
- フォルダやメタデータによる検索・絞り込みに対応
- 右側パネルで詳細情報を確認可能
- 選択ファイルを StepGeomChecker で開いて詳細確認可能
- 大量の CAD データを扱いやすい運用を重視

### 主な用途

- 受領した 3D データをまとめて整理したいとき
- 過去モデルをサムネイル一覧から探したいとき
- ローカルライブラリから必要なモデルをすばやく見つけたいとき
- 管理作業と詳細確認作業を分けて運用したいとき
- GeomCatalog で探して StepGeomChecker で詳しく確認したいとき

---

## Quick Links / クイックリンク

- Download / ダウンロード  
  [Go to Releases](../../releases)

- Official Website / 公式ページ  
  [LWJ Official Website](http://www.lwj.co.jp/)

- Companion Viewer / 連携ビューア  
  [StepGeomChecker](https://github.com/pandaxp28/StepGeomChecker)

---

## Screenshots / スクリーンショット

Main View / メイン画面  
![GeomCatalog Thumbnail Library](imgages/geomcatalog-thumbnail.png)

Import Dialog / 取り込み画面  
![GeomCatalog Import Dialog](imgages/import.png)



---

## Features / 機能一覧

| Feature | English | 日本語 |
|---|---|---|
| 3D file catalog | Build and manage a local catalog for CAD files | CAD ファイル用のローカルカタログを作成・管理 |
| Supported formats | Import and organize STEP / IGES / STL files | STEP / IGES / STL を取り込み・整理 |
| Thumbnail library | Browse files visually with thumbnails | サムネイルで視覚的に一覧表示 |
| Import workflow | Import folders with Reference / Copy / Move | Reference / Copy / Move でフォルダ取り込み |
| Local storage | Store catalog data locally with SQLite | SQLite によるローカル保存 |
| Background jobs | Generate thumbnails in the background | バックグラウンドでサムネイル生成 |
| Search and filter | Narrow files by folders and metadata | フォルダやメタデータで絞り込み |
| Detail panel | Review item details and actions in the side panel | 右側パネルで詳細情報と操作を表示 |
| StepGeomChecker handoff | Open selected files for detailed inspection | 選択ファイルを StepGeomChecker で詳細確認 |
| Large library workflow | Designed for efficient handling of many CAD files | 大量の CAD データを扱いやすい運用に対応 |

---

## Supported Formats / 対応形式

### Input / 入力

- STEP (.step / .stp)
- IGES (.igs / .iges)
- STL (.stl)

### Output / 出力

- Managed local catalog records
- Thumbnail cache
- Metadata updates
- StepGeomChecker handoff for selected files

---

## Download / ダウンロード

Please download the latest version from the Releases page.  
最新版は Releases ページからダウンロードしてください。

[Download from Releases / Releases からダウンロード](../../releases)

---

## Website / 公式ページ

The product page is also available on the company website.  
製品ページは当社ウェブサイトにも掲載予定です。

[LWJ Official Website](http://www.lwj.co.jp/)

---

## Notes / 注意事項

- Supported environment is Windows desktop.
  対応環境は Windows デスクトップです。

- Initial catalog creation or large imports may take time depending on file count and model complexity.
  初回カタログ作成や大量取り込みでは、件数やモデルの複雑さにより時間がかかる場合があります。

- Background job failures should be handled as job states rather than blocking normal workflow.
  バックグラウンド処理の失敗は、通常操作全体を止めるのではなく、ジョブ状態として扱う想定です。

- Detailed viewing and inspection are intended to be handled in StepGeomChecker.
  詳細表示や詳細確認は StepGeomChecker 側で行う想定です。

---

## Environment / 対応環境

- Windows
- .NET 8 based WinForms application

---

## License / ライセンス

GeomCatalog is provided with a free edition baseline, and some features may be gated for paid editions.  
GeomCatalog は無料版を基本とし、一部機能は有料版向けに制限される場合があります。

Current public baseline includes:
- one catalog
- up to 200 registered items
- Reference import allowed
- Copy / Move gated
- advanced sync features gated

現在の基本方針:
- 1 カタログ
- 最大 200 アイテム
- Reference 取り込み対応
- Copy / Move は制限対象
- 高度な同期機能は制限対象

If you include a separate license or terms file in this repository later, please refer to that file for detailed conditions.  
今後このリポジトリに利用条件やライセンスファイルを追加する場合は、詳細条件はそちらを参照してください。

---

## Feedback / フィードバック

Bug reports, feedback, and suggestions are welcome.  
不具合報告、ご意見、ご要望を歓迎します。
