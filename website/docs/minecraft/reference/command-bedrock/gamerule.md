# gamerule

|項目|内容|
|---|---|
| コマンド |`gamerule`|
|目的| ゲームルールを設定する |
| OP 権限           | 必要                   |
| コマブロで実行    | 可能                   |
| 適用対象          | ワールド               |

## 構文

[[dl|指定したゲームルールの値を設定する]]
|```
|/gamerule <ゲームルール> <値>
|```

[[dl|指定したゲームルールの現在の値を取得する]]
|```
|/gamerule <ゲームルール>
|```

## 引数

[[dl| <ゲームルール> (必須)]]
|設定または取得するゲームルールを指定する。ルール一覧は後述。

[[dl| <値> (設定する場合は必須、取得する場合は不要)]]
|ゲームルールに設定する値を書く。

## BE で設定できるゲームルール一覧

| ルール名                | 説明                                                                                               | デフォルトの値 |
|---------------------|--------------------------------------------------------------------------------------------------|---------|
| commandblockoutput  | コマンドブロックがコマンドを実行した際に、OP 権限を持つプレイヤーに通知するか否か                                                       | true    |
| dodaylightcycle     | 昼夜サイクルが動くか否か (時間が動くか否か)                                                                          | true    |
| doentitydrops       | Mob ではないエンティティ(トロッコなど)がアイテムをドロップするか否か                                                            | true    |
| dofiretick          | 火が勝手に燃え広がるか否か                                                                                    | true    |
| domobloot           | Mob がアイテムをドロップするか否か                                                                              | true    |
| domobspawning       | Mob が自然にスポーンするか否か。スポーンブロックには影響しない                                                                | true    |
| dotiledrops         | ブロックがアイテムをドロップするか否か                                                                              | true    |
| doweathercycle      | 天候が変化するか否か                                                                                       | true    |
| drowningdamage      | プレイヤーが水に溺れてダメージを受けるか否か                                                                           | true    |
| falldamage          | プレイヤーが落下ダメージを受けるか否か                                                                              | true    |
| firedamage          | プレイヤーが火のダメージを受けるか否か                                                                              | true    |
| keepinventory       | プレイヤーが死んだ後も持ち物をインベントリに保持するか否か                                                                    | false   |
| mobgriefing         | クリーパー、ゾンビ、エンダーマン、ガスト、ウィザー、エンダードラゴン、ウサギ、ヒツジ、村人がブロックに変更を加えるか否か。また、村人、ゾンビ、スケルトン、ゾンビピッグマンがアイテムを拾うか否か | true    |
| naturalregeneration | 満腹度が一杯の場合に、体力が自然回復するか否か (金リンゴや再生のポーションなどの追加の回復には影響しない)                                           | true    |
| pvp                 | プレイヤーが他のプレイヤーと戦闘できるか(PvP できるか)否か                                                                 | true    |
| sendcommandfeedback | プレイヤーがコマンドを実行した時に、チャットに通知を流すか否か。また、コマンドブロックが実行結果の文章を保持するか否か                                      | true    |
| showcoordinates     | 画面左上に現在位置の座標を表示するか否か                                                                             | false   |
| tntexplodes         | TNT を起爆できるか否か                                                                                    | true    |

## 実行結果

ゲームルール名や指定した値が正しくない場合は失敗する。

取得モードと設定モードがあり、成功すると、

- 値が**与えられていない**場合は、**現在の値を返す。**
- 値が**与えられている**場合は、その値に**変更する。**

## 使用例

- `/gamerule dodaylightcycle false` : 昼夜サイクルを止める
- `/gamerule pvp` : このワールドはPVPが有効かどうか**確認する**(変更はされない)