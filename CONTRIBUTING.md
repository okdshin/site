#cpprefjpへのコントリビュート方法
本リポジトリは、C++の日本語リファレンスサイト[cpprefjp](http://cpprefjp.github.io/)のコンテンツを扱っています。私たちは、本サイトを一緒にに編集していただける方を歓迎いたします。

ここでは、本サイトおよびそのMarkdownテキストを扱う本リポジトリを編集するにあたってのガイドラインをまとめます。

##できる限り全てのコンテンツにひとつ以上のサンプルコードを付ける
本サイトが提供するコンテンツは、全ての関数、全てのクラスにひとつ以上のサンプルコードを提供することを目標としています。これによって、ユーザーがその機能をどのように使えばよいのかの道を示せるようにし、その機能をどのような用途で使えるかを示せるようにします。


##正確なものに不要な情報はない
本サイトが提供するコンテンツは、編集者間での合意がとれるものである限りにおいて、「提供しなくてよい情報」というものはないと考えています。情報を書きすぎてはいけないということはありませんので、情報不足と思われる場所を見つけたら、現在の本サイトのスコープに収まる限りは追記していただいてかまいません。

スコープを超えるコンテンツを提供したい場合には、pull requestかissueを発行して、合意をとってください。


##本サイトは翻訳サイトではない
本サイトは、C++の規格書や他のリファレンスサイトの翻訳を提供するサイトではありません。本サイトのコンテンツは、仕様を理解した編集者が自分たちなりの言葉でC++機能の解説を書き、提供します。


##ほかの人が書いたコンテンツの編集方法
本サイトには、多くの方がコンテンツを提供しています。そのため、ほかの人が書いたコンテンツを編集することも少なくありません。編集者間での考え方の違いによるトラブルを防止するために、ほかの人が書いたコンテンツを編集する際は、以下のフローで修正の仕方を検討していただければと思います：

1. 修正方針がわからない・複数考えられるが決めかねるようならissueを作って確認をとる
2. 修正はできるが、修正内容について修正者以外の合意・確認が必要そうならpull requestを作る
3. 元の記事を書いた人に伝えておきたいだけなら、事前にコメントを飛ばしたうえで直接修正する
4. 1.〜3.のようなことが何もなければ直接修正してかまわない。ただし、修正の理由や根拠は、修正内容かコミットメッセージのどちらかでフォローしておいたほうがよい

なお、「ほかの人が書いたコンテンツ」には、本サイトの方針も含まれます。方針の改訂を提案する場合にも、上記フローでお願いします。


##本サイトのスコープを超えるコンテンツを書くには
本サイトでは多くのコンテンツを提供していますが、考えられる限り全ての情報を記載しているわけではありません。現在の本サイトが提供している範囲を超えるコンテンツを提供したい場合には、issueもしくはpull requestを作って合意をとってください。


##困ったことがあったらissueで相談
本サイトの編集にあたって、編集者間の相談にはissueを使用してください。編集者間で直接やりとりしていただいてもかまいませんが、本サイトの記録として残したほうがよいやりとりであると判断した場合には、そのやりとりを本リポジトリのissueに貼り付けたり、リンクを貼ったりしていただければと思います。

ただし、編集者間の合意が必要あるものは、編集者間の直接のやりとりではなく、必ず本リポジトリのissueかpull requestで相談してください。オープンに議論できるものについては、管理者も同様です。


##本サイトのタスクを確認するには
本サイトで書くことが決まっているタスクを確認するには、issueを参照してください。「TASK」ラベルが付いているもので、担当者がついていないものがあれば、ぜひとも引き取ってください。


##push権限を持っていない人向け
push権限を持っていない方は、pull requestで何らかの編集を行うところからはじめてください。タスクを引き取っていただける場合には、タスクのissueに「やります」とコメントを書いていただければ、担当をお渡しします。

管理者からpush権限をお渡しする申請が届いた場合には、引き受けていただけると幸いです。
