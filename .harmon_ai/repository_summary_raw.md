## mergekit-evolve

[![Docker Build](https://github.com/YOUR_USERNAME/mergekit-evolve/actions/workflows/docker-build.yml/badge.svg)](https://github.com/YOUR_USERNAME/mergekit-evolve/actions/workflows/docker-build.yml)

### Sakana.aiの革新的なモデル統合手法「Evolutionary Model Merging」をDocker Composeで手軽に利用できるリポジトリです。

約1ヶ月前、Sakana.aiが発表したEvolutionary Model Mergingに関する論文と、その後のモデルと評価結果は、画期的な統合手法として大きな話題を呼びました。しかし、コミュニティにとって残念なことに、彼らはその驚異的な結果をもたらしたアルゴリズムを公開しませんでした。

Arceeでは、この発表以来、コミュニティのためにこの画期的な技術を開発することに全力を注いできました。そして今、MergeKitでこの最先端の機能をリリースできることを嬉しく思います。

Evolutionary Model Mergingにより、マージにおいて特定の能力や特性をターゲットにすることができます。これがなければ、モデルのマージは、何十ものマージを試行し、手動で評価し、マージパラメータと最終モデルのパフォーマンスの関係を説明するメンタルフレームワークを考え出すという、非常に手探りで探索的なプロセスになります。Evolutionary Model Mergingを使用すると、代わりにモデルに求める特性を指定することができ、最適化は私たちに代わって行ってくれます。

### 特徴

- Docker Composeで簡単に環境構築が可能
- mergekit-evolveの最新バージョンを常に利用可能
- シンプルな設定で、すぐに使い始めることができます

### インストール

1. このリポジトリをクローンします。
2. `.env` ファイルを編集し、必要に応じて環境変数を設定します。
3. `docker-compose up -d` コマンドを実行します。

### 使用方法

詳細な使用方法については、[MergeKitのドキュメント](https://www.mergekit.ai/docs) を参照してください。

### ライセンス

このリポジトリは、[MIT License](LICENSE) の下でライセンスされています。

### 免責事項

このリポジトリは、Sakana.aiまたはArceeとは一切関係ありません。