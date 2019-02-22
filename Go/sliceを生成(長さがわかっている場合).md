# Summary
生成したいsliceの長さが10だとわかっている場合
```
slice := make([]uint, 0, 10)
```

# Pro
キャパシティが足りていない状態で、sliceをappendする際に、新しい配列が生成されて代入されてしまうのを防ぐ。

## 参考文献
(https://golang.org/pkg/builtin/#append)    
(https://mattn.kaoriya.net/software/lang/go/20150928144704.htm)
