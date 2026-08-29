# Map And Fog System

地图是节点网络，不是完全开放地图。

节点状态：
- HIDDEN
- REVEALED
- DISCOVERED
- VISITED
- DEPLETED
- LOCKED
- CHANGED

迷雾只展示可能方向，不提前展示关键内容。

部分事件可以：
- 揭开远处节点
- 关闭路线
- 新增路线
- 改变节点类型
