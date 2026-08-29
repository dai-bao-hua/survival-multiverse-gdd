# Content Validation

构建时必须做数据校验：

- ID 唯一
- NextEvent 存在
- Node 存在
- Item ID 存在
- Ending 条件引用 Flag 存在
- Route 阶段连续
- 普通 Death 的 revivable = true
- 终局 Death 不允许普通 Revive
- 每个 World 至少有一条完整路线
- 每个关键资源至少有来源
