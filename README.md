# Hybrid machine learning - Alpha Release
![LICENSE](https://img.shields.io/github/license/konabuta/azureml-hybrid)
![ISSUE](https://img.shields.io/github/issues/konabuta/azureml-hybrid)
![Language](https://img.shields.io/badge/python-3.6-F9DC3E.svg?logo=python&style=flat)
![Language](https://img.shields.io/badge/Azure%20Machine%20Learning-blue.svg?logo=microsoft-azure&style=flat)

Azure Machine Learning を利用することで、オンプレミスの計算環境を生かしつつ、クラウドのメリットを享受することができます。

本リポジトリでは、Data Scientist 向けの Workshop コンテンツです。機械学習の実験をオンプレミスで実行し、それをクラウドにも連携しながら、よりスケーラブルな環境へ拡張することを実感頂くことができます。

## 目次

| リソース          | リンク                            |
|-----------------|----------------------------------|
| 事前準備        | - [conda 環境の作成](examples/conda-setup.ipynb)<br/>- [Azure ML 設定](examples/azureml-config.ipynb) |
| ローカル実行        | - [学習スクリプト実行](examples/local-pytorch-run.ipynb) |
| リモート実行        | - [データアップロード](examples/1-data_upload.ipynb)<br/>- [Environment作成](examples/2-environment.ipynb)<br/>- [Azure ML 学習](examples/3-aml-run.ipynb)<br/>- [ハイパーパラメータチューニング](examples/4-hyperdrive.ipynb)<br/>- [機械学習パイプライン](examples/5-aml-pipeline.ipynb)|


## 使用しているテクノロジー
- Azure Machine Learning
- Visual Studio Code (coming soon)
- WSL (coming soon)

## ハイブリッド環境のユースケース

Azure Machine Learning はクラウドベースの機械学習プラットフォームですが、オンプレミス環境の資産を活用することができます。例えば以下のようなシナリオでご利用になれます。

- 実験管理
    - オンプレミス環境での試行錯誤する機械学習の実験で取得されたメトリック、成果物、ログ、ソースコード (Git) を記録する。
- モデル学習の高速化
    - Windows 端末の Visual Studio Code において Remote Docker (Linux) on WSL2 を利用してモデル学習を行い、スムーズに Azure Machine Learning の Compoute Cluster 上でモデル学習を行う。
- 推論環境のhex 
    - コンテナベースの推論環境をクラウドにデプロイする前に、オンプレミス環境でクイックに推論環境を立ち上げ、クラウドに展開する前の確認を行う。


## 技術要素
### Azure Machine Learning
- Experiment
    - モデル学習の実験履歴を管理
- Dataset
    - 表形式・ファイル形式のデータセットのメタ情報を管理
- Environment
    - Python のパッケージ、Dockerイメージの情報を管理
- Compute Cluster
    - スケーラブルな計算クラスター環境
- Compute Instances
    - クラウドでホストするノートブック環境

### その他
- Visual Studio Code
    - Microsoft が提供するフリーのプログラム開発環境
- WSL (Windows Subsystem Linux)
    - Windows 上の Linux (Ubuntu) 環境


## 参考情報
- [Azure Machine Learning ドキュメント](https://docs.microsoft.com/ja-JP/azure/machine-learning/)
- [Azure Machine Learning サンプル集 (公式)](https://github.com/Azure/MachineLearningNotebooks)
- [Azure Machine Learning サンプル集 (Communiy)](https://github.com/Azure/azureml-examples)