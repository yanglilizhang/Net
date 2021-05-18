[net](../../index.md) / [com.drake.net.interfaces](../index.md) / [ProgressListener](./index.md)

# ProgressListener

`abstract class ProgressListener`

进度监听器, 为下载和上传两者

### Parameters

`interval` - 进度监听器刷新的间隔时间, 单位为毫秒, 默认值为500ms

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | 进度监听器, 为下载和上传两者`ProgressListener(interval: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)` = 500)` |

### Properties

| Name | Summary |
|---|---|
| [elapsedTime](elapsed-time.md) | `var elapsedTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [interval](interval.md) | 进度监听器刷新的间隔时间, 单位为毫秒, 默认值为500ms`var interval: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [intervalByteCount](interval-byte-count.md) | `var intervalByteCount: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |

### Functions

| Name | Summary |
|---|---|
| [onProgress](on-progress.md) | 监听上传/下载进度回调函数`abstract fun onProgress(p: `[`Progress`](../../com.drake.net.component/-progress/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |