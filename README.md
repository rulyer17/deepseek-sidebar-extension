# DeepSeek 侧边栏

一个极简的 Chromium 浏览器扩展：点击工具栏图标后，在浏览器侧边栏中打开 [DeepSeek](https://chat.deepseek.com/)。

## 特点

- 不调用 DeepSeek API。
- 不读取或保存聊天记录、网页内容、账号信息或 Cookie。
- 不包含统计、广告、远程配置或第三方脚本。
- 不需要除侧边栏和 `chat.deepseek.com` 嵌入所需权限以外的权限。

## 安装

1. 下载或克隆本仓库。
2. 在 Chromium 浏览器打开扩展管理页并启用“开发人员模式”。
3. 选择“加载已解压的扩展程序”，选中本目录。
4. 点击扩展图标即可打开侧边栏，并在其中登录 DeepSeek。

## 隐私与安全说明

扩展本身不收集、不传输、不存储你的数据。登录和对话仍直接在 DeepSeek 网站内完成，适用 DeepSeek 自己的服务条款与隐私规则。

为让 DeepSeek 能在侧边栏的 iframe 中显示，扩展仅对 `chat.deepseek.com` 响应移除了阻止嵌入的 `X-Frame-Options` 与 CSP 响应头。这会降低该网站原本的防嵌入保护；如果你不接受这一取舍，请不要安装或启用本扩展。

本项目与 DeepSeek 没有隶属或授权关系。

详细数据说明见 [PRIVACY.md](PRIVACY.md)。
