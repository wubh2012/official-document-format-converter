# 公文格式中转工具

[在线使用](https://blog.aalmix.com/official-document-format-converter/)

一个纯前端的公文内容格式化工具。将已写好的文本按常见公文层级自动识别、预览，并可复制富文本或导出 Word，方便粘贴到 CMS、Word 或 WPS。

## 使用方法

1. 打开 [在线工具](https://blog.aalmix.com/official-document-format-converter/)。
2. 在左侧粘贴或输入公文内容；每一行会作为一个段落，空行会保留。
3. 在右侧查看识别后的格式；悬停段落可按需修正层级。
4. 选择“**一键复制**”将富文本粘贴到 CMS、Word 或 WPS，或选择“**导出 Word**”保存文件。

## 隐私说明

工具无需账号，也不会将文本上传到服务器。草稿仅使用浏览器本机存储保存；请勿在非受信任设备上处理敏感内容。

## 自动部署

推送到 `main` 分支后，GitHub Actions 会自动把最新版本部署到 GitHub Pages。也可以在 Actions 页面手动运行“Deploy GitHub Pages”工作流。
