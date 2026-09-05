# Skill 01: Thought Capture & Structuring

## Purpose

会話の中で生まれた思考を、ユーザーへの質問を通じて深掘りし、未来の自分が再現・再利用できるKnowledgeへ変換する。

このSkillは思考を急いで文章化するためのものではない。会話の背景にある暗黙知を取り出し、本人の判断基準や思考の変化を明確にするためのものです。

## Activation

通常の会話では発動しない。次のような明示的な依頼があった場合だけ発動する。

- 「これ構造化して」
- 「この話を整理して」
- 「これをナレッジ化して」
- 「この気づきを残したい」
- 「今までの話をドキュメントにして」

明示的な依頼がない場合は、思考を勝手にKnowledge化・保存しない。

## Workflow

```text
Conversation
↓
Reflection
↓
Hypothesis
↓
Questioning
↓
Tacit Knowledge Extraction
↓
Thinking Structure
↓
Generalization
↓
Reusable Knowledge
```

## Operating Procedure

### 1. Reflection

直前までの会話を振り返り、事実、解釈、感情、判断、変化を分けて読む。会社・顧客・プロジェクト固有の情報や機密情報が含まれていないかも確認する。

### 2. Hypothesis

いきなり本文を書かず、まず「今回の本質は○○では？」という短い仮説を提示する。仮説は断定せず、ユーザーが修正できる形にする。

### 3. Questioning

必要な場合だけ、答えやすい数の質問をする。質問は次の観点から選ぶ。

- 何が起きたか
- そのとき何を考えていたか
- なぜそう考えたか
- 何に気づいたか
- 以前と何が変わったか
- 現在どう捉えているか
- 他の場面でも使えるか
- どこまで一般化できるか
- どんな条件なら成立しないか

情報が十分なら、質問を増やさず構造化へ進む。

### 4. Thinking Correction

以前の思考を修正する要素がある場合は、積極的に次の形で抽出する。

- **Before**: 以前の考え方
- **After**: 現在の考え方
- **Trigger**: 何が変化を起こしたか
- **Why**: なぜ修正が必要だったか
- **Anti-pattern**: 以前の考え方が招く問題
- **Personal Rule**: 今後の自分向けのルール

### 5. Generalization

個別の出来事から、再利用できる判断基準、条件、手順、パターンを抽出する。ただし過度に一般化しない。適用条件と成立しない条件を明記する。

### 6. Output

内容に応じて、次のいずれかの粒度でKnowledge Documentを作る。

#### 小さな気づき

```text
Context
Insight
Why it matters
Essence
How I want to remember this
```

#### 思考の変化

```text
Context
Before / After
Trigger
Why
Insight
Personal Rules
```

#### 再利用可能な知識

```text
Essence
Context
Insight
Thinking
Framework / Method
Example
Reusability
Personal Rules
Related Knowledge
```

不要なセクションは作らない。テンプレートを機械的に埋めない。

## Quality Checks

- ユーザー自身の思考・判断基準として書かれているか
- 事実と解釈が混ざっていないか
- 他の場面で使う条件が分かるか
- 成立しない条件や限界があるか
- Before / Afterが必要なのに欠けていないか
- 機密情報や会社固有の情報を抽象化できているか
- 後から読んだ自分が、その時点の気づきを再現できるか

完成後のKnowledge登録は `skills/playbook-record-registration.md` に引き渡す。思考の構造化とRecord登録を同じ工程として扱わない。
