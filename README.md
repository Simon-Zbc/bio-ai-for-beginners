# bio-ai-for-beginners

**エンジニアのためのバイオAI入門** ― 論文を読み、Colab で動かす

生物の専門知識がないソフトウェアエンジニアが、最先端のバイオAI（タンパク質の構造予測・設計から創薬、LLM エージェントまで）を理論と実践の両面から学ぶための連載です。Qiita に投稿している記事の原稿と、各章のハンズオン用ノートブックをまとめています。

- 数式の厳密な導出は最小限にし、**論文の要点を理解してコードを動かす**ことを重視しています
- 生物の知識は高校レベルを前提に、必要な分だけ説明します
- ノートブックはすべて **Google Colab の無料枠**で動作することを目標にしています

## 目次

| # | 記事 | ノートブック |
|---|---|---|
| 00 | [はじめに ― なぜ今学ぶのか、何を学ぶのか](articles/00_はじめに.md) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Simon-Zbc/bio-ai-for-beginners/blob/main/notebooks/00_first_look_at_protein.ipynb) |
| 01 | セントラルドグマ | 準備中 |
| 02 | タンパク質の構造と機能 | 準備中 |
| 03 | バイオデータとツール | 準備中 |
| 04 | タンパク質言語モデル | 準備中 |
| 05 | AlphaFold2 の仕組み | 準備中 |
| 06 | AlphaFold3 と共折りたたみモデル | 準備中 |
| 07 | GAN から拡散モデル・Flow Matching へ | 準備中 |
| 08 | タンパク質デザイン | 準備中 |
| 09 | バインダー設計の最前線 | 準備中 |
| 10 | マルチモーダル生成モデル | 準備中 |
| 11 | 分子表現と GNN | 準備中 |
| 12 | ドッキングと結合予測 | 準備中 |
| 13 | 分子生成 | 準備中 |
| 14 | バイオ RAG | 準備中 |
| 15 | バイオAI エージェント | 準備中 |
| 16 | 総合ハンズオン | 準備中 |
| 17 | 倫理と展望 | 準備中 |

## リポジトリ構成

```
bio-ai-for-beginners/
├── articles/    # Qiita 記事の原稿（Markdown、章ごとに1ファイル）
├── notebooks/   # 各章のハンズオン用 Colab ノートブック
├── LICENSE
└── README.md
```

## 使い方

1. 目次の「Open in Colab」ボタンからノートブックを開きます
2. GPU が必要な章では、「ランタイム」→「ランタイムのタイプを変更」→「T4 GPU」を選びます
3. 上のセルから順に実行します

## ライセンス

- ソースコード（`notebooks/` など）：[MIT License](LICENSE)
- 記事（`articles/`）：[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja)

各章で使う外部のモデルやデータには、それぞれのライセンスが適用されます（例：AlphaFold3 のモデル重みは非商用利用に限られます）。利用する前に、各プロジェクトのライセンスを確認してください。
