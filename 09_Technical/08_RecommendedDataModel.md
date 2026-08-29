# Recommended Data Model

核心表：

World
Node
Event
Choice
Item
Recipe
NPC
Flag
Route
RouteStage
Death
Ending
RunSave

关系：
World 1-N Node
Node 1-N Event
Event 1-N Choice
Choice N-N Flag/Item/Stat
World 1-N Route
Route 1-N RouteStage
Ending 读取 Route/Flag/NPC/Stat
