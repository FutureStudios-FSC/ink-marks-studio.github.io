# 快速开始
## 下载和使用
### 1.下载
可以从 [NuGet 包](https://www.nuget.org/packages/StarLight_Core ) 获取 StarLight_Core，
或者在 [GitHub 存储库](https://github.com/Ink-Marks-Studio/StarLight.Core) 下载文件。
### 2.配置
在你的 CSharp 文件中添加引用代码：
```
using StarLight_Core;

using StarLight_Core.Authentication; // 验证器
using StarLight_Core.Launch; // 启动器 一般还需要依赖：
using StarLight_Core.Models.Launch;
using StarLight_Core.Enum;
using StarLight_Core.Utilities; // 工具
```
如果你只想引用对应的类，也可以在后面加上类名，一般常用的类名有：
| 名称 | 作用 |
|:------:|:------------------------------------------:|
| Authentication | 账户验证，包含正版、离线、第三方等相关验证组件（详见验证器相关文档） |
| Launch | 启动器，编辑启动配置、异步启动游戏（详见[启动器](https://luzhou.wiki/Launcher/Launcher.html)）
| Utilities | 经过封装的实用工具，用于获取游戏核心、JVM虚拟机等 |
