# GeomCatalog

3Dデータを、もっと見やすく、もっと探しやすく。

GeomCatalog は、STEP・IGES・STL などの 3D データをサムネイルで一覧表示し、名称やコメントとあわせて整理・検索できる Windows 向けの 3D データ管理ツールです。必要なモデルをすばやく見つけ、閲覧から詳細確認までスムーズにつなげます。 :contentReference[oaicite:0]{index=0}

---

## GeomCatalog とは

GeomCatalog は、3D設計データをサムネイル中心で管理するための Windows デスクトップアプリケーションです。  
フォルダから CAD ファイルを取り込み、ローカルカタログを構築し、バックグラウンドでサムネイルを生成しながら、一覧・検索・整理を行えます。詳細確認が必要な場合は、連携ビューア **StepGeomChecker** で開くことができます。 :contentReference[oaicite:1]{index=1}

---

## 主な特長

- STEP / IGES / STL ファイルに対応
- サムネイル中心の一覧表示
- フォルダ単位での取り込み
- ローカル SQLite ベースのカタログ管理
- バックグラウンドでのサムネイル生成
- 検索・絞り込み・整理に対応
- StepGeomChecker との連携で詳細確認が可能 :contentReference[oaicite:2]{index=2}

---

## こんな用途に向いています

- 受領した 3D データをまとめて整理したい
- 過去モデルをサムネイル一覧から探したい
- STEP や IGES ファイルを見比べながら確認したい
- 3D データの管理と詳細確認を分けて運用したい
- 詳細閲覧は StepGeomChecker、管理は GeomCatalog と役割分担したい

---

## 対応フォーマット

現在の主な対応形式は以下です。

- `.step`
- `.stp`
- `.iges`
- `.igs`
- `.stl` :contentReference[oaicite:3]{index=3}

---

## 基本的な使い方

### 1. カタログを作成または開く
ローカルのカタログデータベースを作成し、管理対象の情報を保存します。  
カタログには、アイテム情報、フォルダ情報、タグ、サムネイル状態などが保持されます。 :contentReference[oaicite:4]{index=4}

### 2. フォルダを取り込む
取り込み元フォルダを選択し、次のいずれかの方法で登録します。

- Reference
- Copy
- Move :contentReference[oaicite:5]{index=5}

### 3. サムネイルで一覧表示
取り込み後は、メイン画面のサムネイル一覧からファイルを視覚的に確認できます。  
フォルダやメタデータによる絞り込みにも対応します。 :contentReference[oaicite:6]{index=6}

### 4. 詳細確認
選択したファイルは、必要に応じて StepGeomChecker で開いて詳細確認できます。 :contentReference[oaicite:7]{index=7}

---

## UI コンセプト

GeomCatalog は、Lightroom のような視覚的ワークフローを意識して設計されています。

- 左側: フォルダツリー / フィルタ
- 中央: 大きなサムネイル一覧
- 右側: メタデータ / 操作パネル
- 下部: フィルムストリップ / ステータス表示

大量の CAD データの中から、必要なモデルへ素早くたどり着くことを目的としています。 :contentReference[oaicite:8]{index=8}

---

## StepGeomChecker との連携

GeomCatalog は、3D データの「探す・整理する」を担い、  
StepGeomChecker は、3D データの「詳しく見る・確認する」を担います。

この連携により、一覧管理と詳細確認を分けて効率よく運用できます。 :contentReference[oaicite:9]{index=9}

---

## 製品の位置づけ

GeomCatalog は、次のような製品ではありません。

- フル機能の PDM / PLM
- クラウド前提の SaaS
- 3D モデリングソフト
- StepGeomChecker の代替

GeomCatalog は、あくまで **3D データのカタログ化・閲覧・整理・検索** に特化した製品です。 :contentReference[oaicite:10]{index=10}

---

## エディションについて

現在の基本方針では、無料版の基準は次のとおりです。

- 1カタログ
- 最大 200 アイテム
- Reference 取り込み対応
- Copy / Move は制限対象
- 高度な同期機能は制限対象 :contentReference[oaicite:11]{index=11}

※ 実際の仕様は今後変更される場合があります。

---

## 動作環境

- Windows 対応
- .NET 8 ベースの WinForms アプリケーション :contentReference[oaicite:12]{index=12}

---

## ダウンロード

最新版のダウンロードは、GitHub Releases または配布ページをご利用ください。

> 準備中

---

## スクリーンショット

> 準備中

- メイン画面
- 取り込み画面
- サムネイル一覧
- 詳細パネル

---

## 今後の展開

GeomCatalog は、3D データ管理をより使いやすくするため、今後も改善を進めていきます。

- サムネイル表示の強化
- 検索・絞り込み機能の改善
- 運用しやすい取り込みフローの最適化
- StepGeomChecker との連携強化

---

## お問い合わせ

> www.lwj.co.jp
