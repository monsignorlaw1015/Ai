# AI资讯日报 - GitHub Pages

这是AI资讯聚合系统自动生成的每日AI资讯网页。

## 访问方式

- **最新资讯**: [index.html](index.html)
- **历史归档**: 按日期访问，如 `2026-01-06.html`

## 内容来源

本站资讯来自以下渠道：

### 社交媒体
- Twitter/X (@OpenAI, @AnthropicAI, @GoogleAI, @ylecun, @karpathy 等)
- Reddit (r/MachineLearning, r/artificial, r/OpenAI)

### 聚合社区
- Hacker News

### 官方博客
- OpenAI Blog
- Anthropic News
- Google AI Blog
- 机器之心
- 量子位

### 学术前沿
- arXiv (cs.AI, cs.LG, cs.CL)

## 特色功能

- ✅ 中英文对照展示
- ✅ 智能热度评分
- ✅ 响应式设计
- ✅ 每日自动更新

## 部署到GitHub Pages

### 1. 创建GitHub仓库

```bash
# 在GitHub上创建一个新仓库，例如：ai-news-aggregator
```

### 2. 配置远程仓库

```bash
cd /home/ubuntu/ai-news-aggregator/docs
git remote add origin https://github.com/YOUR_USERNAME/ai-news-aggregator.git
```

### 3. 推送代码

```bash
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
```

### 4. 启用GitHub Pages

1. 进入仓库的 Settings
2. 找到 Pages 设置
3. Source 选择 `main` 分支
4. 目录选择 `/ (root)`
5. 点击 Save

### 5. 访问网站

几分钟后，您的网站将在以下地址可用：
```
https://YOUR_USERNAME.github.io/ai-news-aggregator/
```

## 自动化部署

系统会在每天早上6:50自动：
1. 采集最新AI资讯
2. 生成HTML页面
3. 提交到Git仓库
4. 推送到GitHub（如果配置了远程仓库）

## 更新配置

编辑 `/home/ubuntu/ai-news-aggregator/config/config.yaml` 中的 `github.base_url` 为您的实际GitHub Pages地址。

---

由 AI资讯聚合系统 自动生成 | [项目源码](https://github.com/YOUR_USERNAME/ai-news-aggregator)
