# プログラミング言語 Python

## Pythonについて

- 現在のデータサイエンスにおいて標準と言って良い
- インデント(字下げ)によって構造を決めるのが大きな特徴
  - 必然的に読みやすいものとなる
- Python 自体の動作速度は速いものではないが，膨大なライブラリを利用することで様々な場面で利用されている．
  - その典型例は，GPU を用いた機械学習
  - これ以外にも多様な分野のライブラリ/パッケージが作成されている．

## Python の勉強方法

- どのようなものかを簡単に知るならば，クラウドの学習サイトを用いるのが手軽である．
  - [paizaラーニング](https://paiza.jp/works) ：Python に限らず，様々なプログラミング言語の学習ができる．
  - [progate](https://prog-8.com/) ：こちらも様々なコンテンツがある
- より詳しく学ぶならば，例えば以下がある
  - [Pythonプログラミング入門(東京大学)](https://sites.google.com/view/ut-python/)
    - 順天堂のアカウントからも利用できる Google Colaboratory を用いて展開されているので，それをそのまま動かすことができる．
  - [プログラミング演習 Python 2021(京都大学)](https://repository.kulib.kyoto-u.ac.jp/dspace/handle/2433/265459)
    - こちらはスタンダードな教科書の形態である

## (参考)Jupyter について

- Python を利用するための形態の1つ
- Webブラウザからアクセスすることで利用できる
- 「セル」と呼ばれるブロック毎のインタラクティブな実行が可能
  - 文書や画像などを入れることもできる
- Mathematica のような数式処理ソフトのような使い方もできる

## Google Colaboratory について

- Google が提供するクラウド環境
- Jupyter とは厳密には異なるが，ほぼ同じであると考えて良い
  - 基本的なパッケージは最初から利用できる上に，自身で追加も可能
- 順天堂のアカウント(`@juntendo.ac.jp`)から無料で利用できる
  - 複数の授業で利用することになるだろう
- GPU も利用できるが，利用制限があるので注意
- 詳細は[Google Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb?hl=ja)を確認のこと

## Anaconda による実行環境導入

- 基本的には Google Colaboratory を利用できるようになれば十分であるが，長時間の計算などをするには別の環境を利用する必要がある．
- 自身のPCに Python 実行環境を導入してみても良いだろう．
- 様々な方法があるが，良く分からなければ[Anaconda](https://www.anaconda.com/)と呼ばれる仕組みを用いると良いだろう．

## GPU の利用について

- 現状で Python にて GPU を用いる場合，NVIDIA製のグラフィックカードを利用することになるだろう．
- 機械学習関連では，以下からGPUを用いることが多い:
  - Tensorflow(Keras)
  - Pytorch

## 関連リンク

- [公式サイト](https://www.python.org/)
- [Python.jp プログラミング言語 Python情報サイト](https://www.python.jp/)
