---
title: "GitHubPagesとかCircleCiとか"
date: 2017-10-19T18:26:36+09:00
draft: true
---
# GitHubPagesで公開
`ユーザ名.github.io` という名前のリポジトリを作ると、`https://ユーザ名.github.io` でアクセスできるようになる。
今回の場合だと、`plus4hiwaka.github.io` になりますね。

これをしないと、`https://ユーザ名.github.io/リポジトリ名` になってしまうんだなぁ。
つまり、`https://plus4hiwaka.github.io/pwa-study/` みたいな感じになるです。

---
# CircleCiってやつがあるらしい
無料から使えるCIサービスだそうで。GitHubへのPushを検知して色々やってくれるらしい。

こいつを活用して、作成用のリポジトリと公開用のリポジトリを分け、作成用にPushしたらジェネレートして公開用にPush、ということができるらしい。
