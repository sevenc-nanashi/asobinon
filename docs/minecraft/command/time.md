# time

| 項目 | 内容 |
| --- | --- |
| コマンド | `time` |
| 目的 | ワールドの太陽と月の位置を変更する |
| 必要な権限レベル | 1 |
| コマブロで実行 | 可能 |
| 適用対象 | ワールド |

## 構文

### 変更

![朝、昼、夜それぞれのtimeコマンド](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208112118.png)

[[dl|時間を変更する]]
|```
|/time set <時間>
|```

![dayとnight](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208112122.png)

以下のように、英単語で指定することもできる。

[[dl|時間を朝 (1000) にする]]
|```
|/time set day
|```

[[dl|時間を昼 (6000) にする]]
|```
|/time set noon
|```

[[dl|時間を夜 (13000) にする]]
|```
|/time set night
|```

[[dl|時間を真夜中 (18000) にする]]
|```
|/time set midnight
|```

[[dl|時間を早朝 (23000) にする]]
|```
|/time set sunrise
|```

### 追加

[[dl|時間を少しだけ進める]]
|```
|/time add <時間>
|```
|1時間=1000、1日=24000である。
|ちなみに**/time add 24000**と入力すると、太陽と月の位置はまったく変わらない。

## 引数

[[dl| <時間> (必須)]]
|「0」～「23999」までの数値を入力して数値を指定**する。
|24000を超えると、`/time (set|add) <時間-24000>` となり、余剰分が計算に使われる。
|
|![マイクラの一日](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sasigume/20210208/20210208092652.png)
|時間はこのように変化しており、
|- 日の出の時間が「0」
|- 正午が「6000」
|- 日の入りが「12000」
|- 真夜中12時が「18000」
|- 「24000」と入力すれば、また日の出に戻ってくる
