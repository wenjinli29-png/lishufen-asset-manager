# v19.0.0 — Windows 便携使用版

主程序 v19，Chrome / Edge 插件 0.4.1。适用于 Windows 10 / 11 64 位系统。

本发布提供可下载使用的软件及教程，不提供应用源工程，不声明为开源软件。

## 下载附件

| 项目 | 内容 |
| --- | --- |
| Windows 使用版 ZIP | `Lishufen-Asset-Manager-Windows-v19.zip` |
| 文件大小 | 39,928,950 字节（约 38.08 MiB） |
| 包内文件数 | 121 |
| SHA-256 | `d4ef7bb779d770da172c043d29d012e6599be171234d38fb36621ea273123de9` |

[直接下载 Windows 使用版](https://github.com/wenjinli29-png/lishufen-asset-manager/releases/download/v19.0.0/Lishufen-Asset-Manager-Windows-v19.zip) · [下载校验文件](https://github.com/wenjinli29-png/lishufen-asset-manager/releases/download/v19.0.0/SHA256SUMS.txt)。全部附件见本仓库 [Releases](https://github.com/wenjinli29-png/lishufen-asset-manager/releases/latest)。GitHub 自动生成的 `Source code (zip)` 只是介绍与教程仓库的归档，不是软件使用版。

本包通过 9 项实际解压功能检查与 20 项分发内容检查；测试使用独立示例库，不涉及制作者的真实资料。

完整解压到可写目录，双击 `李淑芬的资产管理工具.exe`。所需运行组件随包提供，无需自行安装 Python 或 Node.js。退出网页后后台仍运行；待当前任务结束，双击 `关闭后台服务.exe` 停止。

## 本次发布内容

- 角色、服装、场景、道具、群演及 Skill 管理；按项目和总库查找、预览、复制原文件。
- 项目使用总库引用，同一素材可加入多个项目；删除前显示受影响项目，回收站暂存三天。
- 角色全套、本套服装与单件原文件复制；声音单独试听和取用。整套复制不包含独立面部图、声音或历史版本。
- Skill 的说明、封面、完整制作包和历史版本，支持比较正文与切换版本。
- Chrome / Edge 插件 0.4.1，提供项目层级、服装与道具预览、声音试听、可拖动入口和放入素材操作。
- 本地资产目录切换、完整备份、百度网盘授权与资料库上传下载。
- v19 采用事件触发同步：开启后打开检查一次，软件内修改停止约 8 秒后同步，空闲不反复查询。失败保留本地资料，不反复重试同一状态。
- Windows 便携启动、关闭后台入口及第三方组件许可说明。
- 约 3 分 19 秒的中文配音演示、字幕、六页 PDF 图文指南、可编辑 Word 版与封面。

讲解视频与六页指南 PDF 作为本版本的独立 Release 附件提供：[演示视频](https://github.com/wenjinli29-png/lishufen-asset-manager/releases/download/v19.0.0/Lishufen-Asset-Manager-Demo.mp4) · [图文指南 PDF](https://github.com/wenjinli29-png/lishufen-asset-manager/releases/download/v19.0.0/Lishufen-Asset-Manager-Guide.pdf)。视频、PDF、可编辑 Word、字幕和封面也全部包含在便携包的 `使用文档/功能介绍与演示/` 中。

## 使用边界

发布包首次启动为新空库，不包含制作者的素材数据库、项目、机器配置或百度授权。讲解视频与文档中的人物和目录为演示示例，不会导入新库。

插件最低要求 Chrome 120 或相应 Chromium 版本的 Edge。目标网站可拒绝模拟拖放或文件上传，放入后应检查网站预览；插件不会点击生成。当前未宣称即梦、LibTV、Seko、小云雀的全部登录工作区都已实测适配。

群演支持多选原文件复制，当前不自动拼图。云端上传和下载使用完整资料库包；暂无单图按需下载、增量原件传输或冲突自动合并。旧项目独立副本保留，不按同名自动删除。

关闭网页不会关闭本地服务。已有版本占用默认端口时，应先从其所在目录关闭后台。升级前先备份，保留自己的资料库与机器设置；分享给其他人请使用原始发布 ZIP。

第三方组件许可及其文件位置以包内 `第三方组件说明.txt` 为准，包括 Python 及其所含组件的许可，以及百度连接组件的 Apache License 2.0。对应许可适用于各自组件，不将本应用声明为开源软件。
