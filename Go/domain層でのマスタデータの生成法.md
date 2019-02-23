# Summay
マスタデータを定義する際にiotaを使用して番号を割り振る。

# Example
```
const = (
  _TournamentType = iota
  InPreparation                        // 準備中(1)
	Accepting                            // 参加受付中(2)
	Started                              // 開催中(3)
	Ended                                // 終了(4)
)
```
