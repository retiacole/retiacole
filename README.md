<p align="center">
  <img src="assets/room-series-banner-six.png" width="960" alt="船に乗るroomシリーズの6人のキャラクター / The six room-series characters aboard a sailing ship">
</p>

# ブラウザからはじめる、セキュリティの基礎

# Learn cybersecurity fundamentals in your browser.


## 日本語 (ENGLISH FOLLOWS)

セキュリティをこれから学ぶ人に向けて、ブラウザだけで基礎を練習できる教材を作っています。ソフトウェアのインストールや外部サービスへの接続が難しい社内ネットワークなど、制限の多い環境でも学び始められるように、Linuxコマンド、ログ分析、パケットの読解、SOCの調査手順を、一つずつ試せる形にしています。教材のHTMLファイルをあらかじめ入手すれば、JavaScriptを実行できるブラウザで、演習をオフラインで進められます。

Linuxコマンドや調査画面は、基礎を理解するための学習用シミュレーターとして再現しています。実際のOSや各種ツールを完全に再現したものではなく、使えるコマンド、オプション、表示結果、細かな挙動などは、実物と100%同じではありません。まずは操作や考え方に慣れ、実際の環境で学ぶための足がかりとして使ってもらえる教材を目指しています。

### おすすめの学習順

どこから始めるか迷ったら、まずはSOCroom-easyの初級で、ログから時刻やアカウント、処理結果を読み取ってみましょう。Linuxの知識は必要ありません。その後、Linuxroomで検索・集計のためのコマンド操作を学び、より詳しいログ分析や通信の読解、調査と報告へ進みます。

**SOCroom-easy初級 → Linuxroom初級 → SOCroom-easy中級・上級 → Logroom → pcaproom-easy → SOCroom → ThreatHunting-room**

