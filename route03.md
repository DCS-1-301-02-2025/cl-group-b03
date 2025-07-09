# ○○の通学経路

[メンバー表に戻る](member.md#メンバー表)

```graphviz
digraph {
    edge [dir=both]
    八王子国際キャンパス　-> 高尾駅 [label=バス]
    高尾駅 -> 西国分寺駅 [label=中央線]
    西国分寺駅 -> 新秋津駅 [label=武蔵野線]
    新秋津駅 -> 秋津駅 [label=徒歩]
    秋津駅 -> 東久留米駅 [label=西武池袋線]
    東久留米駅 -> 家 [label=徒歩]
    
}
```
