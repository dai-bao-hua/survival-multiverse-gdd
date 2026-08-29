# Death Revive Ads

状态机：

ALIVE
→ ORDINARY_DEATH
→ CAN_REVIVE if charges > 0
→ AD_COMPLETED
→ REVIVING
→ ALIVE

若 charges = 0：
ORDINARY_DEATH → RUN_OVER

新 Run 初始化 charges = 3。
