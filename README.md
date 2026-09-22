# MyAIStudio Windows 客户版

这是基于 RunningHub 云算力与本地画布功能的 Windows 便携版。

## 下载与使用

1. 下载 `MyAIStudio-Windows-Portable.zip`。
2. 解压后进入 `MyAIStudio` 文件夹。
3. 双击 `AIstudio.exe` 启动。
4. 在应用设置中填写客户自己的 RunningHub API Key，即可提交云端工作流任务。

本版本同时包含本地画布、项目保存、素材上传和结果下载功能。客户无需单独安装 Python 或 Node.js，但必须保留解压后的完整目录结构。

如果启动窗口无法打开，请先运行压缩包内 `install\MicrosoftEdgeWebview2Setup.exe`，再重新启动。

详细说明见压缩包内的 `MyAIStudio\客户使用说明.md`。

## 配置规则参考

- [config3规则.txt](./config3规则.txt)：ComfyUI 工作流配置文件的编写规则与 JSON 示例，供配置多模态输入、节点映射和参数类型时参考。
- 该文件是配置参考资料，不需要放入客户压缩包才能启动 MyAIStudio。

## 文件完整性

- SHA-256: `8EDE97BAA3B977C589A26B821D1333AEA49E75ECE28776514B1A8D4A98D10228`
- 更新日期：2026-09-18
- 版本类型：Windows 便携客户版
- 源文件未单独拆分为开发仓库；客户包按已验证的“拷贝版本”整体提供。
