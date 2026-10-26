# LiquidGalssAvalonia

基于 .NET 10 + Avalonia 12 的桌面应用。

## 技术栈

| 项目 | 版本 |
| --- | --- |
| .NET SDK | 10.0.302 |
| Avalonia | 12.1.4 |
| 目标框架 | net10.0 |

## 目录结构

```
LiquidGalssAvalonia.slnx           解决方案
global.json                        固定 SDK 版本
src/LiquidGalssAvalonia/           主项目（Avalonia .NET App 模板）
```

## 构建与运行

```bash
dotnet restore
dotnet build
dotnet run --project src/LiquidGalssAvalonia
```

当前阶段：启动后仅显示一个空白窗口。
