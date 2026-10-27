# 俞羿辰 · 项目作品集

两个数据 / AI 应用项目的可展示版本：

| 项目 | 内容 |
|---|---|
| [美债 10Y-1Y 利差监控与日报](treasury-spread.html) | 把「利差到历史高位就买入」量化成阈值，用 AI Agent 每天 8:10 自动取数、计算、分级并推送；33 次运行记录，跟踪 53–82BP 区间 |
| [小红书 / 抖音双平台博主分析](xhs-analysis.html) | TikHub 抓取同一博主两个平台的 54 篇作品，做同题材配对比较：抖音放大 8.7 倍、小红书反超 6.8 倍 |

- 首页：`index.html`
- PDF 下载：`treasury-spread.pdf`、`xhs-analysis.pdf`
- 技术栈：纯静态 HTML/CSS，无构建步骤、无后端、无第三方 JS

## 本地预览

直接双击 `index.html`，或在本目录运行任意静态服务器：

```powershell
python -m http.server 8080
# 打开 http://localhost:8080
```

## 部署

推送到 GitHub 后，仓库根目录即可通过 GitHub Pages 访问。
若绑定自定义域名，在仓库里新建 `CNAME` 文件，内容为域名（如 `portfolio.example.com`）。

## 联系方式

俞羿辰 ｜ 上海 ｜ yu7067128@gmail.com
