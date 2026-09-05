# Personal Thinking OS

## Purpose

このRepositoryは、日々のAIとの対話から生まれる自分の思考を、再利用可能なKnowledgeとして蓄積するための個人用Thinking OSです。

単なるメモ置き場ではなく、会話から思考を取り出し、構造化し、知識化し、将来の判断や仕事で再利用するための基盤です。

保存する対象は、次のような自分自身の思考資産です。

- 思考と判断基準
- 仕事の進め方
- 学びと気づき
- Framework / Method / Principle
- Case / Mindset / Checklist
- 思考の変化と修正

## Philosophy

これは会社のKnowledgeではありません。

> 会社のKnowledgeではなく、自分のThinking OSを持ち運ぶ。

このRepositoryでは、「何を知っているか」よりも「どう考えるか」を保存します。蓄積するのは、Thinking Pattern、Decision Pattern、Work Pattern、Learning Patternです。

会社、顧客、プロジェクトに固有の情報は保存せず、そこから抽象化した自分の思考・学びだけを残します。

## Structure

```text
.
├── README.md
├── skills/
│   ├── thought-capture-structuring.md
│   └── playbook-record-registration.md
├── knowledge/
│   ├── principles/
│   ├── frameworks/
│   ├── methods/
│   ├── checklists/
│   ├── case-studies/
│   ├── learnings/
│   └── mindsets/
└── templates/
    └── knowledge-record.md
```

## Workflow

```text
Daily Conversation
↓
Thought Capture & Structuring
↓
Knowledge
↓
Playbook Registration
↓
Accumulated Thinking OS
```

1. 日々の会話から、残す価値のある思考を見つける。
2. `skills/thought-capture-structuring.md` に従い、質問で暗黙知を引き出して構造化する。
3. 完成したKnowledgeを、内容に合う `knowledge/` の分類へ新規ファイルとして保存する。
4. `skills/playbook-record-registration.md` に従い、再利用しやすいRecordとして登録する。

## Rules

### Append Only

既存Knowledgeは参照専用です。登録・更新時には、既存Recordを勝手に変更しません。

- 既存Recordを編集、削除、統合しない
- 既存RecordのTitle、Essence、Category、Type、Status、順番を変更しない
- 似た内容を見つけても、勝手に重複排除しない
- 新しいKnowledgeは必ず新規ファイルとして追加する
- 関連性がある場合は、新規Knowledge側から既存Knowledgeを参照する
- 明確な重複がある場合は、追加前にユーザーへ確認する

### Confidentiality

このRepositoryは公開される可能性があります。次の情報は保存しません。

- 顧客名、個人情報、社内固有情報
- システム情報、ソースコード、認証情報、URL
- 非公開資料、契約情報、その他の機密情報

Case Studyを残す場合も、会社固有の事実ではなく、そこから抽象化した自分の思考・学びとして記録します。

### Quality

すべての思考を無理にFrameworkやMethodへ一般化しません。小さな気づきは短い記録で残し、思考の変化があるときはBefore / After、Trigger、Why、Anti-pattern、Personal Ruleなどを使います。

## Adding Knowledge

1. 会話中に「これ構造化して」「この気づきを残したい」などの明示的な依頼があったら、Thought Capture Skillを発動する。
2. 仮説を提示し、必要な質問を通じて思考の背景と再利用条件を確認する。
3. `templates/knowledge-record.md` を出発点にする。ただし不要な見出しは削除し、内容に合わせて構成する。
4. 既存Knowledgeとの類似を確認する。明確な重複はユーザーに確認し、追加する場合も既存ファイルは変更しない。
5. 新規ファイルを適切な `knowledge/` サブディレクトリへ追加する。
6. Playbook Record Registration SkillでMetadataと関連Knowledgeを整える。

## Categories

- `principles/`: 判断や行動を支える原則
- `frameworks/`: 思考や分析の枠組み
- `methods/`: 再現可能な進め方
- `checklists/`: 実行前後に確認する項目
- `case-studies/`: 抽象化した事例と学び
- `learnings/`: 日常の気づきや学習
- `mindsets/`: 物事の捉え方、姿勢、思考の転換
