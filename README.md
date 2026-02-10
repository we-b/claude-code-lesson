# Claude Code活用コース サンプルファイル

このリポジトリは「非エンジニアのためのClaude Code活用」コースで使用するサンプルファイルです。

## 使い方

### 1. リポジトリをクローン

```bash
git clone https://github.com/we-b/claude-code-lesson.git ~/claude-code-lesson
```

### 2. クローンしたフォルダでClaude Codeを起動

```bash
cd ~/claude-code-lesson
claude
```

## フォルダ構成

```
sample-files/
├── documents/          # ドキュメント類
│   ├── 議事録_20260115.md
│   ├── 報告書_2025Q1.txt
│   └── 提案書_草案.txt
├── spreadsheets/       # 表計算データ
│   └── 予算管理.csv
├── images/             # 画像ファイル（空）
├── templates/          # テンプレート
│   └── 週報テンプレート.md
└── projects/           # プロジェクト別フォルダ
    ├── project-a/
    │   └── 進捗.md
    ├── project-b/
    │   └── 進捗.md
    └── project-c/
        └── 進捗.md
```

## 各Lessonで使用するファイル

### Lesson 2: ローカルファイル操作エージェント

#### Chapter 2: ファイル操作の基本
- `sample-files/` フォルダ全体を使ってGlob、Read、Write、Edit、Bashを学習

#### Chapter 3: 基本操作を組み合わせて実践
- `templates/週報テンプレート.md` - テンプレートから資料を自動生成
- `projects/*/進捗.md` - 複数フォルダから情報を収集してレポート作成

#### Chapter 4: オフィスファイルを操作
- Word/Excelファイルの読み書き練習（Chapter内で新規作成）

## ライセンス

教育目的での使用を想定しています。
