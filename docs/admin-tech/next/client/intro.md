---
sidebar_position: 0
---

# クライアントとはどこまでを指すか

ナポアンのマイクラNEXTは、ナポクラで初の**サーバーレス形式**での公開がされています。

## vercelについて

具体的には、「vercel」というサービスを使っているのですが、特筆すべき点としては

- レンタルサーバー代が全く必要ない
- FTPソフトも全く必要ない
- レポジトリさえあれば公開ができる

という点です。このセクションでは、**主にこの「vercel」にデプロイ(公開)しているサイトを「クライアント」して、その運営・メンテナンス方法を解説します。**

:::warning

この「クライアント」の定義はかなり曖昧なもので、他のWebアプリケーション全般に適用できるものではありません。
ここでは、「vercelにデプロイしている部分」としていますが、vercelにも実質「バックエンド」のためのAPIサーバーを置くことは可能ですし、このクライアントでもAPIルートでサーバーレスファンクションを動かしています。

結局ここでの「クライアント」は、**[このレポジトリのカバーする範囲](https://github.com/sasigume/projectnapoancom-client-next-2021)**を指していると思ってください。

:::
## バックエンド編も見てね

クライアントだけでは、記事の整理ができません。ナポアンのマイクラNEXTでは、あらかじめ **バックエンドで記事のデータとツイート数などを合成する** という作業を行っており、運用のためにはバックエンド側のメンテナンスも必要です。

詳しくは[バックエンド編](/docs/admin-tech/next/backend/intro)もご覧ください。