
# Python環境の準備


## Anaconda を用いたPython環境の準備

```{warning} 
既にPython環境が整っている場合はこの節はスキップしてください。
```
[https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)
* AnacondaはPythonと主要なライブラリを一括でインストール可能にしたディストリビューション（Jupyter Notebook/Labも含む）です。この授業では、Anacondaを用いた環境構築をお勧めします。他の方法でPythonやJupyter Labが使える状態にある方は、そのままの環境をお使いになることで問題ありません（Python3系を使用してください）。
* [Jupyter Lab](http://jupyter.org/)
    * この授業では主に、Pythonコードをブラウザ上でインタラクティブに実行可能とするJupyterLabを用います。
    * Notebookドキュメントを通して、ブラウザ上でコードの記述と実行結果の保存と共有が可能となります。
    * AnacondaでPython環境を準備する場合は、インストールの必要はありません。AnadondaでJuypter Labも使えるようになります。


```{admonition} WindowsでのPython環境セットアップ

1. [https://www.anaconda.com/distribution/#windows](https://www.anaconda.com/distribution/#windows)から「Python 3.xx version」を選んでインストーラーをダウンロードしてください。
2. インストーラーを起動してインストールを行ってください。Windowsのアプリケーションに「Anaconda Navigator」というアプリケーションがインストールされます。
3. Anaconda Navigatorを起動して「Jupyter Notebook」をLaunchします。もしくは、「Anaconda Command Prompt」を起動して「jupyter lab」とエンターを入力することでも起動できます。
```

```{admonition} MacでのPython環境セットアップ

1. [https://www.anaconda.com/distribution/#macos](https://www.anaconda.com/distribution/#macos)から「Python 3.xx version」を選んでインストーラーをダウンロードしてください。
2. インストーラーを起動してインストールを行ってください。Windowsのアプリケーションに「Anaconda Navigator」というアプリケーションがインストールされます。
3. Anaconda Navigatorを起動して「Jupyter Notebook」をLaunchします。もしくは、「terminal」を起動して「jupyter lab」とエンターを入力することでも起動できます。
```

## Jupyter Labの使い方

1. Anaconda Navigatorを起動して「Jupyter Lab」をLaunch
    * もしくは、Macの場合「terminal」をWindowsの場合「Anaconda Prompt」を起動して「jupyter lab」とエンターを入力することでも起動できます。
2. Notebookを新規作成
    * 任意の場所に授業用のディレクトリを作っておくと良いでしょう。
    * ファイル名やディレクトリ名は英語がベター。スペースの代わりにアンダースコアーなどを使う方が良いです。
3. Jupyter Labの初期画面の左側のパネルからNotebookを作りたい任意の場所へ移動します。
4. `Launcher`の`Notebook`--> `Python 3 (ipykernel)`を選んで新しいNotebookを作ります。
    * Launcherが表示されていない場合は、左上の「＋」マークをクリックしてください。
    <img source="/assets/img/jupyterlab_top.png" width = "70%">
5. 新しいNotebookの名前は編集しておきましょう。
6. Notebookの保存は左上の保存マークをクリックしてください。
7. Jupyter Notebookを終了するには、
    * 左上の「File」--> 「Shut down」を選択するか、
    * Anaconda Navigatorを終了するか、
    * もしくは、Macの場合「terminal」をWindowsの場合「Anaconda Prompt」で「control + c  」とReturn(Enter)を入力すると「Shutdown this notebook server (y/[n])?」と出ます。「y」とReturn(Enter)を入力すると終了できます。

