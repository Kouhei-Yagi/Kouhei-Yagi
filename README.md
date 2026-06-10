# 八木 孝平（Kouhei Yagi）

バックエンドエンジニアを目指して学習・開発を進めています。  
主に Laravel / PHP を中心に、業務系 Web アプリケーションの開発に取り組んでいます。

## スキル
※ レベルは「ポートフォリオでの使用経験」「書籍での学習経験」を基準にしています。

### 実践レベル（ポートフォリオで使用）
- PHP / Laravel
- Tailwind CSS
- Git / GitHub

### 基礎レベル（書籍などで習得）
- Linux
- Docker
- HTML
- SQL

### 入門レベル（書籍などで学習経験あり）
- CSS
- JavaScript

### 資格
- 基本情報技術者試験
- LinuC レベル1
- PHP技術者認定試験 初級
- ITパスポート

## 代表作：顧客管理アプリ（Laravel CRM App）
顧客・案件・対応履歴を一元管理できる業務系 CRM システムです。
Laravel を用いて、認証・検索・権限管理・テストまで一通り実装しています。

### リポジトリ
[https://github.com/kouhei-yagi/laravel-crm-app](https://github.com/kouhei-yagi/laravel-crm-app)

### 主な実装内容
- 顧客・案件・対応履歴の CRUD（関連データの表示・管理）
- 複数条件検索・ソート・ページネーション維持
- 権限管理（担当者のみ編集・削除可能）
- master 管理（顧客ステータス / ランク / 案件ステータス / 対応種別）
- CSV エクスポート（検索条件を反映）
- 外部キー制約・SoftDeletes によるデータ保護
- Feature Test / Unit Test（CRUD・検索・Policy・FormRequest）
- Factory / Seeder によるダミーデータ生成

## 改善予定

### 機能拡張
- ダッシュボードの追加（案件数・対応件数などの可視化）
- ファイル添付機能の導入（PDF 等のアップロード）
- タグ管理の追加（柔軟な検索・分類を可能にする）

### UI / UX 改善
- 詳細ページの 2 カラムレイアウト化
- 検索条件フォームの折りたたみ機能
- 顧客詳細から対応履歴を直接追加できる導線の改善

### 技術的改善
- Controller の責務分離（Service 層の導入）
- 検索・ソートロジックの共通化（Trait の拡張）
- CSV エクスポート処理の Service 化

### テスト強化
- CSV エクスポート機能の Feature Test 追加

※ 今後も保守性・拡張性を意識しながら継続的に改善を進めていきます。
