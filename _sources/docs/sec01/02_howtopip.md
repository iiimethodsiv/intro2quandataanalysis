# 必要なパッケージ

## パッケージのインストール方法

### requirements.txtを用いたインストール（推奨）
このWebsite補助教材で必要なPythonのパッケージを一括でインストールするには、<a href="https://www.yuyashibuya.com/assets/data/requirements.txt">requirements.txt</a>をPCにダウンロードし、Terminal（mac）やAnaconda Prompt（win）で`requirements.txt`が保存されている場所に移動した後、次のコマンドを実行すると必要なパッケージをダウンロードすることができます。

```sh
pip install -r requirements.txt
```

### 必要なパッケージなどをインストール
Terminal（mac）やAnaconda Prompt（win）でダウンロードした場所に移動し、インストールしたいパッケージ名（例：`statsmodels`）をに置き換えて以下のコマンドを実行すると必要なパッケージをダウンロードすることができます。

```sh
pip install statsmodels
```

もしくは、すでにJupyter Labを開いている場合は、Notebookのセルで次のコマンドを実行してもダウンロードすることができます。

```sh
!pip install statsmodels
```

## envを用いた仮想環境の管理

様々なパッケージを用いると、それぞれのバージョンの依存関係などが複雑化してしまい、意図しないエラーが生じしたりすることもあります。そのため、プロジェクトごとなどで独立した環境を作成し、それぞれの環境下で作業することをおすすめします。`venv`を用いて簡単に環境構築ができます。詳しくは、[こちらのドキュメント](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment)を読んでください。

```{note}
追記予定
```