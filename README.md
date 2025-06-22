# Conventional Commits Form

このプロジェクトは、[Conventional Commits](https://www.conventionalcommits.org/ja/v1.0.0/) 形式のコミットメッセージを簡単に生成できる HTML フォームです。  
コミットメッセージの形式統一を支援し、チーム開発における一貫性のある履歴管理を目的としています。

## 特長

- Webブラウザ上で動作するシンプルなフォーム
- `type`、`scope`、`description` など Conventional Commits に準拠した入力欄
- 入力内容をリアルタイムでフォーマットし、コピー可能なコミットメッセージを自動生成


## 使用方法

1. `ConventionalCommitsForm.html` を Webブラウザで開く
2. 各入力欄に必要な情報を入力
3. 下部に表示されるフォーマット済みメッセージをコピーして使用

### 入力項目

- **Type**: コミットの種類（例: `feat`, `fix`, `docs` など）
- **Scope** *(任意)*: 変更対象のスコープ（例: `auth`, `ui`, `api` など）
- **Description**: 短く簡潔な説明文
- **Body** *(任意)*: 詳細説明
- **Footer** *(任意)*: 関連する issue や BREAKING CHANGE などの追加情報

### 出力例

```text
feat(ui): ボタンのスタイルを修正

ユーザーが hover したときのスタイルを改善しました。

Refs: #123
```
