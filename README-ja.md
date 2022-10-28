# GitHub Labels export import
GitHubにある1つのリポジトリのLabelsをエクスポートし、別のリポジトリにインポートすることができます。

## 言語
- [English](README.md)
- [Japanese / 日本語](README-ja.md)

## 説明
1. インポート側のリポジトリから全てのラベルを削除します
2. エクスポート側のリポジトリから全てのリポジトリを取得します
3. 取得したラベルをインポートリポジトリに追加します

##  インストール
```bash
git clone git@github.com:HidakaRintaro/github-labels-export-import.git
```

## セットアップ
```bash
npm install
```

## 使い方
```bash
node index.js <owner> <exportRepo> <importRepo> <token>
```

## ライセンス
[MIT](LICENSE)
