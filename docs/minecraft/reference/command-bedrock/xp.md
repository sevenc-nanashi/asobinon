# xp

| 項目 | 内容 |
| --- | --- |
| コマンド | `xp` |
| 目的 | プレイヤーの経験値を追加・削除する |
| 必要な権限レベル | 1 |
| コマブロで実行 | 可能 |
| 適用対象 | プレイヤー |

## 構文

[[dl|指定したプレイヤーの経験値ポイントを増やす]]
|```
|/xp <経験値の量> [プレイヤー]
|```

[[dl|指定したプレイヤーの経験値レベルを増やす・減らす]]
|```
|/xp <経験値レベル>L [プレイヤー]
|```


## 引数

[[dl| <経験値の量> ]]
|プレイヤーに与える経験値の量を指定する。0以上2147483647以下でないといけない。

[[dl| <経験値レベル>L ]]
|**`L`を付けた場合は、ポイントではなくレベルを増やす。**マイナスの値を書くことでレベルを減らすことが出来る。

[[dl|[プレイヤー] (任意) ]]
|経験値を増やすプレイヤー、もしくは経験値レベルを増やす・減らすプレイヤーを指定する。**指定しない場合はコマンドの実行者がターゲットになる。**
|コマンドブロックではこの引数は必須。

## 実行結果

引数が正しく指定されていない場合、プレイヤーが見つからない場合は失敗する。

成功すると、経験値ポイントを与える、もしくは経験値レベルを与える・減らす。経験値が0を下回ることはない。

## 使用例

- `/xp 7` : 自分の経験値ポイントを7増やす
- `/xp -3L steve` : steveのレベルを3減らす
- `/xp -2147483648L @a` : 全員の経験値レベルを強制的に0にする