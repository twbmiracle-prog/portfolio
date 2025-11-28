# 个人主页 (Portfolio)

这是一个基于您的简历生成的个人主页网站。

## 📂 文件结构
*   `index.html`: 网站的主页面，包含您的个人信息、技能和项目经历。
*   `style.css`: 网站的样式文件，采用现代简约设计。

## 🚀 如何部署到 GitHub Pages

由于您的电脑上没有安装 `gh` (GitHub CLI)，您需要手动创建一个仓库并推送代码。请按照以下步骤操作：

### 第一步：在 GitHub 上创建仓库
1.  登录 [GitHub](https://github.com)。
2.  点击右上角的 **+** 号，选择 **New repository**。
3.  **Repository name** 填写 `portfolio` (或者您喜欢的名字)。
4.  确保选择 **Public**。
5.  **不要** 勾选 "Initialize this repository with a README"。
6.  点击 **Create repository**。

### 第二步：推送代码
打开您的终端 (Terminal)，确保您在 `/Users/mac/Documents/Agent BI/portfolio` 目录下，然后执行以下命令（将 `YOUR_GITHUB_USERNAME` 替换为您的 GitHub 用户名）：

```bash
# 初始化 git 仓库
git init

# 添加所有文件
git add .

# 提交更改
git commit -m "Initial commit"

# 关联远程仓库 (请替换下面的 URL)
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/portfolio.git

# 推送到 GitHub
git push -u origin main
```

### 第三步：开启 GitHub Pages
1.  回到 GitHub 仓库页面。
2.  点击 **Settings** (设置) 选项卡。
3.  在左侧菜单中找到 **Pages**。
4.  在 **Build and deployment** 下的 **Source** 选择 `Deploy from a branch`。
5.  在 **Branch** 下选择 `main` 分支，文件夹选择 `/ (root)`。
6.  点击 **Save**。

稍等几分钟，刷新页面，您就会看到您的个人网站链接了！
