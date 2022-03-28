# nonebot-plugin-arcaeabot
An arcaea plugin for nonebot2. ( A cross platform Python async bot framework. )

## 功能 Resume

Arcaea 查分器。

## 如何开始 Quick Start
使用前请确保您的Python版本>=3.8</br> 

使该项目被您的 NoneBot2 (nonebot2 及 nonebot-adapter-onebot 版本不得低于 `2.0.0-beta2` ) 机器人作为插件加载, 至于如何做, 您应该懂的。
### 首次使用您需要更新资源文件(assets/song, assets/char以及constants.json)。
向bot发送"/arc assets_update"以更新资源文件。（默认使用我搭建的api服务器）</br>
如果更新失败（服务器炸了）您可以使用[ArcaeaAssetsUpdater](https://github.com/SEAFHMC/ArcaeaAssetsUpdater)搭建自己的资源更新服务器，然后在.env.{ENVIRONMENT}中填您的api地址) </br>
还可以直接从[百度云](https://pan.baidu.com/s/19tmRj4M3eAov6FB_te6f3A?pwd=7g1b)下载资源文件（更新至3.12.4c）。

## 指令 Command

| 指令               | 描述                                                         |
| ------------------ | ------------------------------------------------------------ |
| /arc assets_update | 更新曲绘, 请务必在您初次使用该插件或者 Arcaea 版本有更新时发送此命令 |
| /arc help          | 查看该插件的帮助文档                                         |
| /arc bind {id}     | 绑定您的 Arcaea 账户, id 应为 9 位数字                       |
| /arc unbind        | 删除您的绑定信息                                             |
| /arc info          | 查询您的绑定信息                                             |
| /arc recent        | 查询您的最近游玩信息                                         |
| /arc b30           | 查询您的 best 30 记录                                        |

## To Do
- 自定义名片
<p align="center">
  <a href="https://sm.ms/image/JDvXTCQl8zghV3B" target="_blank">
    <img src="https://s2.loli.net/2022/03/25/JDvXTCQl8zghV3B.png">
  </a>
</p>

咕咕咕
## 参考代码
- [DiheChen/nonebot-plugin-arcaea](https://github.com/DiheChen/nonebot-plugin-arcaea)
- [iyume/nonebot-plugin-arcaea](https://github.com/iyume/nonebot-plugin-arcaea)

