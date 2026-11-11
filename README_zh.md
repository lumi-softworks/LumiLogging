# LumiLogging

📖 English | [中文版](README_zh.md)

Lumi 家族应用共用的日志原语与应用内日志收集。

## 产品

- `LumiLoggingKit` 提供 `SuperLog`、`MagicLogger` 与 `MagicLogEntry`。
- 系统日志的消息正文使用私有隐私级别；应用内日志条目仍对宿主界面可见。

## Swift Package Manager

```swift
.package(url: "https://github.com/lumi-softworks/LumiLogging.git", from: "1.0.0")
```

```swift
.product(name: "LumiLoggingKit", package: "LumiLogging")
```

```swift
import LumiLoggingKit
```
