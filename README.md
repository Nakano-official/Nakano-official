情報系の学部生です（2028年3月卒業予定）。
業務システムの自動化、AI に実装を任せる基盤、機械学習の可視化を作っています。

---

### [takeover](https://github.com/Nakano-official/takeover) — 障がい学生支援室の欠員補充システム

自分がノートテイカーとして働く支援室の業務システムです。シフトに欠員が出ると候補者を自動で抽出し、
Google Chat で代行を依頼して、最初に承諾した人で確定させます。個人情報は学内 Google Workspace の中で完結。
要件ヒアリングから設計・実装・職員向けマニュアルまで1人で担当し、**2026年9月28日に本番稼働**しました。

Google Apps Script / Google Workspace（Chat・Sheets）

### [Loop-Engine](https://github.com/Nakano-official/Loop-Engine) — AI に実装を任せるループの実行基盤

定義と設計を深く書けば、実装は弱いモデルでも担える狭い仕事になる、という考えを試す実験です。
定義・設計は Claude、実装はローカルの 9B モデルが担い、テストは設計の入出力例から機械が生成します。
要求から「開けば動く HTML アプリ」が出るところまで通っています（作り直しの途中）。

Python / WSL2

### [Syllabel](https://github.com/ProjectResearch2026/Syllabel) — 履修登録支援 AI チャットボット（チーム開発）

龍谷大学プロジェクトリサーチのチーム開発（学生5名・2026年5月〜）。学年・課程・既修得科目から次学期の時間割を提案し、
シラバスについての質問に答えます。推論は学内サーバのローカル LLM で行い、成績データを学外へ出しません。
私は履修要項を、卒業要件の判定を機械的に計算できる YAML に構造化する部分を担当し、
全6課程 × 4入学年度分（2023〜2026年度入学）を原典・シラバスと照合して作成しました。

Python（FastAPI）/ Next.js / vLLM ・ 担当は `curricula/` のデータとスキーマ

### HATOBA — ハッカソン2位・フロントエンド担当

値引き食材から AI がメニューを提案し、スーパーのイートインを大学生向けの夕食食堂にする提案です。
龍谷大学スマートライフハッカソン（平和堂 × ソフトバンク・2026年）で **2位**。6人チーム。

Next.js / TypeScript / Gemini API ・ [リポジトリ](https://github.com/shimizu-kiichi/HATOBA)

### そのほか

- **[NN-](https://github.com/Nakano-official/NN-)** — ライブラリを使わず JavaScript だけで書いたニューラルネットワークの学習教材。[公開ページ](https://nakano-official.github.io/NN-/)
- **[AIChat](https://github.com/Nakano-official/AIChat)** — ローカルの Ollama を使うチャットと授業ノート要約。会話とノートは外部の LLM に送らず、検索して根拠と照合する調査モードもあります。[デモ](https://nakano-official.github.io/AIChat/)
- **[Pre-Auto-Trade](https://github.com/Nakano-official/Pre-Auto-Trade)** — LLM の判断とリスク管理を分離して検証する自動売買の研究環境。Codex とローカル LLM の判断を、MT5 のデモ口座で比較しています
