# mymmd1

```mermaid
stateDiagram-v2
    [*] --> 待機
    待機 --> [*]
    待機 --> Moving
    Moving --> 待機
    Moving --> クラッシュ
    クラッシュ --> [*]
