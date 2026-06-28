# AutoTouch Pro - 安卓自动操作录制回放软件

## 项目简介

**AutoTouch Pro（触控精灵专业版）** 是一款基于 Android 无障碍服务开发的自动化操作录制与回放工具。用户可以通过悬浮窗一键录制自己在手机上的所有操作（点击、滑动、长按等），并将录制的操作脚本保存下来，随时一键回放执行。

## 核心功能

- ✅ **操作录制**：全局录制点击、滑动、长按等操作
- ✅ **操作回放**：精确回放录制的操作脚本
- ✅ **悬浮控制**：全局悬浮窗控制录制/回放
- ✅ **脚本管理**：保存、加载、删除、重命名脚本
- ✅ **脚本编辑**：可视化编辑脚本动作
- ✅ **循环回放**：支持设置循环次数和间隔
- ✅ **速度调节**：支持 0.5x - 3x 倍速回放

## 项目结构

```
AutoTouch/
├── app/                    # 应用主模块
│   └── src/
│       ├── main/
│       │   ├── java/com/autotouch/pro/
│       │   │   ├── app/           # 应用全局
│       │   │   ├── ui/            # UI层（MVVM）
│       │   │   ├── service/       # 服务层
│       │   │   ├── data/          # 数据层
│       │   │   ├── domain/        # 领域层（业务逻辑）
│       │   │   ├── util/          # 工具类
│       │   │   └── extension/     # 扩展函数
│       │   ├── res/               # 资源文件
│       │   └── AndroidManifest.xml
│       ├── test/                  # 单元测试
│       └── androidTest/           # 仪器化测试
├── Docs/                   # 项目文档
│   ├── AutoTouch_Pro_详细设计文档.md
│   └── Assert/             # 文档配图
├── gradle/                 # Gradle 配置
├── build.gradle.kts        # 根构建配置
├── settings.gradle.kts     # 项目设置
└── README.md
```

## 技术栈

- **开发语言**：Kotlin
- **UI框架**：Jetpack Compose
- **架构模式**：MVVM + Clean Architecture
- **异步处理**：Kotlin Coroutines + Flow
- **依赖注入**：Hilt
- **数据库**：Room
- **构建工具**：Gradle + Kotlin DSL

## 最低要求

- Android 8.0 (API 26) 及以上
- 无障碍服务权限
- 悬浮窗权限

## 文档

详细设计文档请查看 [Docs/AutoTouch_Pro_详细设计文档.md](Docs/AutoTouch_Pro_详细设计文档.md)

## License

TODO
