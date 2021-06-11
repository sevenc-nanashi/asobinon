
---
title: あらゆるテクスチャをGoogle検索の画像にするとこうなる
slug: /minecraft-je/howto/resource-pack-google-image
description: RedditのMinecraftコミュニティに、奇妙なリソースパックが投稿された。ある意味では史上最も「現実的」なリソースパックであり、同時に我々に様々な疑問を投げかけてくれる作品でもある。
---

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208095432.png)

こうしてまた、マインクラフトと現実の境界線が曖昧になった。

RedditのMinecraftコミュニティに、奇妙なリソースパックが投稿された。ある意味では史上最も「現実的」なリソースパックであり、同時に我々に様々な疑問を投げかけてくれる作品でもある。

## ダウンロード

I made a resource pack where every block is its Google Image result : Minecraft

[https://www.reddit.com/r/Minecraft/comments/cexwni/i\_made\_a\_resource\_pack\_where\_every\_block\_is\_its/](https://www.reddit.com/r/Minecraft/comments/cexwni/i_made_a_resource_pack_where_every_block_is_its/)

circuit10氏作成。Dropboxのリンクからダウンロードできる。

なお、このリソースパックはJava Editionの**バージョン1.14以上用**なので注意。2019年8月5日現在圧縮するフォルダーが間違っており、いったん展開して、中身のフォルダーを使う必要がある。(リソースパックの配布ではよくある話だ)

## これがGoogle画像検索リソースパックだ

作者はいちいち検索したわけではなく、**Pythonのスクリプトで画像を収集する手法を使った**とのこと。例えば「oak\_log.png」(樫の原木のテクスチャ)なら「oak log -minecraft」で検索するわけだ。「-minecraft」と付けることで、マインクラフトのテクスチャ画像が一番目に表示されることを防止している。

果たしてテクスチャをGoogleの画像検索結果に置き換えるとどうなるのか。結果は…

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208095356.png)

これである。

そう、ツタは「vine.png」なので「vine -minecraft」で検索するのだから、当然あの「vine」のロゴになってしまったのである。ちなみにジャングルの原木のテクスチャは、フィリピンの「エンチャントキングダム」という遊園地の「Jungle Log」というアトラクションの写真だ。

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208095359.png)

線路(Rail)は線路の写真になると思いきや、車両の写真になってしまっている。そして曲がった部分はクローゼットの洋服をかけるレールの曲がった部分だ。線路という意味は無視されている。

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208095405.png)

サボテンも興味深い結果になっている。サボテンは上面・底面・側面が独立した画像になっており、側面は「cactus\_side.png」なので「cactus side -minecraft」の検索結果になっているわけだが、これは明らかにサボテンの画像ではない。これはシトロエンのC4 カクタス(2015年モデル)である。**作者が「cactus side」で検索した際に「C4カクタスの側面」が出てきた結果、「サボテンが車になる」現象が発生している**のだ。

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208095425.png)

意味がわからないかもしれないが、これは「オークの木材で囲まれた**薄灰色の**色付きガラス板」である。検索結果からマインクラフトの画像を除外するどころか、マインクラフトのレシピが出てきてしまった。**しかも薄灰色ではなく空色である。**これはつまり、空色の色付きガラス板のレシピが載ったWebページに、「minecraft」というワードは書かれていないけれど「light gray glass pane」が書かれていたために、Googleに「薄灰色の色付きガラス板はこれだ」と判断されたのだろう。

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208095416.png)

少なくともこのリソースパックの作者はセーフサーチを使っていなかったことが分かる。ちなみにこれは「ライラック」だ

## マインクラフトにしか存在しない物体の画像はこうなる

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208095408.png)

「マインクラフトのテクスチャ画像が一番目に表示されることを防止している」はずが、やはりマインクラフト世界にのみ存在する物体に対応する画像はマインクラフトのテクスチャになってしまう。例えばレッドストーントーチはレッドストーントーチのテクスチャそのままだ。

## マインクラフトを遊んでいるから故の思い込み

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208095413.png)

赤い羊毛。マインクラフトを遊んでいると「羊毛は立方体である」という思い込みをしてしまい、この画像が一瞬全く別のものに見えてしまった人も多いのではないだろうか。

## Google画像検索の欠陥がよく分かった

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208095420.png)

Google画像検索は時に全く関係のない画像を表示することもある。この場合は「マインクラフトと関係のない画像」というわけではないが、なんてったってこれは「ネザー水晶鉱石」である。なぜネザー水晶鉱石がプレイヤーの顔になるのか? 「nether quartz ore -minecraft」で検索すると、答えがすぐわかる。

[https://twitter.com/kaasboom/status/548422961649438720](https://twitter.com/kaasboom/status/548422961649438720)

このツイートである。このツイートのページがGoogleには「ネザー水晶鉱石のページ」だと判断され、この人のプロフィール画像が「ネザー水晶鉱石の画像」になってしまったわけだ。今のうちにTwitterでブロックの名前をツイートしておけば、このリソースパックが更新された時に「自分のプロフィール画像をマインクラフトの世界に登場させる」ことが可能かもしれない。

## まとめ

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208095429.png)

テクスチャのファイル名で検索した結果おかしくなってしまった部分もあったが、現実世界とマインクラフトのテクスチャは必ずしもイコールではないし、テクスチャは当然「立体の表面」でしかないのだから、シュールな絵面になることは誰もが予想できるだろう。

ただ、土や石など自然の写真はそのままテクスチャとして機能していることも忘れてはいけない。「テクスチャをGoogle画像検索の結果で置き換える」という手法は、**フォトリアルを追求する現代のゲームの風刺のように見えないだろうか。**マインクラフトという実験場を巧みに活用した、歴史に残るべき作品だと私は思う。