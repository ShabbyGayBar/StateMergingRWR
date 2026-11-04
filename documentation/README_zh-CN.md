# 真实资源 X 省份合并

![Steam Subscriptions](https://img.shields.io/steam/subscriptions/3833507054?logo=steam)
![Steam Downloads](https://img.shields.io/steam/downloads/3833507054?logo=steam)

[English](../README.md)

这是一个独立整合模组，结合了[省份合并模组](https://github.com/ShabbyGayBar/StateMerging)和[真实资源模组](https://steamcommunity.com/sharedfiles/filedetails/?id=3459869359)。

请**仅启用本整合模组**，**不要启用两个原始模组**。必须开始**新存档**；不支持继续使用原版或任一原始模组的存档。其他修改相同地图、历史或脚本文件的模组可能与本模组冲突。

## 模组介绍

本模组合并了[真实资源模组](https://steamcommunity.com/sharedfiles/filedetails/?id=3459869359)中的部分省份，建筑、人口等数据总量保留原样。

建筑、人口等数据都保留原样。但是因为合并了各个省份，所以整体陆军、海军、征税等加成在省份上的数值上限都减少了，所以通过加 buff 的方式弥补了一部分回来。

因技术力有限，被合并的省份的城市、建筑模型都会消失。

被合并的省份的代码会消失，可能会导致部分日志和事件无法触发或完成，如有此 BUG 请在 Issues 中提出。 

另外，buff 是按被合并的省份的数量给的，但是因为有些省份实在太小了，我认为它们本来就不应该算一个省份，所以给 buff 时没有计入。

## 当前已经合并的省份

请参照原版[省份合并模组](https://github.com/ShabbyGayBar/StateMerging)。

## 安装方法

可通过以下任一方式安装：

- 在 [Steam 创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3833507054)订阅本模组。
或者
- 在 [Paradox 官网](https://mods.paradoxplaza.com/mods/166222/Any)下载本模组。
或者
- 从[发布页面](https://github.com/ShabbyGayBar/StateMergingRWR/releases)下载模组的 zip 文件，并解压到维多利亚3的模组文件夹中（通常位于 `Documents\Paradox Interactive\Victoria 3\mod`）。

## 提交反馈

### BUG 反馈

请在 Issues 中使用 bug report 模板报告您遇到的任何错误。

### 功能请求

如需提出进一步的省份合并建议，请前往原版[省份合并模组](https://github.com/ShabbyGayBar/StateMerging)。

## 兼容性

跟任何修改了以下目录中文件的模组都不兼容：

- game\common\history\buildings\
- game\common\history\pops\
- game\common\history\states\
- game\map_data\state_regions\

<details>

<summary>其他对游戏进程影响较小的文件的改动</summary>

- game\common\ai_strategies
- game\common\character_templates
- game\common\company_types
- game\common\country_definitions
- game\common\country_formation
- game\common\decisions
- game\common\dynamic_country_names
- game\common\flag_definitions
- game\common\history\global
- game\common\journal_entries
- game\common\on_actions
- game\common\scripted_buttons
- game\common\scripted_effects
- game\common\scripted_triggers
- game\events
- game\localization\LANGUANGE\map

</details>

## 相关链接

- 如果您希望**使用原版资源**，请使用原版省份合并模组：
  - [Github](https://github.com/ShabbyGayBar/StateMerging)，或
  - [Steam 创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3371693463)，或
  - [Paradox 官网](https://mods.paradoxplaza.com/mods/120868/Any)。
- 如果您希望制作自己的省份合并模组，您可以使用[省份合并自动化脚本及教程](https://github.com/ShabbyGayBar/StateMerger)。

## 致谢

* 特别感谢 [Asuna](https://steamcommunity.com/profiles/76561198866770890) 制作的原版[真实资源模组（Explorable Real-World Resources）](https://steamcommunity.com/sharedfiles/filedetails/?id=3459869359)。

## 软件许可证

本模组使用 [MIT LICENSE](../LICENSE) 授权。
