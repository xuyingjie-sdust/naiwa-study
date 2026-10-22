# 奶蛙爱学 · AI 学习搭子

一个可以直接打开使用的 AI 学习陪伴单页应用。

![奶蛙爱学截图](screenshot.png)

## 功能

- 奶蛙 AI 学习搭子：讲知识点、规划复习、苏格拉底式引导
- 错题本：收录题目、解析、笔记、掌握状态，支持随堂小测
- 答对播放奶蛙笑声，可在设置或小测提示条里关闭
- 思考强度：自动 / 关闭 / 轻 / 标准 / 深度（DeepSeek thinking mode）
- 知识库：Word、PDF、图片 OCR、纯文本；文档库目标 512 MB（IndexedDB）
- LaTeX 公式：KaTeX 与字体已内嵌，断网也能渲染
- 手机端头像静态 PNG 回退，不依赖外部图片

## 直接打开

双击或用浏览器打开根目录的 `index.html` 即可。

第一次进入需要点「去设置钥匙」，填写自己的 DeepSeek API Key（或任意 OpenAI 兼容接口的 Key / Base URL / 模型名），然后保存。

## 文件

- `index.html`：完整应用（样式、图片、声音、公式库都已内嵌）
- `assets/icon.png`：站点图标
- `screenshot.png`：界面截图
- `NOTICE.md`：第三方素材与开源库说明
