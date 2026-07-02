# -# HorseAI Ultimate

> **AI-Powered Horse Racing Analysis Framework**
>
> Version: **1.0.0**

---

# Overview

HorseAI Ultimateは、競馬予想AIではありません。

本プロジェクトは、

**「競馬レースを再現性のある手順で分析するためのAI分析システム」**

を構築することを目的としています。

目的は単なる的中率ではなく、

* 長期回収率
* 分析品質
* 再現性
* 客観性
* 保守性
* 拡張性

を重視した競馬分析フレームワークを提供することです。

HorseAI Ultimateでは、

**事実（Fact）・分析（Analysis）・期待値（Value）・意思決定（Decision）**

を完全に分離して処理します。

---

# Project Philosophy

HorseAI Ultimateは以下の思想に基づいて設計されています。

## 1. Fact First

すべての分析は客観的事実から開始します。

推測による補完は禁止します。

---

## 2. Explainable AI

すべての分析には根拠が必要です。

結論のみを出力してはいけません。

分析結果は必ず

* 使用データ
* 分析根拠
* 判断理由

を保持します。

---

## 3. Reproducibility

同じデータを入力した場合、

同じ分析結果になることを目標とします。

分析フローを固定し、

AIの回答品質を安定させます。

---

## 4. Value Driven

能力順位と馬券価値は異なります。

HorseAI Ultimateでは、

能力評価と期待値評価を分離します。

---

## 5. Continuous Improvement

本システムは継続的に改善されます。

すべての変更はCHANGELOGで管理します。

---

# Project Structure

```
HorseAI Ultimate/

README.md

LICENSE

CHANGELOG.md

SYSTEM/
├── Core Rules.md
├── Workflow.md
├── Decision Rules.md
└── Confidence Rules.md

PROMPTS/
├── 01 Data Collection.md
├── 02 Validation.md
├── 03 Normalization.md
├── 04 Ability.md
├── 05 Pace.md
├── 06 Value.md
├── 07 Betting.md
└── 08 Audit.md

KNOWLEDGE/
├── Course Database.md
├── Bloodline.md
├── Trainer.md
├── Jockey.md
├── Pace Dictionary.md
├── Bias.md
└── Race Class.md

TEMPLATES/
├── Input.md
├── Output.md
└── JSON.md

TEST/
├── Case001.md
├── Case002.md
└── Case003.md

GPTS/
├── Instructions.md
├── Knowledge List.md
└── Actions.md
```

---

# Analysis Workflow

HorseAI Ultimateは以下の順序で分析を行います。

```
Information Collection

↓

Validation

↓

Normalization

↓

Ability Analysis

↓

Pace Analysis

↓

Value Analysis

↓

Betting Strategy

↓

Audit

↓

Final Report
```

この順番は変更しません。

---

# Core Principles

HorseAI Ultimateは以下を厳守します。

* 情報を創作しない
* 推測しない
* 情報不足を補完しない
* 古い情報を最新情報として扱わない
* 公式情報を最優先する
* 能力分析でオッズを参照しない
* 期待値分析で初めてオッズを利用する
* 分析根拠を保持する
* 自己監査を実施する

---

# Data Priority

情報取得優先順位

1. 主催者公式
2. JRA公式
3. 地方競馬公式
4. 公的データベース
5. 信頼できる競馬データベース
6. 信頼できる報道
7. ユーザー提供情報

---

# Output Standard

すべての分析結果は以下の構造を採用します。

```
Summary

Fact

Analysis

Evidence

Risk

Confidence

Conclusion
```

---

# Versioning

本プロジェクトはSemantic Versioningに準拠します。

```
MAJOR.MINOR.PATCH
```

例

```
1.0.0

1.1.0

2.0.0
```

---

# Development Policy

各ファイルは単独で理解可能な構造とします。

依存関係を最小限にし、

保守・更新が容易なモジュール構成を維持します。

---

# Future Expansion

将来的に以下の機能追加を想定しています。

* AI Rating Engine
* Speed Figure
* Pace Figure
* Bias Detector
* Race Level Rating
* Trainer Statistics
* Jockey Statistics
* Monte Carlo Pace Simulation
* Expected Value Optimizer

---

# Changelog

変更履歴はCHANGELOG.mdで管理します。

READMEには履歴を記載しません。

---

# License

ライセンス内容はLICENSE.mdを参照してください。

---

# Project Status

Current Version

```
v1.0.0
```

Development Status

```
Active Development
```

System Status

```
Foundation Complete
```

---

# Author

HorseAI Ultimate Project

AI Racing Analysis Framework

Version 1.0.0
