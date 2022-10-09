# その他

## 入れておくと便利である(かもしれない)ソフトウェア

- [Visual Studio Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
現在世界で最も人気があるエディタ．様々なプラグインが利用でき，Gitとの連携も容易である．
- [textlint](https://textlint.github.io/)：文書校正ツール．日本語文書に対応している．カスタマイズをすることで柔軟な設定が可能となる．Visual Studio Code で利用できるが，少しばかり手間がかかるので，[テキスト校正くん](https://marketplace.visualstudio.com/items?itemName=ICS.japanese-proofreading)を用いるのが手軽である．なお，企業でも利用されており，例えば，[以下](https://zenn.dev/kgsi/articles/a88273d293abe07c5acb)で確認できる
- [Kite](https://www.kite.com/)：コード補完するツール
- [Docker](https://www.docker.com/)：仮想化環境．コンテナと呼ばれる単位で構築されており，様々なサービスを手軽に利用できる
- [Tableau](https://www.tableau.com/)：分析ソフトウェア．有料であるが学生を対象とする[無料ライセンス](https://www.tableau.com/academic/students)が存在する

## 知っておくと便利である(かもしれない)こと

### Markdownの記載

ひとまず[ここ](https://www.markdown.jp/syntax/)にあるものを確認すれば十分である．

### lint の導入/カスタマイズ

校正ツールは Markdown, Python など特定の言語により記載されたコードの他，日本語自体の校正も可能となる．Visual Studio Code には上も触れた[テキスト校正くん](https://marketplace.visualstudio.com/items?itemName=ICS.japanese-proofreading)を始め様々な機能をプラグインとして実現できる．

### [GitHub Copilot](https://copilot.github.com)の利用

AIによりコードを半自動的に記載させる仕組みである．例えば，関数の名前を記載するとそれに従ったコードを自動生成する，といったことが可能である．利用には登録が必要である．

### LaTeX形式の数式記法

$\LaTeX$ は組版システムの1つであるが，ここで用いられる数式を指定する手法がMarkdownでも利用できる．最近はGitHubのMarkdownでも利用できるようになった([参考](https://github.blog/2022-05-19-math-support-in-markdown/))．
