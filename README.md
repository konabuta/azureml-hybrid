# Hybrid machine learning - Alpha Release
![LICENSE](https://img.shields.io/github/license/konabuta/azureml-hybrid)
![ISSUE](https://img.shields.io/github/issues/konabuta/azureml-hybrid)
![Language](https://img.shields.io/badge/python-3.6-F9DC3E.svg?logo=python&style=flat)
![Language](https://img.shields.io/badge/Azure%20Machine%20Learning-blue.svg?logo=microsoft-azure&style=flat)
![Twitter](https://img.shields.io/twitter/url?style=social)

Azure Machine Learning を利用することで、オンプレミスの計算環境を生かしつつ、クラウドのメリットを享受することができます。

本リポジトリでは、Data Scientist 向けの Workshop コンテンツです。機械学習の実験をオンプレミスで実行し、それをクラウドにも連携しながら、よりスケーラブルな環境へ拡張することを実感頂くことができます。

## 目次

| リソース          | リンク                            |
|-----------------|----------------------------------|
| 事前準備        | - [conda 環境の作成](examples/conda-setup.ipynb)<br/>- [Azure ML 設定](examples/azureml-config.ipynb) |
| ローカル実行        | - [学習スクリプト実行](examples/local-pytorch-run.ipynb) |
| リモート実行        | - [データアップロード](examples/1-data_upload.ipynb)<br/>- [Environment作成](examples/2-environment.ipynb)<br/>- [Azure ML 学習](examples/3-aml-run.ipynb)<br/>- [ハイパーパラメータチューニング](examples/4-hyperdrive.ipynb) |



## 使用しているテクノロジー
- Azure Machine Learning


## 参考情報
- [Azure Machine Learning ドキュメント](https://docs.microsoft.com/ja-JP/azure/machine-learning/)
- [Azure Machine Learning サンプル集 (公式)](https://github.com/Azure/MachineLearningNotebooks)
- [Azure Machine Learning サンプル集 (Communiy)](https://github.com/Azure/azureml-examples)