# Claude Code活用コース サンプルファイル

このリポジトリは「非エンジニアのためのClaude Code活用」コースで使用するサンプルファイルです。

## 使い方

### 1. リポジトリをクローン

```bash
git clone https://github.com/we-b/claude-code-lesson.git ~/claude-code-lesson
```

### 2. 各章のフォルダをVSCodeで開く

章ごとに専用のフォルダが用意されています。学習する章のフォルダをVSCodeで開いてください。

```bash
# Chapter 2を学習する場合
code ~/claude-code-lesson/lesson2/chapter2

# Chapter 3を学習する場合
code ~/claude-code-lesson/lesson2/chapter3

# Chapter 4を学習する場合
code ~/claude-code-lesson/lesson2/chapter4
```

### 3. Claude Codeを起動

VSCodeでフォルダを開いた状態で、Claude Codeを起動します。

## フォルダ構成

```
claude-code-lesson/
├── README.md
└── lesson2/
    ├── chapter2/           ← ファイル操作の基本
    │   ├── documents/
    │   │   ├── 議事録_20260115.md
    │   │   ├── 報告書_2025Q1.txt
    │   │   └── 提案書_草案.txt
    │   ├── spreadsheets/
    │   │   └── 予算管理.csv
    │   └── images/
    │
    ├── chapter3/           ← 基本操作を組み合わせて実践
    │   ├── templates/
    │   │   └── 週報テンプレート.md
    │   └── projects/
    │       ├── project-a/
    │       │   └── 進捗.md
    │       ├── project-b/
    │       │   └── 進捗.md
    │       └── project-c/
    │           └── 進捗.md
    │
    └── chapter4/           ← オフィスファイルを操作
        └── README.md       （この章ではファイルを新規作成します）
```

## 各章の内容

### Lesson 2: ローカルファイル操作エージェント

| 章 | タイトル | 学習内容 |
|:---|:---|:---|
| Chapter 2 | ファイル操作の基本 | Glob、Read、Write、Edit、Bashの基本操作 |
| Chapter 3 | 基本操作を組み合わせて実践 | テンプレートから資料生成、複数フォルダから情報収集 |
| Chapter 4 | オフィスファイルを操作 | Word/Excelの読み書き、データ連携 |

## ライセンス

教育目的での使用を想定しています。
