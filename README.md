# 商業高校教員向け 生成AI利活用ツールキット

商業高等学校の教員が生成AI技術を効果的に活用するための包括的なリソース集です。プロンプトエンジニアリングの基礎から実践的な活用方法まで、教育現場で即座に使える教材・ツールを提供します。

## 📚 概要

このツールキットは、商業教育における生成AI活用を支援することを目的としています。簿記・会計、マーケティング、情報処理、ビジネス基礎の各分野で使用できる実践的なプロンプト集や評価ツールを含んでいます。

### 対象者
- 商業高等学校の教員
- 簿記、会計、マーケティング、情報処理、ビジネス基礎等の担当教師
- ICTを活用した教育改善に興味のある教育関係者

### 特徴
- **実践的**: 即座に授業で使用可能な具体的なプロンプト例
- **体系的**: 基礎から応用まで段階的に学習可能
- **包括的**: 商業教育の主要分野を網羅
- **継続的**: 継続的な改善をサポートするツール

## 📁 ファイル構成

### 📄 メイン資料
- [`detailed_lecture_materials.md`](./detailed_lecture_materials.md) - セミナー詳細講義資料（90分）

### 📋 基本テンプレート集
- [`templates/5W1H_confirmation_sheet.md`](./templates/5W1H_confirmation_sheet.md) - プロンプト作成前のチェックリスト
- [`templates/4_elements_structure_template.md`](./templates/4_elements_structure_template.md) - 効果的なプロンプト設計の基本構造
- [`templates/subject_basic_prompts.md`](./templates/subject_basic_prompts.md) - 商業教育各分野の基本テンプレート

### 📝 分野別プロンプト事例集
- [`examples/bookkeeping_prompt_examples.md`](./examples/bookkeeping_prompt_examples.md) - 簿記・会計分野（15例）
- [`examples/marketing_prompt_examples.md`](./examples/marketing_prompt_examples.md) - マーケティング分野（10例）
- [`examples/it_prompt_examples.md`](./examples/it_prompt_examples.md) - 情報処理分野（8例）
- [`examples/business_basics_prompt_examples.md`](./examples/business_basics_prompt_examples.md) - ビジネス基礎分野（7例）

### ✅ 評価・管理ツール
- [`tools/prompt_evaluation_checklist.md`](./tools/prompt_evaluation_checklist.md) - プロンプト評価チェックリスト
- [`tools/practice_record_sheet.md`](./tools/practice_record_sheet.md) - 実践記録シート
- [`tools/improvement_action_plan.md`](./tools/improvement_action_plan.md) - 改善アクションプラン

### 🎯 プレゼンテーション資料
- [`presentation/`](./presentation/) - セミナー用プレゼンテーション資料（4種類のフォーマット対応）
  - [`presentation/index.html`](./presentation/index.html) - プレゼンテーション選択ページ
  - [`presentation/reveal.html`](./presentation/reveal.html) - Reveal.js版（高機能プレゼンテーション）
  - [`presentation/swipe.html`](./presentation/swipe.html) - Swipe版（タッチ操作対応）
  - [`presentation/remark.html`](./presentation/remark.html) - Remark.js版（軽量版）
  - [`presentation/marp.md`](./presentation/marp.md) - Marp版（Markdownベース）

### 📊 フィードバック
- [`seminar_survey.md`](./seminar_survey.md) - セミナー受講後アンケート

## 🚀 使い方

### 0. プレゼンテーション資料の活用
セミナー講師や研修担当者の方は、以下のプレゼンテーション資料をご活用ください：

