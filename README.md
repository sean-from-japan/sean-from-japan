## sean-from-japan

**English** | [日本語](#日本語)

Third-year computer science undergraduate, after a ten-month exchange abroad.

I like problems where the answer has to be argued for, not asserted: search and
optimisation, data and privacy, formal logic, authorisation design, and the small
tools that keep a workflow honest. Most of what I publish is built the same way
— the claim is in the README, the evidence is in the repository, and the tests
run in CI.

### What to look at

Ten public repositories. They came from four different places, so that is how
they are grouped.

#### Football

Two projects that started from watching matches, not from an assignment.

| | |
|---|---|
| **[togakuren-analytics](https://github.com/sean-from-japan/togakuren-analytics)**<br>`Python` | **2,312 university fixtures turned into reproducible analysis.** Player-minutes rebuilt from lineups and free-text substitution times, a forecast scored on seasons its settings never saw, and adjusted plus-minus ratings — none of it redistributing amateur players' data. |
| **[football-setpiece-spotter](https://github.com/sean-from-japan/football-setpiece-spotter)**<br>`Python` | **Corner detection in amateur footage, measured rather than demonstrated.** Every corner found from the dataset's own tracking, 0.43 recall once the positions come from perception built here, and the collapse traced to the one player the heuristic leans on. |

#### Team projects, revisited

Group work I went back to alone, to find out how much of it I could carry myself.

| | |
|---|---|
| **[torcs-racing-controller](https://github.com/sean-from-japan/torcs-racing-controller)**<br>`Python` | **An autonomous racing controller taken from 261.42 s to 106.63 s.** The recovered residual-network weights are published; a pinned-container rerun reached 107.08 s, 1.46 s faster than the CMA-only controller in the same environment. |
| **[two-stage-evacuation-router](https://github.com/sean-from-japan/two-stage-evacuation-router)**<br>`Python` | **Escape routing that optimises the whole route to a shelter, not the nearest exit.** A high-school team project reimplemented as an explainable constrained-routing system. |

#### Tools I built for my own work

Things I needed, so I made them, and then kept using them.

| | |
|---|---|
| **[ZzzMemo](https://github.com/sean-from-japan/ZzzMemo)**<br>`Python` | **The task manager I actually use, self-hosted.** Natural-language capture, LLM sorting with local fallback, calendar sync. |
| **[blog-asset-pipeline](https://github.com/sean-from-japan/blog-asset-pipeline)**<br>`Python` | **A manual delivery workflow turned into a CLI that refuses to ship a broken set.** Dependency-free image inspection, so it runs anywhere. |
| **[evidence-first-travel-planner](https://github.com/sean-from-japan/evidence-first-travel-planner)**<br>`Python` | **Itineraries checked the way code is checked.** Travel-planning practice across roughly fifteen European countries distilled into a deterministic validator for provenance, freshness, time, transfers, conflicts, and fallbacks. |

#### Coursework, rebuilt

Modules I took, redone afterwards without the scaffolding the course provided.

| | |
|---|---|
| **[assessment-system-design-case-study](https://github.com/sean-from-japan/assessment-system-design-case-study)**<br>`Python` | **Reading a system I helped build as an attacker would.** Ten findings with evidence, then a rebuilt authorisation core so they are answered by code, not by prose. |
| **[learning-logic-in-computer-science](https://github.com/sean-from-japan/learning-logic-in-computer-science)**<br>`Python` | **A logic module made executable.** DPLL, resolution, unification and bounded model checking, alongside the record of how I studied it. |
| **[java-programming-retrospective](https://github.com/sean-from-japan/java-programming-retrospective)**<br>`Java` | **First-year coursework rebuilt two semesters later.** Failures reported instead of swallowed, drawing made testable, and an honest record of what I did not know at the time. |

### Currently

Building implementation depth through evidence-first software: sports analytics,
constrained routing, evolutionary computation, security-focused design, and tools
built around real workflows. Interested in software engineering and AI
internships.

Japanese (native) · English (IELTS 6.5)

---

## 日本語

[English](#sean-from-japan) | **日本語**

情報工学を専攻している学部3年です。10ヶ月の交換留学から戻ってきました。

答えを主張するのではなく論証しなければならない問題に関心があります。探索と最適化、データとプライバシー、形式論理、認可の設計、そしてワークフローを正直に保つための小さなツールです。公開しているものはどれも同じ作り方をしています。主張はREADMEに書き、根拠はリポジトリに置き、テストはCIで動かします。

### 見てほしいもの

公開しているのは10本です。生まれた場所が4つに分かれるので、そのまま分けています。

#### サッカー

課題ではなく、試合を見ていて気になったところから始めた2本です。

| | |
|---|---|
| **[togakuren-analytics](https://github.com/sean-from-japan/togakuren-analytics)**<br>`Python` | **大学サッカー2,312試合を再現可能な分析にしたもの**。先発と自由記述の交代時刻から再構成した出場時間、設定が見ていないシーズンで採点した試合予測、調整プラスマイナス評価。いずれもアマチュア選手のデータを再配布しない形 |
| **[football-setpiece-spotter](https://github.com/sean-from-japan/football-setpiece-spotter)**<br>`Python` | **アマチュアの映像からのコーナーキック検出を、デモではなく実測で示したもの**。データセット付属の追跡データからは12本すべてを検出し、自前の認識で作った座標では未見のハーフで再現率0.43まで低下。その落差が判定規則の依存する1人の選手にあることまで特定 |

#### チーム課題を一人で作り直したもの

チームで取り組んだものに一人で戻り、どこまで自分で持てるかを確かめたものです。

| | |
|---|---|
| **[torcs-racing-controller](https://github.com/sean-from-japan/torcs-racing-controller)**<br>`Python` | **自律走行のレーシングコントローラを261.42秒から106.63秒まで短縮**。回収した残差NNの重みを公開し、固定コンテナでも107.08秒を記録。同一環境のCMA-ES単体より1.46秒速いことを確認 |
| **[two-stage-evacuation-router](https://github.com/sean-from-japan/two-stage-evacuation-router)**<br>`Python` | **最も近い出口ではなく、避難所までの経路全体を最適化する避難経路探索**。高校のチーム課題を、説明可能な制約付き経路探索として作り直したもの |

#### 自分の作業のために作ったもの

自分が必要になって作り、そのまま使い続けているものです。

| | |
|---|---|
| **[ZzzMemo](https://github.com/sean-from-japan/ZzzMemo)**<br>`Python` | **実際に自分で使っているタスク管理ツールをセルフホストしたもの**。自然言語での入力、ローカルにフォールバックするLLM分類、カレンダー同期 |
| **[blog-asset-pipeline](https://github.com/sean-from-japan/blog-asset-pipeline)**<br>`Python` | **手作業だった納品フローを、不備のある一式は納品させないCLIにしたもの**。画像検査は依存なしで、どこでも動作 |
| **[evidence-first-travel-planner](https://github.com/sean-from-japan/evidence-first-travel-planner)**<br>`Python` | **旅程をコードと同じように検査するもの**。ヨーロッパ約15ヶ国での旅程作成の経験を決定的な検証器にまとめ、出典、鮮度、時刻、乗り換え、矛盾、代替手段を検査 |

#### 授業を作り直したもの

履修した科目を、講義が用意していた足場を外して後から作り直したものです。

| | |
|---|---|
| **[assessment-system-design-case-study](https://github.com/sean-from-japan/assessment-system-design-case-study)**<br>`Python` | **構築に関わったシステムを攻撃者の視点で読み直したもの**。根拠つきの指摘10件と、それに散文ではなくコードで答えるために作り直した認可の中核 |
| **[learning-logic-in-computer-science](https://github.com/sean-from-japan/learning-logic-in-computer-science)**<br>`Python` | **論理学の科目を実行可能にしたもの**。DPLL、導出、単一化、有界モデル検査と、その科目をどう学んだかの記録 |
| **[java-programming-retrospective](https://github.com/sean-from-japan/java-programming-retrospective)**<br>`Java` | **1年次の課題を2学期後に作り直したもの**。失敗を握り潰さず報告する形にし、描画を検証可能にした記録。当時わかっていなかったこともそのまま記載 |

### 現在

根拠を先に置くソフトウェア開発を通して、実装の力を積み上げています。対象はスポーツ分析、制約付き経路探索、進化計算、セキュリティを意識した設計、そして実際のワークフローに合わせたツールです。ソフトウェアエンジニアリングとAIのインターンに関心があります。

日本語（母語）・英語（IELTS 6.5）
