# azureml-hybrid
hybrid machine learning on Azure Machine Learning

環境作成 : `prerequisite.ipynb`
- 自分の PC に conda 環境を作成
- Azure ML Workspace の config を保存

ローカル実行 : `local-pytorch-run.ipynb`
- 学習スクリプトを実行 


リモート実行
- データアップロード : `1-data_upload.ipynb`
- 環境作成 : `2-environment.ipynb`
- Azure ML 学習 : `3-aml-run.ipynb`
- ハイパーパラメータチューニング : `4-hyperdrive.ipynb`