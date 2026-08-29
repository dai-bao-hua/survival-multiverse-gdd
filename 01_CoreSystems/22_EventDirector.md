# Event Director

EventDirector 每次选事件时依次处理：

1. 收集当前位置候选事件
2. 排除条件不满足项
3. 排除冷却中事件
4. 根据 World/Day/Weather/Flags/Traits/NPC 修正权重
5. 对近期重复标签降权
6. 对长期未出现但应该出现的关键路线事件增加保护权重
7. 抽取事件
8. 写入 EventHistory

关键路线不得只靠纯随机低概率触发。
使用“保护权重”确保玩家已经满足条件后，在合理时间内能看到推进机会。
