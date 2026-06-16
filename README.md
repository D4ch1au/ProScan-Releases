# ProScan

ProScan 是一个面向资产发现、子域收集、指纹识别与企业信息关联分析的 CLI 工具。

本仓库仅用于发布 ProScan 的公开二进制文件，不包含源码。请在 Releases 页面下载对应平台的二进制文件。

## 下载

- Windows x64: `proscan_windows_amd64.exe`
- Windows ARM64: `proscan_windows_arm64.exe`
- Linux x64: `proscan_linux_amd64`
- Linux ARM64: `proscan_linux_arm64`
- macOS Intel: `proscan_darwin_amd64`
- macOS Apple Silicon: `proscan_darwin_arm64`

## 运行

Windows:

```powershell
.\proscan_windows_amd64.exe -h
```

Linux/macOS:

```bash
chmod +x ./proscan_linux_amd64
./proscan_linux_amd64 -h
```

## 配置

ProScan 默认从用户主目录下的 `.proscan` 配置目录读取运行配置。首次运行会生成模板配置文件。