#### 📱 オンライン版（推奨）
GitHub Pagesで公開中：[https://nahisaho.github.io/CommerceHS-GenAI-toolkit/presentation/](https://nahisaho.github.io/CommerceHS-GenAI-toolkit/presentation/)

#### 💻 ローカル使用
1. [`presentation/index.html`](./presentation/index.html) をブラウザで開く
2. 用途に応じてプレゼンテーション形式を選択：
   - **正式なプレゼンテーション**: Reveal.js版
   - **タブレット・スマホ**: Swipe版（タッチ操作対応）
   - **軽量・シンプル**: Remark.js版
   - **Markdown編集**: Marp版

#### 🎯 プレゼンテーション特徴
- **4種類のフォーマット**: 用途に応じて選択可能
- **レスポンシブデザイン**: デスクトップ・タブレット・スマホに対応
- **インタラクティブ**: 演習コーナーや体験課題を含む
- **90分構成**: 基礎理解から実践まで体系的に学習

### 1. 基礎学習
1. [`detailed_lecture_materials.md`](./detailed_lecture_materials.md) でプロンプトエンジニアリングの基礎を学習
2. [`templates/5W1H_confirmation_sheet.md`](./templates/5W1H_confirmation_sheet.md) を使用してプロンプト作成の準備
3. [`templates/4_elements_structure_template.md`](./templates/4_elements_structure_template.md) で構造化されたプロンプト作成方法を習得

### 2. 実践活用
1. [`templates/subject_basic_prompts.md`](./templates/subject_basic_prompts.md) から担当科目の基本プロンプトを選択
2. [`examples/`](./examples/) フォルダから関連する事例を参照
3. [`tools/prompt_evaluation_checklist.md`](./tools/prompt_evaluation_checklist.md) で品質を確認

### 3. 継続改善
1. [`tools/practice_record_sheet.md`](./tools/practice_record_sheet.md) で実践結果を記録
2. [`tools/improvement_action_plan.md`](./tools/improvement_action_plan.md) でスキル向上を計画
3. 定期的な見直しと改善を実施

## 💡 活用例

### 学習指導案作成
```markdown
あなたは商業高校の簿記担当教師です。
高校1年生（簿記初学者）に対する「仕訳の基礎」の授業（50分）の学習指導案を作成してください。

【条件】
- 対象：高校1年生30名（簿記未習）
- 時間：50分（導入15分、展開25分、まとめ10分）
- 教材：教科書、仕訳帳、電卓
- 重視点：借方・貸方の概念理解、基本的な仕訳の正確性

【出力形式】
1. 本時の目標（知識・技能・思考力の3観点）
2. 時間配分と学習活動（詳細な流れ）
3. 指導上のポイント（5項目以内）
4. 評価方法（形成的評価・総括的評価）
5. 準備物一覧
```

### 練習問題作成
```markdown
あなたは簿記検定3級の専門家です。
高校1年生向けの仕訳練習問題を10問作成してください。

【条件】
- 難易度：簿記3級基礎レベル
- 内容：現金、当座預金、売掛金、買掛金の基本取引
- 形式：取引内容→仕訳記入
- 時間：20分程度で解答可能

【出力形式】
1. 問題10問（各問80文字以内の取引内容）
2. 解答（正しい仕訳）
3. 解説（各問50文字程度の要点）
4. 指導上の注意点
5. 発展問題への展開例
```

## 🔄 更新・改善

このツールキットは継続的に更新・改善されます。以下の方法で最新情報を確認してください：

- **GitHub Releases**: 新バージョンのリリース情報
- **Issues**: 問題報告や改善提案
- **Discussions**: 活用事例の共有や質問

## 🤝 コントリビューション

このプロジェクトへの貢献を歓迎します：

1. **事例の共有**: 実際の活用事例や成功例の提供
2. **改善提案**: より効果的なプロンプトや新しいテンプレートの提案
3. **問題報告**: バグや不正確な情報の報告
4. **翻訳・多言語化**: 他言語への翻訳協力

### コントリビューション方法
1. このリポジトリをフォーク
2. フィーチャーブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add some amazing feature'`)
4. ブランチにプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

## 📄 ライセンス

このプロジェクトは [Creative Commons Attribution-NonCommercial 4.0 International License](LICENSE.txt) の下でライセンスされています。

### ライセンス概要
- ✅ **利用可能**: 教育目的での自由な使用・改変・共有
- ✅ **改変可能**: 内容の修正・追加・削除
- ✅ **共有可能**: 他の教育機関・教員との共有
- ❌ **商用利用禁止**: 営利目的での使用は禁止
- ⚠️ **帰属表示**: 使用時は適切なクレジット表示が必要

詳細は [LICENSE.txt](LICENSE.txt) をご確認ください。

## ⚠️ 免責事項

- このツールキットの使用は利用者の責任において行ってください
- 生成AIの出力内容は必ず確認・検証してから使用してください
- 教育機関の規則や法令を遵守して使用してください
- 個人情報や機密情報をAIに入力しないよう注意してください

## 🙋‍♀️ サポート・お問い合わせ

### よくある質問
一般的な質問については、まず以下をご確認ください：
- [詳細講義資料のFAQセクション](./detailed_lecture_materials.md#よくある質問faq)
- [GitHub Issues](https://github.com/your-username/CommerceHS-GenAI-toolkit/issues) の既存の質問

### お問い合わせ方法
- **一般的な質問**: [GitHub Discussions](https://github.com/your-username/CommerceHS-GenAI-toolkit/discussions)
- **バグ報告**: [GitHub Issues](https://github.com/your-username/CommerceHS-GenAI-toolkit/issues)
- **プライベートな相談**: リポジトリ管理者への直接連絡

## 🏆 謝辞

このツールキットの開発にあたり、以下の方々・組織に感謝いたします：

- 商業教育に携わる全ての教員の皆様
- 生成AI技術の発展に貢献する研究者・開発者の皆様
- オープンソースコミュニティの皆様

## 📈 統計・実績

- **プロンプト事例数**: 50例以上
- **対応分野**: 4つの商業教育分野
- **サポートツール**: 7つの実践ツール
- **プレゼンテーション**: 4種類のフォーマット対応
- **対象レベル**: 基礎から応用まで
- **セミナー時間**: 90分完全対応

---

**商業教育の未来を、AIとともに創造しましょう。**

*Generated with ❤️ for Commercial High School Education*