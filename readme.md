# LexiForge

**受験英語を「構造と音」で攻略する、インタラクティブ英語総合学習スタジオ**

`LexiForge` は、高校受験・大学受験・英検（2級・準1級）に対応したブラウザ完結型の英語学習Webアプリです。単一のHTMLファイル（`index.html`）で構成されており、GitHub Pagesへアップロードするだけで自分の専用URLからすぐに起動できます。

## Live Demo（GitHub Pages）

https://jkj7vv2nd7-lang.github.io/lexiforge/ 

---

## 収録コンテンツ（計99問 ＋ SVOC長文9本）

- **高校受験コース**: 語順パズル 10問 / 文脈語彙・文法 10問 / 音声ディクテーション 8問 / SVOC長文 3本
- **大学受験コース**: 語順パズル 12問 / 文脈語彙・言い換え 12問 / 音声ディクテーション 8問 / SVOC長文 3本
- **英検（2級・準1級）コース**: 語順パズル 10問 / 大問1対策語彙 12問 / 音声ディクテーション 8問 / SVOC長文 3本

---

## 主な機能

1. **Syntax Forge（語順パズル）**: 分詞構文・仮定法・倒置・関係詞などの重要構文をブロック組み立てで体得。
2. **Context Cloze（文脈穴埋め）**: 言い換えや文脈推測を重視した入試・英検直結の4択演習。
3. **Echo Dictation（音声ディクテーション）**: ブラウザ標準の `speechSynthesis`（0.8x / 1.0x / 1.2x）を聴いてスペル入力。
4. **SVOC Chunk Reader（構造スラッシュ読解）**: S・V・O・C・M の色分けとチャンク訳のON/OFFを切り替えて返り読みゼロの読解力を養成。
5. **忘却曲線（SRS）弱点復習 & 継続設計**: 間違えた問題の自動ストック、デイリー3クエスト、XP・コンボ、3分集中スプリントタイマーを搭載（`localStorage` 保存対応）。

---

## GitHub Pages での公開方法

1. GitHubで新しい公開リポジトリ（例：`lexiforge`）を作成します。
2. ダウンロードした `lexiforge_index.html` を **`index.html`** にリネームし、`lexiforge_README.md` を **`README.md`** にリネームしてリポジトリのルートにアップロードします。
3. リポジトリの **Settings → Pages** を開き、Sourceを `Deploy from a branch`、Branchを `main` / `/ (root)` に設定して **Save** をクリックします。
4. 数分後に発行される `https://<ユーザー名>.github.io/<リポジトリ名>/` からいつでも利用できます。
