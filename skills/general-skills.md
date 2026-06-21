# General Skills

AI活用スキル、各種AIサービス、フレームワーク、ライブラリのリンク集。

## Planning / Review（計画の深掘り・ストレステスト）

`/plan` の代わり、または並行して使い、計画をより実効性のあるものにするためのSkill群。共通する考え方は「実装前にプラン・設計・意思決定を徹底的に質問で詰める」こと。

* [dig (ryonakae)](https://github.com/ryonakae/dotfiles/tree/master/config/.agents/skills/dig) - プラン・設計・技術的意思決定について共通理解に達するまで徹底的に質問するSkill。質問は一度に1つずつ・推奨回答付きで提示し、コードベースで分かることは聞かずに調べる。幅より深さを優先して論点を掘り尽くす日本語版。 #skill #planning #review
* [dig (fumiya-kume)](https://github.com/fumiya-kume/claude-code/tree/master/dig) - ※SkillではなくClaude Code用plugin（`/dig` スラッシュコマンド）。実装前にプランの隠れた前提・未検討リスク・暗黙の意思決定を深掘りインタビューで洗い出す。コンテキスト収集→前提マッピング→深掘り調査→プランへ反映→完全性評価の5フェーズ構成で、AskUserQuestionツールを使い高リスクな前提から「広さより深さ」で詰め、決定内容をplanファイルに書き戻す。`/plan` と組み合わせて計画の穴を潰すのに有効。 #claude-code #plugin #planning #review
* [grill-me (mattpocock)](https://www.skills.sh/mattpocock/skills/grill-me) - プランや設計を体系的な質問で容赦なくストレステストするSkill。決定ツリーを枝ごとに辿り、共通理解に達するまで一問ずつ質問する。コード参照可能な点はコードベースを自動探索して無駄な往復を減らす。設計レビュー・アーキテクチャ検証・実装前計画向け。インストール: `npx skills add https://github.com/mattpocock/skills --skill grill-me` #skill #planning #review
