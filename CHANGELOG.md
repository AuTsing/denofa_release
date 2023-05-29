# Denort Change Log 更新日志

## [0.7.3] - 2023/05/29

-   修复了一些已知问题

## [0.7.2] - 2023/05/11

### Denort App v0.7.2 更新日志

-   修复启用 WS 服务器异常时没有提示的问题
-   修复媒体投影服务权限开关重启活动后没有同步的问题
-   修复底部消息栏消息重叠的问题
-   修复底部消息栏可能导致应用 ANR 的问题
-   修复 `UiObject` 中使用的 Rect 非 JS 端 `Rect` 的问题
-   `DenortCore` v0.4.0 -> v0.4.1

### DenortCore v0.4.1 更新日志

-   新增 `UiObject` 类成员函数 `getOriginId`
-   优化 `UiSelector` 类 `toString` 可读性
-   优化 `UiSelectorBuilder` 类 `toString` 可读性
-   修复 `UiObject` 中使用的 `Rect` 非 JS 端 `Rect` 的问题

## [0.7.1] - 2023/05/10

### Denort App v0.7.1 更新日志

-   修复对于固定横屏的应用横竖屏参数错误的问题

## [0.7.0] - 2023/05/09

### Denort App v0.7.0 更新日志

-   修复运行工程之前不刷新获取最新工程的问题
-   修复横屏后屏幕参数异常的问题
-   修复删除工程和刷新工程列表没有同步进行的问题
-   无障碍操作参数从 `Coor` 迁移至 `Point`

### DenortCore v0.4.0 更新日志

-   新增模块 `Android.img` 图色模块
    -   新增函数 `refresh` 刷新底层图片
    -   新增函数 `refreshManually` 刷新底层图片
    -   新增函数 `getImage` 获取底层图片 (暂未实装)
    -   新增函数 `lock` 锁定底层图片
    -   新增函数 `unlock` 解锁底层图片
    -   新增函数 `compareColor` 单点比色
    -   新增函数 `compareColors` 多点比色
    -   新增函数 `findColor` 找单点色
    -   新增函数 `findColors` 找多点色
    -   新增函数 `findMultiColor` 多点找单点色
    -   新增函数 `findMultiColors` 多点找多点色
    -   新增类 `CompareColorOptions` 比色可选项
    -   新增类 `FindColorOptions` 找色可选项
-   新增类 `Android.Point` 点类
-   更新类 `Android.Rect` 矩形类
-   更新模块 `Android.finger.accessibility`
    -   更新函数 `click` 函数签名
    -   更新函数 `press` 函数签名
    -   更新函数 `swipe` 函数签名

## [0.6.0] - 2023/05/06

-   新增 WS 服务器支持截图命令
-   修复媒体投影服务可能导致应用崩溃的问题

## 0.5.0 - 2023/04/18

-   WS 服务器
-   FTP 服务器
-   无障碍服务
-   媒体投影服务
-   悬浮窗
-   新关于页面
-   Denort core 升级至 v0.3.0
-   Deno 升级至 v1.31.3
-   若干可能导致崩溃的 bug 修复
-   若干影响流畅度的 bug 修复

## 0.4.0 - 2022/11/13

-   ✨ 工程新增删除按钮
-   ✨ 通过模板新建已实装
-   ✨ 新增 13 个示例
    -   Hello world
    -   import 和 export 模块
    -   管理依赖
    -   请求数据
    -   文件读写
    -   实现 unix cat 程序
    -   HTTP web 服务器
    -   文件服务器
    -   TCP echo 服务器
    -   OS 信号
    -   文件系统事件
    -   模块 metadata

## 0.3.0 - 2022/11/9

-   ✨ 全新的代码编辑器
-   ✨ 新建文件，新建工程已实装
-   🔧 工程详情页面新增打开工程选项
-   🔧 项目根目录调整至 /Denort/Projects

## 0.2.0 - 2022/10/31

-   ✨ 全新的新建工程页面，FTP 服务器开关转移至设置页面
-   🔧 工程页面 UI 调整优化
-   🎈 设置页面新增 FTP 服务器开关
-   🎈 设置页面新增关于页面

## 0.1.1 - 2022/10/29

-   📕 补充部分翻译

## 0.1.0 - 2022/10/28

-   ✨ 现代的 JS 和 TS 运行时 Deno
-   ✨ 安卓 API io 和 finger
-   ✨ Material Design 3 设计的客户端界面
-   ✨ FTP 管理工程
-   ✨ 一键运行工程项目
-   ✨ 简洁的日志管理
