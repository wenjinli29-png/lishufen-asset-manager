# 更新记录

## v19.3.0 · 整理更顺手，插件预览更轻快

这次把主软件和插件里容易卡住创作节奏的地方重新整理了一遍：拖动排序更直观，项目素材各归各位，打开插件后先看到眼前需要的图片。

- **统一界面与操作**：主软件和插件采用浅色与玫红配色，调整搜索、卡片和导入按钮的布局；小窗口里也保留方便点击的按钮。
- **卡片和项目都能拖动排序**：可排序的卡片使用一致的拖动让位效果，项目顺序也能直接调整。
- **修复新项目的道具显示**：新建项目初始为空，只显示加入该项目的道具，以及项目角色和场景关联的道具。
- **修复插件大图预览**：不再把超过 8 MB 的图片直接跳过，单文件上限仍为 32 MB。预览失败会显示原因，可在卡片上单独重试。
- **改善声音与视频预览**：增加播放兼容处理；如果网页仍限制播放，或浏览器不能解码格式，可在主软件中预览。
- **减少重复加载**：缩略图按窗口可见范围加载；同一资料库改名、排序、分配项目或收起后重新打开时，复用有效缩略图。搜索会合并连续输入，避免每敲一个字都重建列表。

原文件导入仍保留完整文件，单次合计上限为 64 MB。插件提供即梦、LibTV、Seko、小云雀和 Updream 入口；画布是否接收文件以网站实际反馈为准，放入后先确认预览再继续生成。

**[下载 Windows v19.3.0](https://github.com/wenjinli29-png/lishufen-asset-manager/releases/download/v19.3.0/Lishufen-Asset-Manager-Windows.zip)** · [单独下载 Chrome / Edge 插件 0.7.4](https://github.com/wenjinli29-png/lishufen-asset-manager/releases/download/v19.3.0/Lishufen-Asset-Manager-Browser-0.7.4.zip)

Windows 软件包内含插件、使用说明、图文指南和中文演示视频。已安装插件的朋友，更新文件后在浏览器扩展管理页点“重新加载”，再刷新创作网页即可。更新软件前先备份自己的资料，完整解压使用。Mac 继续提供原有的 v19.1.0-mac.1 测试版，本次未更新 Mac 安装包。

欢迎继续反馈使用感受，也欢迎来我的主页聊聊 AI 视频创作。[抖音主页](https://v.douyin.com/RnsvkrkP2rU/) · [B站主页](https://space.bilibili.com/494755856)

### English

v19.3.0 updates the Windows app and Chrome / Edge extension 0.7.4:

- A consistent light and rose interface with compact cards and clear action buttons.
- Consistent drag-to-reorder behavior for sortable cards, plus project ordering.
- New projects no longer show unrelated props.
- Image previews now work above 8 MiB, up to the existing 32 MiB per-file limit. Failed cards show the reason and offer a retry.
- Improved audio and video playback compatibility, visible-area thumbnail loading, cache reuse and debounced search.

Imports preserve original file bytes, with a 64 MiB batch limit. The destination website must accept dropped files; check its preview before generating. Reload the updated extension and refresh your creative page. The Windows package includes instructions, the illustrated guide and the existing Chinese demo video. Mac remains at v19.1.0-mac.1.

## v19.0.1 · 把我的主页放进软件

这次把我的抖音和 B站主页放进了软件，也在软件包里加了一份“作者与社媒.txt”，方便大家找到我。日常整理和复制素材的功能保持原样。

欢迎大家试用，有想法也可以来交流。

- 抖音：[AIGC异想天开的老李](https://v.douyin.com/RnsvkrkP2rU/)
- B站：[AIGC异想天开的老李](https://space.bilibili.com/494755856)

[下载最新 Windows 版](https://github.com/wenjinli29-png/lishufen-asset-manager/releases/latest/download/Lishufen-Asset-Manager-Windows.zip)

## v19.0.0 · 整理、查找、复制素材

把平时做 AI 视频会用到的素材集中放在一起：

- 按项目整理角色、服装、场景、道具和群演，同一素材可以在多个项目中使用。
- 预览图片、试听声音，复制单个原文件，或一次复制角色当前的服装和道具。
- 保存 Skill 的说明、示例和历史版本，方便之后继续用。
- 用 Chrome / Edge 插件在创作网页旁取用素材。
- 选择自己的存放位置，做好本地备份，或通过百度网盘上传和下载整个素材库。

这一版也把同步调整为“打开时检查，修改后同步”，空闲时不反复检查。删除的素材会在回收站暂存三天，方便找回。

软件包附有中文讲解视频和图文指南。下载后完整解压，双击“李淑芬的资产管理工具.exe”即可打开。

[下载 v19.0.0](https://github.com/wenjinli29-png/lishufen-asset-manager/releases/download/v19.0.0/Lishufen-Asset-Manager-Windows-v19.zip) · [观看演示](https://github.com/wenjinli29-png/lishufen-asset-manager/releases/download/v19.0.0/Lishufen-Asset-Manager-Demo.mp4) · [图文指南](https://github.com/wenjinli29-png/lishufen-asset-manager/releases/download/v19.0.0/Lishufen-Asset-Manager-Guide.pdf)
