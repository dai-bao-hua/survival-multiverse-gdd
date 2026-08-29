# Flag System

Flag 负责长期记忆。

类型：
- 世界 Flag
- 路线 Flag
- NPC Flag
- 事件 Flag
- 一次性 Flag
- 永久图鉴 Flag

命名示例：
FOUND_RADIO
HELPED_ENGINEER
CAVE_COLLAPSED
KNOW_SECRET_LAB

必须定期审计：是否存在永远不会被设置或永远不会被读取的 Flag。