1. **[SOCroom-easy 初級](https://retiacole.github.io/socroom-easy/) — まずログを読む体験から。** 画面上で時刻・アカウント・処理結果などを読み取り、検索や資料の照合、短い報告を練習します。Linuxコマンドを知らなくても始められます。
2. **[Linuxroom 初級](https://retiacole.github.io/linuxroom/) — コマンド操作に慣れる。** ログから何を読み取るかを体験した後で、ファイルの移動・閲覧・検索・集計を練習します。応用編・発展編には、ほかの教材を進めながら戻ってきても大丈夫です。
3. **[SOCroom-easy 中級・上級](https://retiacole.github.io/socroom-easy/) — ログの読解と調査を深める。** 初級で学んだ読み方を土台に、より複雑なログや調査課題に取り組みます。
4. **[Logroom](https://retiacole.github.io/logroom/) — コマンドでログを調べる。** 学んだ操作を使ってログを検索・集計・照合し、何が起きたのかを証拠から考えます。
5. **[pcaproom-easy](https://retiacole.github.io/pcaproom-easy/) — 通信の中身を読む。** パケットの見方と基本的なプロトコルを学び、DNS・TCP・HTTPなどの通信の流れを確かめます。
6. **[SOCroom](https://retiacole.github.io/socroom/) — 調査から判断・報告までつなげる。** 「操作チュートリアル」→「ガイド付き実務演習」→難易度「低」の順に、ログ・資料・担当者への照会を組み合わせた調査に挑戦します。
7. **[ThreatHunting-room](https://retiacole.github.io/threathunting-room/) — 仮説から調査を始める。** 不審な活動の仮説を立て、通常業務や反証と比較しながらログを調べます。分かったことと観測の限界を整理し、次のハントや改善へつなげます。

卒業後の別room案内は「次のおすすめ」として表示します。同じroomの続きや復習を選んでも構いません。各教材・各段階を全問クリアしてから次へ進む必要はありません。Linux操作に慣れている方はLinuxroom初級を省略でき、ネットワークに興味がある方はpcaproom-easyから始めても大丈夫です。Logroomとpcaproom-easyは順番を入れ替えたり、並行して進めたりできます。分からない操作や用語が出てきたら、前の教材やヒントに戻りながら進めてください。

## English

I build browser-based learning tools for people getting started in cybersecurity. The aim is to make the basics accessible even in restricted environments, such as corporate networks where installing software or connecting to external services can be difficult. These tools offer step-by-step practice with Linux commands, log analysis, packet reading, and SOC investigations. Once you have obtained the HTML files, you can complete the exercises offline in a browser that supports JavaScript.

The Linux commands and investigation interfaces are educational simulations. They do not fully reproduce a real operating system or professional tools: supported commands, options, output, and behavior are not 100% identical to their real-world counterparts. The goal is to help you become comfortable with the basic operations and ways of thinking, as a starting point for learning in a real environment.

### Suggested learning order

If you are unsure where to begin, start with the beginner lessons in SOCroom-easy and practice reading timestamps, accounts, and outcomes in logs. No Linux knowledge is required. Then use Linuxroom to learn commands for searching and summarizing data before moving on to deeper log analysis, network traffic, investigations, and reporting.

**SOCroom-easy (beginner) → Linuxroom (beginner) → SOCroom-easy (intermediate and advanced) → Logroom → pcaproom-easy → SOCroom → ThreatHunting-room**

1. **[SOCroom-easy: beginner](https://retiacole.github.io/socroom-easy/) — Start by reading logs.** Read timestamps, accounts, and outcomes on screen, then practice searching, cross-checking reference material, and writing a short report. You can begin without knowing Linux commands.
2. **[Linuxroom: beginner](https://retiacole.github.io/linuxroom/) — Get comfortable with commands.** Once you have tried reading logs, practice navigating files, reading, searching, and summarizing data. You can return to the applied and advanced lessons while working through the other tools.
3. **[SOCroom-easy: intermediate and advanced](https://retiacole.github.io/socroom-easy/) — Develop your log-reading and investigation skills.** Build on the beginner lessons with more complex logs and investigation exercises.
4. **[Logroom](https://retiacole.github.io/logroom/) — Investigate logs with commands.** Use those skills to search, aggregate, and correlate records, and work out what happened from the evidence.
5. **[pcaproom-easy](https://retiacole.github.io/pcaproom-easy/) — Read network traffic.** Learn how to inspect packets and basic protocols, then follow exchanges involving DNS, TCP, and HTTP.
6. **[SOCroom](https://retiacole.github.io/socroom/) — Connect investigation, judgment, and reporting.** Start with the interface tutorial, continue with the guided cases, then try the low-difficulty cases. Combine logs, reference material, and inquiries to relevant staff to support your conclusions.
7. **[ThreatHunting-room](https://retiacole.github.io/threathunting-room/) — Start an investigation from a hypothesis.** Test ideas about suspicious activity against logs, normal business explanations, and counter-evidence. Explain findings and visibility limits, then plan the next hunt or improvement.

After graduation, other rooms are offered as optional recommendations. You can continue or review in the same room. You do not need to finish every exercise or level before moving on. If you already know basic Linux commands, you can skip the beginner lessons in Linuxroom; if networking interests you most, start with pcaproom-easy. Logroom and pcaproom-easy can be taken in either order or alongside each other. Revisit earlier lessons and use the hints whenever you encounter an unfamiliar operation or term.

## セキュリティ学習教材 / Security learning tools

| Repository | 日本語 | English |
| --- | --- | --- |
| [linuxroom](https://github.com/retiacole/linuxroom) | Linuxコマンド入門。基本操作から検索・集計・パイプまで、3段階121課題・49コマンドを練習。日本語・英語対応。<br>[すぐにやってみる](https://retiacole.github.io/linuxroom/) | Learn Linux commands, from file navigation to searching, aggregation, and pipelines. 121 lessons across 3 levels, covering 49 commands. Japanese and English.<br>[Play Now](https://retiacole.github.io/linuxroom/) |
| [socroom-easy](https://github.com/retiacole/socroom-easy) | SOC業務の入門教材。初級・中級・上級の63問で、ログの読み方と調査操作を練習。日本語・英語対応。<br>[すぐにやってみる](https://retiacole.github.io/socroom-easy/) | An introduction to SOC work, with 63 beginner-to-advanced challenges in reading logs and performing investigations. Japanese and English.<br>[Play Now](https://retiacole.github.io/socroom-easy/) |
| [logroom](https://github.com/retiacole/logroom) | Linux風のコマンドでログを調べる演習。本編10ケース・104問に、準備4問と根拠付きの出口演習2本を追加。61コマンドで調査。日本語・英語・タイ語対応。<br>[すぐにやってみる](https://retiacole.github.io/logroom/) | Investigate logs with Linux-style commands. Explore 10 core cases and 104 questions, plus 4 preparation questions and 2 evidence-based exit exercises, using 61 commands. Japanese, English, and Thai.<br>[Play Now](https://retiacole.github.io/logroom/) |
| [pcaproom-easy](https://github.com/retiacole/pcaproom-easy) | Wireshark風の画面で学ぶパケット読解。54演習・101設問を通じて、プロトコルと通信の流れを確認。日本語・英語対応。<br>[すぐにやってみる](https://retiacole.github.io/pcaproom-easy/) | Read packets in a Wireshark-style interface. Explore protocols and traffic flows through 54 lessons and 101 questions. Japanese and English.<br>[Play Now](https://retiacole.github.io/pcaproom-easy/) |
| [socroom](https://github.com/retiacole/socroom) | SOCアナリストの調査を体験。操作チュートリアル、端末隔離の実行確認まで進むガイド付き実務演習6件、難易度別15件を収録。時間制限なし・2件並行の練習も選択可能。<br>[すぐにやってみる](https://retiacole.github.io/socroom/) | Practice SOC analyst investigations with an interface tutorial, 6 guided cases including endpoint isolation and result verification, and 15 cases across 3 difficulty levels. Optional untimed and two-case practice modes.<br>[Play Now](https://retiacole.github.io/socroom/) |
| [threathunting-room](https://github.com/retiacole/threathunting-room) | 仮説から始める脅威ハンティング教材。本編38問と任意の自立調査1件で、証拠・反証・観測不足から次の調査計画まで練習。日本語・英語対応。<br>[すぐにやってみる](https://retiacole.github.io/threathunting-room/) | Practice hypothesis-driven threat hunting across 38 core lessons and an optional independent capstone: assess evidence, counter-evidence, and visibility gaps, then plan the next hunt. Japanese and English.<br>[Play Now](https://retiacole.github.io/threathunting-room/) |

オフライン用HTMLの入手方法は、各リポジトリのREADMEをご覧ください。 / See each repository's README for instructions on obtaining the HTML files for offline use.

## パンフレット / Brochures

6つの教材・おすすめの学習順・オフラインでの始め方を、URL・QRコード付きのA4・2ページにまとめました。

Explore all six learning tools, the suggested learning path, and how to get started offline in a two-page A4 brochure with links and QR codes.

**[日本語版をダウンロード（PDF）](brochures/logroom-series-brochure-ja.pdf?raw=true) · [Download English brochure (PDF)](brochures/logroom-series-brochure-en.pdf?raw=true)**


## その他のプロジェクト / Other projects

| Repository | 日本語 | English |
| --- | --- | --- |
| [hanabi-simulator](https://github.com/retiacole/hanabi-simulator) | ブラウザで楽しむ3D花火シミュレーター。10種類の花火を、重力・空気抵抗・風・煙とともに観察。<br>[すぐにやってみる](https://retiacole.github.io/hanabi-simulator/) | A browser-based 3D fireworks simulator with 10 patterns, gravity, aerodynamic drag, wind, and smoke.<br>[Play Now](https://retiacole.github.io/hanabi-simulator/) |

---

制作にはAI（OpenAI Codex）を活用しています。 / Built with the help of AI (OpenAI Codex).
