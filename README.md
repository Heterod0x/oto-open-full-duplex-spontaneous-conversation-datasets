## OTO Open Full-Duplex Spontaneous Conversation Datasets

英語のフルデュープレックス（同時双方向）な雑談音声会話を、オープンに議論しながら設計・収集・公開していくためのリポジトリです。プロジェクトは oto（私たちのスタートアップ）がリードし、最終的に合計 1,000 万時間規模の英語雑談会話データを目指します。

### 概要
- **目的**: フルデュープレックス会話のデータセット設計・収集・評価・公開ポリシーをコミュニティで議論し、オープンな形で前進させる
- **対象**: 英語の自発的（spontaneous）かつ自然な雑談音声会話
- **公開場所**: 主に Hugging Face の Discussions を中心に公開議論を行います（リンクは後述）。

### Full-duplex（同時双方向）とは
相手の発話を待たずに、重なり・相槌・割り込み・共同での語り直しなどが自然に起こり得る会話形態です。電話のような半二重（片方向ずつ交互）の会話とは異なり、人間同士の雑談に近い相互作用を再現します。

### 目標とマイルストーン
- 短期: データの要件定義、収集設計、倫理・プライバシー基準の合意
- 中期: プロトタイプ規模の収集・評価手順・メタデータ仕様の確立
- 長期: 1,000 万時間規模の英語雑談音声会話の整備と段階的公開（可能な範囲）

### スコープ
- 自発的な雑談（task-free/loose-goal）
- オーバーラップ発話・相槌・修復（repair）・沈黙などの会話現象
- 音声＋メタデータ（収録条件、話者属性の匿名化情報など）

非スコープ（現時点）
- 個人を特定し得る生データの無制限配布
- 過度に制約的なスクリプト読み上げデータのみの収集

### 倫理・プライバシー
本プロジェクトは、個人のプライバシーと倫理を最優先します。収集・公開は法令および各プラットフォーム規約に従い、同意・匿名化・再配布条件を明確化します。詳細は今後、議論のうえで明文化します。

### 参加方法
1. Hugging Face の Discussions へ参加（提案・質問・議論）
2. GitHub Issues での課題提起・要望
3. Pull Request によるドキュメント整備・提案の反映

参考リンク（更新予定）
- Hugging Face Discussions: TBA
- oto サービス: TBA

### コントリビューション
- 新規 Issue や Discussion の作成時は、背景・目的・想定インパクトを簡潔に書いてください。
- 提案（PR）は最小差分で、関連する議論や Issue へのリンクを記載してください。
- 文章は日本語/英語どちらでも歓迎です。

### リポジトリ構成
このリポジトリは議論駆動のドキュメント中心です。全体像は `PROJECT_STRUCTURE.md` を参照してください。

### ライセンス
議論・設計ドキュメントのライセンスは整備中です。公開データのライセンスはデータソースに依存する場合があります。確定次第、本 README と LICENSE に反映します。

### メンテナー
- oto（スタートアップ） / Maintainers: TBA

### よくある質問（FAQ）
Q. 実データはいつ公開されますか？
A. 倫理審査・匿名化・権利整理を優先し、段階的に公開可否を判断します。時期は議論の進展に応じて更新します。

Q. 英語以外は対象ですか？
A. 当面は英語を主対象とします。将来的な多言語拡張は議論のうえ検討します。

---

English (brief)

This repository hosts open discussions and documentation for building large-scale, full-duplex spontaneous conversation datasets in English, led by oto. We aim for 10M hours. Join via Hugging Face Discussions and GitHub Issues/PRs. Ethics and privacy come first; releases will be staged and policy-driven.


