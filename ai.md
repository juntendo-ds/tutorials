# 対話型AIについて

授業資料を抜粋して掲載することにする．

## 現在主流である対話型AIの原理

- 与えられた文字列に「それらしい」文字列を生成する仕組み
  - 対話型AIでは，相手の発言に対して適切な返答をするのが基本
- AIが内容の正しさを判断しているわけではない
- 訓練情報から，似た状況では適切に返答することが期待できるが...
  - 単に計算をしているだけで，過去を思い出しているわけではない
- 以上の話は，最新の仕組みはその限りではない
  - 公開されていない新技術があるかもしれない

## 現状のサービス

- 代表的な以下を紹介する
  - [ChatGPT](https://chatgpt.com/)
  - [Microsoft Copilot](https://copilot.microsoft.com/)
  - [Google Gemini](https://gemini.google.com/)

### ChatGPT

- [OpenAI](https://openai.com/)により提供
- [以下](https://chat.openai.com/)にアカウント登録することで以下から無料で利用可能
  - 登録なしでも利用できるが履歴など参照不可
- 無料では制約がある
  - 最新モデル(GPT-4o)の利用が限られている
- 制約を外すには有償プラン($20/月)に入る必要がある
  - 有料でしか利用できない機能もある(音声対応やコード作成など)
- APIという仕組みを用いることで，自身で対話ソフトを作成可能
  - 利用料金がかかることに注意

### Microsoft Copilot

- [以下](https://copilot.microsoft.com/)から利用可能
- Microsoft社が提供している
  - [Microsoft Edge](https://www.microsoft.com/ja-jp/edge) でサインインすることで利用可能
- 以前は手放しで推奨できていたのだが，*最近大きな変更があった*
  - 無料プランでは **多くの機能が利用可能できなくなった** ([参考](https://reinforz.co.jp/bizmedia/60823/))
- 現状では推奨できない．今後どうなるかは不明である
  - こういった突然の変更が起こりうることは意識しておくべき

### Google Gemini

- [以下](https://gemini.google.com)から利用可能
- 今回紹介する中では一番新しく発表された
  - 仕組みの詳細は公開されていないが，他と同様に機能する
- Google の個人アカウントがあれば利用できる
- Google のサービスには生成AIを用いたものが他にもある
  - Colaboratoryにおける[コーディング支援](https://blog.google/technology/developers/google-colab-ai-coding-features/)
  - [NotebookLM](http://notebooklm.google.com)による指定した資料との連携
    - RAG(Retrieval Augmented Generation)の一種と言える

### 実際の利用について

- 同じ内容でも質問の方法によって回答の質は変わりうる
- 適切な質問文を作成する理論は *prompt engineering* と呼ばれる
  - これは対話に限定しない指定手法として扱われている
- [以下](https://www.promptingguide.ai/jp)や[以下](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)は参考になるかもしれない(後で扱う予定)
- その他，具体的なTips については色々知られているようである
  - [敬語によるChatGPTの驚くべき変化！](https://chatgpt-lab.com/n/nd8dde92016ec)
  - [ChatGPTを賢くする呪文](https://www.nikkei.com/article/DGXZQOUC22BVO0S3A320C2000000/)
  - [あなたの仕事が劇的に変わる!? チャットAI使いこなし最前線](https://logmi.jp/business/articles/328359)

## 参考資料

- 具体的な用途に対して実際に使うのが一番と思われる
- Web上で提供されている学習コースを受講しても良いだろう
  - [Introduction to Large Language Models](https://www.cloudskillsboost.google/paths/118/course_templates/536?locale=ja)：前半部だけでも有用
  - [Generative AI for Educators](https://grow.google/ai-for-educators/)：実用に関するものが中心
  - [Microsoft Learn](https://learn.microsoft.com/ja-jp/) にも色々なコースがある
    - 開発者向けにものが多い印象である
    - 教育関係のもの(学生/教師用)は概要を把握するには良いだろう
