# 線画着色 Inpaint

## 概要

このプロジェクトは、`diffusers`ライブラリを使用して、手描きの線画に自動で色を付けるモデルを実装したものです。

**特徴：**
- Stable Diffusion + ControlNetの構成を使用
- 線画の情報を壊さずに着色を行う
- 自分で描いた線画に色を付けることが可能
- Google Colab上で完結（環境構築不要）

## 技術スタック

- **diffusers**: Hugging Faceのdiffusersライブラリ
- **Stable Diffusion**: 画像生成モデル
- **ControlNet**: 線画などの構造情報を保持しながら画像生成を制御

## 使用方法

1. `inpaint.ipynb`をGoogle Colabで開く
2. 線画画像を準備する
3. ノートブックのセルを順番に実行する
4. 着色された画像が生成されます

画像を入力すると、塗られた状態の画像が返ってくるシンプルな構成です。

## プロジェクト構成

```
part2/
├── README.md           # このファイル
└── inpaint.ipynb       # メインの実装ノートブック（Colab用）
```

## 参考資料

- [diffusers ドキュメント](https://huggingface.co/docs/diffusers)
- [ControlNet ドキュメント](https://huggingface.co/docs/diffusers/using-diffusers/controlnet)

## Qiita記事

開発の詳細や実装方法については、Qiitaに記事を公開予定です。
