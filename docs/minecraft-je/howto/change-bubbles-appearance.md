
---
title: 1.5で追加された「泡」の見た目をJava版と同じにする方法
slug: /minecraft-je/howto/change-bubbles-appearance
description: アップデートアクアティック(水のアップデート)のPart2としてもうすぐ配信される「1.5」。カメと関連アイテムに加えて、ついに「泡(気泡)」が実装されます。しかし、アプリ版の泡は見た目がしょぼい… Java版のような見た目にするには、設定の変更が必要なんです。
---

アップデートアクアティック(水のアップデート)のPart2として配信された**「1.5」**。**カメと関連アイテムに加えて、ついに「泡(気泡)」が実装されました。**しかし、アプリ版の泡は見た目がしょぼい… **Java版のような見た目にするには、設定の変更が必要なんです。**

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208101318.png)

1.5で「泡」が実装されたことにより、**水中のマグマブロックの上に泡が発生し、下向きに引っ張る力が発生するようになりました**

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208111457.png)

マグマブロックだけでなく、**ソウルサンドからも泡が発生します。ただし、ソウルサンドから出る泡は物体を上昇させます。**

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208111059.png)

あれ? 思っていたのと見た目が違う?

実はBEでは、低スペックの端末に配慮して、**デフォルトではブロックに貼り付いたテクスチャとして表示されるんです。**Java版みたいな**パーティクルで表示させるにはどうすればいいんでしょうか。**

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208110011.png)

答えはビデオ設定！ほら、**「気泡の表現」**って項目をONに… **できませんね。ワールド内では泡の見た目は変更できません。**一旦ワールドを出ましょう。

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208090716.png)

ということでタイトル画面の設定→**「ビデオ」の「気泡の表現」をONに**しましょう。

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208115204.png)

一部のデバイスのパフォーマンスを低下させる可能性があるそうです。まあ私は**i7-6700K + RAM32GB + GTX1080Ti**で遊んでるから全く問題ないんですけどね。

![](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208115209.png)

なんか泡が少ないですが、今後のベータ版の更新で改善されるのを待ちましょう。

**ところで皆さん、BFVのトレーラーはもう見ましたか！？！？**グラフィックやばいでしょ！！と思ったらめっちゃ低評価されてるし！！**皆さんBFVの女兵士やらスキンやらについてどう思いますか！！！**私は**プレミアムパスが廃止**されたならもう何でもありでいいと思いますけどね！！BFってそもそもリアリティいらないでしょ！！！どんぱちできればいいんだよ！！！！それと今作から**グレネードが投げ返せたり**分隊で協力すれば爆撃を要請できたり**破壊された建物を修復できたり**できるらしいですよ！！！！あとなんか戦車に砲台を連結したり！！！！やばくないですか！！！！CODBO4はキャンペーンを捨てましたが**BFVにはちゃんとキャンペーンがあって安心**ですね！！！！バッドカンパニーみたいな感じがする協力PvEモードもあるみたいですし！！！！！後はヨーロッパだけじゃなく太平洋戦争も取り上げてほしいですね！！！！！**皆さんもう予約しましたか！！！！！**予約してない人は今すぐしましょう！！！！予約すればBF1で使える武器5種がもらえるらしいですよ！！！！！！