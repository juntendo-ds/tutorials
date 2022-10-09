# プログラミング言語 Python

## Pythonについて

- 現在のデータサイエンスにおいて標準と言って良い
- インデント(字下げ)によって構造を決めるのが大きな特徴
  - 必然的に読みやすいものとなる
- Python 自体の動作速度は速いものとは言えないが，膨大なライブラリを利用することでさまざまな場面において利用されている
  - その典型例は，GPU を用いた機械学習
  - これ以外にも多様な分野のライブラリ/パッケージが作成されている

## Python の勉強方法

- どのようなものかを簡単に知る並ば，クラウドの学習サイトを用いるのが手軽である
  - [paizaラーニング](https://paiza.jp/works) ：Python に限らず，さまざまなプログラミング言語の学習ができる
  - [progate](https://prog-8.com/) ：こちらもさまざまなコンテンツがある
- より詳しく学ぶ並ば，たとえば以下がある
  - [Pythonプログラミング入門(東京大学)](https://sites.google.com/view/ut-python/)
    - 順天堂のアカウントからも利用できる Google Colaboratory を用いて展開されているので，それをそのまま動かすことができる
  - [プログラミング演習 Python 2021(京都大学)](https://repository.kulib.kyoto-u.ac.jp/dspace/handle/2433/265459)
    - こちらはスタンダードな教科書の形態である

## (参考)Jupyter について

- Python を利用するための形態の1つ
- ブラウザからアクセスすることで利用できる
- 「セル」と呼ばれるブロック毎のインタラクティブな実行が可能
  - 文書や画像などを入れることもできる
- Mathematica のような数式処理ソフトのような使い方もできる

## JupyterLite について

- 現時点でJupyterを最も手軽に利用できる方法と言える
- [JupyterLite](https://jupyter.org/try-jupyter)にアクセスすると直ちに利用できるようになる
  - これは，[Pyodide](https://pyodide.org/en/stable/index.html)と呼ばれる，ブラウザ上でコードを実行する仕組みを用いている
- 初期状態で一通りのパッケージは用意されている
  - 用意されていないものも以下のように，`piplite` を用いることで大抵は利用できる

```pytyon
import piplite
await piplite.install('ipywidgets')
```

## Google Colaboratory について

- Google が提供するクラウド環境
- Jupyter とは厳密には異なるが，ほぼ同じであると考えて良い
  - 基本的なパッケージは最初から利用できる上に，自身で追加も可能
- 順天堂のアカウント(`@juntendo.ac.jp`)から無料で利用できる
  - 複数の授業で利用することになるだろう
- GPU も利用できるが，利用制限があるので注意
- 詳細は[Google Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb?hl=ja)を確認のこと

## Anaconda による実行環境導入

- 基本的には Google Colaboratory を利用できるようになれば十分であるが，長時間の計算などをするには別の環境を利用する必要がある
- 自身のPCに Python 実行環境を導入してみても良いだろう
- さまざまな方法があるが，良く分からなければ[Anaconda](https://www.anaconda.com/)と呼ばれるしくみを用いると良いだろう

## GPU の利用について

- 現状で Python にて GPU を用いる場合，NVIDIA製のグラフィックカードを利用することになるだろう
  - CUDA と呼ばれるものを[以下](https://developer.nvidia.com/cuda-toolkit)から入手して設定することになる
- 購入しやすいのは，いわゆるゲーム用の GPU であるが，昨今の状況から値上がりしている
  - GeForce RTX 3090 は 2022年3月現在，30万円程度である
  - 高額な理由は，仮想通貨のマイニングに利用されるためでもある
- アルゴリズムを確認するだけ並ばGPUを用いなかったり，廉価なものでも十分ではある
  - 廉価な GPU の場合，メモリ容量には注意
- 機械学習関連では，以下からGPUを用いることが多い:
  - [TensorFlow(Keras)](https://www.tensorflow.org/)
  - [Pytorch](https://pytorch.org/)

## クラウド環境からのGPUの利用について

- 大学のアカウントから利用できる Google Colaboratory は無償で利用できるが，GPUの利用に制限がある
  - [Google Colab Pro](https://colab.research.google.com/signup) は月額定額であるが，非公開の利用制限が設定されている
- 制限を気にせず用いる並ば，有償のクラウドサービスを用いる選択肢がある．以下が代表的なものとなる
  - [AWS](https://docs.aws.amazon.com/ja_jp/dlami/latest/devguide/gpu.html)
  - [Microsoft Azure](https://docs.microsoft.com/ja-jp/azure/virtual-desktop/configure-vm-gpu)
  - [Google Cloud Platform](https://cloud.google.com/compute/docs/gpus)

## 関連リンク

- [公式サイト](https://www.python.org/)
- [Python.jp プログラミング言語 Python情報サイト](https://www.python.jp/)
