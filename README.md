# llm-training-sample

## 概要

軽量モデルを利用した LLM のローカル実行のサンプルリポジトリです。以下のリポジトリを参考に実装しています。

- https://github.com/SO0529/2601_software-design-chap3/tree/main

## 実行環境

Google Colab の GPU 環境を利用することを想定しています。

VSCode に以下の拡張機能を入れることで、ローカルのソースコードを Colab のランタイムで実行できます。

- google.colab

## 利用しているモデル

このリポジトリでは、**SmolLM2-360M** と **Qwen3-0.6B** という 2 つの軽量言語モデルを利用しています。

### 概要比較

| 項目         | SmolLM2-360M         | Qwen3-0.6B           |
| ------------ | -------------------- | -------------------- |
| 提供元       | HuggingFaceTB        | Alibaba Cloud / Qwen |
| パラメータ数 | ~360M                | ~600M                |
| 重点領域     | 軽量実行・低リソース | 応答品質・多言語     |
| 用途         | エッジ/オンデバイス  | 汎用テキスト生成     |

### 参考リンク

- Hugging Face: SmolLM2-360M — https://huggingface.co/HuggingFaceTB/SmolLM2-360M :contentReference[oaicite:8]{index=8}
- Hugging Face: Qwen3-0.6B — https://huggingface.co/Qwen/Qwen3-0.6B :contentReference[oaicite:9]{index=9}
