# senshuQmdWord

これは専修大学の心理学科の卒論・修論用のQuartoテンプレートになります。Qmd形式で卒論を書いて，Wordで出力できます。

## 新規作成

TerminalやPowerShellで以下のコマンドを打ち込んでもらえると利用できます。

```bash
quarto use template ykunisato/senshuQmdWord
```

なお，[psyinfr](https://github.com/ykunisato/psyinfr)を利用されている場合は，Rコンソール上でset_rc()を実行すると追加されます。

## 既存のプロジェクトへの追加

既に存在するQuartoプロジェクトに追加する場合は，以下のコマンドを打ち込みます。

```bash
quarto add ykunisato/senshuQmdWord
```

## 使用法

paper_word.qmdファイルを開いて，自分の卒論・修論の内容を書き込んで，'Render'をクリックしてください。Wordファイルが出力されます。

## 使用上の注意

- なぜかタイトル・氏名の直後に目次が挿入されています。そのため，(1)Word出力後にタイトル・氏名の後ろで改ページする。(2)目次の後ろの本文でセクションを分けて，そこからページ番号がスタートするようにする，(3)目次を更新するなどの作業が必要です。

- 引用文献リストで日本語文献と英語文献が分かれて出力されますので，手作業で修正ください。

- このテンプレートは，専修大学の国里愛彦が個人的に作成しているものです。心理学科として品質保証するものではないので，卒業論文・修士論文の手びきをご自身で確認をした上で利用ください。



