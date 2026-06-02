# LuoYan's Claude Code Plugins Marketplace

Claude Code 插件市场，提供各种实用插件。

## 可用插件

| 插件 | 描述 | 版本 |
| --- | --- | --- |
| markitdown-plugin | 将各种文件格式转换为 Markdown，支持 OCR | 1.0.0 |

## 安装

### 添加市场

```bash
claude plugin marketplace add LuoYan-33/claude-plugins-marketplace
```

### 安装插件

```bash
# 安装 markitdown-plugin
claude plugin install markitdown-plugin@luoyan-plugins
```

### 更新插件

```bash
claude plugin update markitdown-plugin
```

## 插件详情

### markitdown-plugin

MarkItDown Plugin for Claude Code - 将各种文件格式转换为 Markdown，支持 OCR。

**功能特性：**
- 支持多种文件格式转换为 Markdown
- 支持 OCR 识别图片中的文字
- 提供 MCP 服务器，供 Claude Code 使用
- 提供 Skills，用于配置和操作
- 提供 Hooks，用于自动检测和转换文件

**使用方法：**

```bash
# 转换文件
/convert <文件路径>

# 配置 OCR
/ocr-config enable
/ocr-config set-key <API_KEY>

# 配置自动转换
/convert-config enable

# 查看日志
/convert-log
```

**项目地址：** https://github.com/LuoYan-33/MarkItDown-Plugin

## 许可证

MIT
