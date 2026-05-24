# Logistic0825.github.io

个人主页源码，基于 GitHub Pages 托管。

**在线地址**：`https://logistic0825.github.io`

---

## ⚠️ 重要提醒

- **不要上传 `2026大模型算法简历.pdf`** 到本仓库，避免个人信息泄露。
- 所有个人信息请在 `index.html` 中手动替换占位符后，再推送。

---

## 🚀 部署步骤

### 1. 在 GitHub 创建仓库

登录 GitHub，新建一个仓库：

- **Repository name**：`Logistic0825.github.io`
- **Public**（必须公开才能免费使用 GitHub Pages）
- 不要初始化 README（本地已有）

### 2. 本地推送到 GitHub

打开终端，进入本目录：

```bash
cd /Users/logistic/Documents/AI/LLM/project/HomePqge

# 初始化 git（如果还没初始化）
git init

# 添加文件（注意不要添加简历PDF！）
git add index.html style.css README.md
git commit -m "init: personal homepage"

# 关联远程仓库（把下面 URL 换成你实际的仓库地址）
git remote add origin https://github.com/Logistic0825/Logistic0825.github.io.git

# 推送
git branch -M main
git push -u origin main
```

### 3. 启用 GitHub Pages

进入仓库 → **Settings** → **Pages** → **Branch** 选择 `main`，点击 Save。

等待 1-2 分钟，访问 `https://logistic0825.github.io` 即可看到主页。

---

## 📝 自定义内容

编辑 `index.html`，替换以下占位符：

| 占位符 | 替换为 |
|--------|--------|
| `你的昵称 / 姓名` | 你的真实昵称或姓名 |
| `你的GitHubID` | 你的 GitHub 数字 ID（可选，不影响使用） |
| `关于我` 段落 | 你的个人简介 |
| `技术栈` 标签 | 你熟悉的技术 |
| `项目/论文` 卡片 | 你的实际项目链接和描述 |

头像已配置自动拉取 GitHub 公开头像，无需手动设置。

---

## 📁 目录结构

```
.
├── index.html      # 主页内容
├── style.css       # 样式文件
└── README.md       # 本说明
```
