# Compatible CGMs

本节简要概述了所有与**AAPS**兼容的**持续血糖监测系统（CGMs）/扫描式血糖监测系统（FGMs）**。

*提示*：如果您可以在xDrip+应用程序中显示您的血糖数据，则可以在**AAPS**中选择xDrip+作为**BG（血糖）**来源。

* [一般建议](../CompatibleCgms/GeneralCGMRecommendation.md)
* [数据平滑](../CompatibleCgms/SmoothingBloodGlucoseData.md)
* [xDrip+设置](../CompatibleCgms/xDrip.md)
* [将Nightscout作为血糖来源](../CompatibleCgms/CgmNightscoutUpload.md)：虽然可以将Nightscout用作闭环胰岛素输注的血糖来源，但**并不推荐这种方法**，因为它依赖于稳定的移动数据或Wi-Fi连接。 这意味着，只有当您与Nightscout站点在线连接时，您的**CGM（持续葡萄糖监测系统）**数据才会被**AAPS**接收。 为了获得更可靠的设置，使用能够从接收器本地广播到**AAPS**的CGM（如下所列）是一个更好的选择。

| CGM                                                   | 可用的[血糖来源](../SettingUpAaps/ConfigBuilder.md#bg-source) |
| ----------------------------------------------------- | ------------------------------------------------------ |
| [Dexcom G7 and ONE+](../CompatibleCgms/DexcomG7.md)   | xDrip+, DiaKEM app or Juggluco                         |
| [Dexcom G6 and ONE](../CompatibleCgms/DexcomG6.md)    | xDrip+ or BYODA (only G6)                              |
| [Dexcom G5](../CompatibleCgms/DexcomG5.md)            | xDrip+                                                 |
| [Libre 3](../CompatibleCgms/Libre3.md)                | xDrip+ (no transmitter) or Juggluco                    |
| [Libre 2](../CompatibleCgms/Libre2.md)                | xDrip+ (no transmitter) or Juggluco                    |
| [Libre 1](../CompatibleCgms/Libre1.md)                | xDrip+, Glimp, Tomato 或者 Diabox. Need a transmitter    |
| [Eversense](../CompatibleCgms/Eversense.md)           | xDrip+ or ESEL/Eversense patched App                   |
| [Enlite (MM640G/MM630G)](../CompatibleCgms/MM640g.md) | xDrip+ or MM640g + 600Series 安卓上传程序 App                |
| [PocTech](../CompatibleCgms/PocTech.md)               | PocTech                                                |
| [Ottai](../CompatibleCgms/OttaiM8.md)                 | Ottai                                                  |
| [Syai Tag](../CompatibleCgms/SyaiTagX1.md)            | Syai Tag                                               |
| Sibionics CGM                                         | Juggluco                                               |
