# qxbgm-schemes-wonderland

千星BGM替换管理器（QxBgmManager）的**奇域复刻 BGM 方案**发布者仓库。
面向复刻经典游戏的奇域地图，把地图实际使用的 BeydMusic 槽位替换为对应原作曲目。

安装：QxBgmManager → 方案市场（索引源 `crt106/qxbgm-registry`）→ 搜索或分类浏览。

## 方案列表

| 方案 | 目标奇域 | 槽位映射 |
|---|---|---|
| `contra-nes-bgm` | 魂斗罗·重返郭往营地 | 10032←Jungle Hangar（关1/3/5）、10046←Bases I&II（关2/4）、10020←Alien's Lair（关6+） |
| `billiards-caromhall` | 模拟台球 | 10082（天使的馈赠）← caromhall |

## 槽位分析依据

槽位来自对奇域运行时存档（`Beyond_Local_Save_Runtime/<奇域ID>.gir`）的解析：
魂斗罗地图的关卡→曲目选择逻辑、台球地图厅内 BGM 的 `{id, volume, duration}` 配置。
详见 `docs/`。

## 权利声明

音频权利归各原版权方所有；本仓库不授予音频的任何再授权，仅作本地个人使用的技术载体。
请勿二次分发音频内容。
