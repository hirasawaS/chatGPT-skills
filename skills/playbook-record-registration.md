# Skill 02: Playbook Record Registration

## Purpose

Skill 01で完成したKnowledge Documentを、既存のKnowledge / Playbook形式に合わせた新しいRecordとして登録する。

このSkillは思考を作らない。内容の深掘り、暗黙知の抽出、思考の修正は `skills/thought-capture-structuring.md` の責務です。

## Activation

Knowledge Documentが完成し、ユーザーが保存・登録を依頼したときに発動する。未整理の会話から新しい思考を推測して登録しない。

## Append Only: Non-negotiable

既存Knowledgeは参照専用です。登録時に既存Recordを変更してはいけない。

- 編集しない
- 削除しない
- 統合しない
- Titleを変更しない
- Essenceを変更しない
- Category、Type、Statusを変更しない
- 既存Recordの順番を変更しない
- 重複排除を目的に既存Recordを変更しない

新しいKnowledgeは必ず新規Markdownファイルとして追加する。関連する既存Knowledgeは、新規Recordの `Related Knowledge` から参照する。

## Duplicate Handling

1. 追加前に、既存Knowledgeに明確な重複がないか確認する。
2. 似ているだけなら、類似点と相違点を整理して新規Recordから参照する。
3. 明確に重複している場合は、ユーザーへ確認する。
4. ユーザーが新規追加を選んだ場合、既存Recordを変更せず新規ファイルを追加する。

## Registration Procedure

1. 完成したKnowledgeの本質を一文で確認する。
2. 内容に応じて保存先ディレクトリを選ぶ。
3. 新しい、衝突しないファイル名を付ける。既存ファイルの名前変更はしない。
4. 冒頭にMetadataを付ける。値はKnowledgeの内容から判断し、推測で機密情報を補わない。
5. 不要なセクションは削除し、内容に合う構成で本文を保存する。
6. `Related Knowledge` があれば既存RecordのパスやTitleを記載する。
7. 追加後に、既存ファイルが変更されていないことと機密情報が含まれていないことを確認する。

## Metadata

可能な場合、次のFront MatterをKnowledgeの冒頭に置く。

```yaml
---
title: ""
category: ""
type: ""
status: ""
essence: ""
---
```

### Category候補

- `How to Work`
- `Skill`
- `Case / Learning`
- `Mindset`

### Type候補

- `Principle`
- `Framework`
- `Method`
- `Checklist`
- `Case Study`
- `Learning`

Statusは、たとえば `draft`、`active`、`revisit` など、現在の確度や見直し状態を表す。新規RecordのStatusは、ユーザーの意図と内容に合わせる。

## Registration Quality Checks

- 新規ファイルとして追加されているか
- 既存Knowledgeの内容・名前・順番に変更がないか
- Title、Category、Type、Essence、Statusが内容と一致しているか
- Knowledgeの本質が再利用可能な形で短く表現されているか
- 関連Knowledgeが必要に応じて参照されているか
- 会社、顧客、プロジェクト固有の機密情報が含まれていないか
- 既存Recordとの重複を勝手に解消していないか

登録用の雛形は `templates/knowledge-record.md` を使う。ただし、セクションを内容に合わせて調整する。
