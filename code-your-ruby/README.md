# Code Your Ruby

Code Your Ruby is a workspace to practice Ruby with code reviewing each other.

# For non-Japanese Developers
Because owner of CodeYourRuby repository is Japanese, all resources here are written in Japanese. See the post below (post to dev.to) if you are interested in this repository.

[How Do You Teach Yourself After Reading Books for Beginners?](https://dev.to/chooyan/how-do-you-teach-yourself-after-reading-books-for-beginners-2din)

The basic idea of CodeYourRuby is introduced in the post above.

# これは何？

Code Your Rubyは、Ruby初級者がコードレビューを通してRubyの書き方や考え方を学ぶためのリポジトリです。  

出題の内容を実装してこのリポジトリへプルリクを送り、それを他のRubyエンジニアがレビューすることで、自分ひとりでの勉強では得られない視点や技術を身に着けることができます。  

「Rubyを仕事にしたくて本やネットで勉強してみたけど、本当にこの書き方で良いのか不安！」という方はぜひ「参加手順」を一読して参加してみてください！

# 参加手順

大まかには、このリポジトリをForkしてお題に沿ったプログラムを実装してmasterブランチにプルリクを投げる、という流れで進みます。

細かなステップは以下の通りです。

1. このリポジトリをForkします。
1. ForkしたリポジトリをローカルにCloneします。
1. `specification`ディレクトリの問題を確認します。どの問題からトライしても大丈夫です。
1. `user`ディレクトリに自分のGitHubアカウント名でディレクトリを作成します。これが作業ディレクトリになります。
1. 作業ディレクトリに、課題の実装コードを配置する`lib`ディレクトリとテストコードを配置する`test`ディレクトリを作成します。
1. 課題の仕様を満たす実装コードとそのテストコードを書きます。
1. 「これで書けた！」と思ったら`user`ディレクトリ以下をコミット＆Pushし、このリポジトリのmasterブランチにPull Requestしてください。

# レビュー手順

「誰が」「いつまでに」「どのような形式で」のようなルールは特にありません。

提出されているプルリクに対して何かコメントのある方はどんどんコメントを追加してください！

ただし、あくまで目的は __参加者の学習__ であることを忘れずに、建設的な議論を意識してください。「微妙、、、」みたいなのはナシです。

# マージについて

プルリクが提出され、コメントのやりとりが落ち着いたと [@chooyan-eng](https://github.com/chooyan-eng) が判断した時点でそのプルリクをマージします。  

最終的なコードの質は特に見ません（見れません）。また、マージすることが目的でもありませんので、マージに関するルールは特にありません。    

マージ後の修正や別の問題へのチャレンジは再度プルリクを提出してください。

# ディレクトリ構成

例えば`@chooyan-eng`がfizz_buzz問題にチャレンジする場合、ディレクトリ構成は以下のようになります。

```
$ tree
.
├── README.md
├── specification
│   └── fizz_buzz.txt
└── user
    └── chooyan-eng
        ├── lib
        │   └── fizz_buzz.rb
        └── test
            └── fizz_buzz_test.rb
```

ただし、`lib`と`test`以下のディレクトリ構成は自由です。  
言い換えると、ディレクトリの切り方もレビュー対象になり得ます。いろいろ考えてみましょう。

# その他

* 問題は随時追加 / 更新予定です。
* このリポジトリのForkや再利用は自由です。同じような取り組みをもっと狭いチーム内でやってみたい、他の言語でやってみたいなどありましたらご自由にアレンジしてください。

Code Your Rubyを作ったきっかけなどをQiitaで記事にしました。併せてご覧ください。  
[これからRubyで仕事したい人のためのリポジトリ「Code Your Ruby」を作りました | Qiita](https://qiita.com/chooyan_eng/items/46f5724202f90ab4004d)



ご意見などがありましたら、[Issues](https://github.com/chooyan-eng/code-your-ruby/issues) か [@chooyan_i18n](https://www.twitter.com/chooyan_i18n)（twitter）までご連絡ください。
