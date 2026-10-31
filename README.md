# Sora

> 穹
> Notes in bone white and ink.

**Sora** 是一个极简、冷峻、注重文字阅读体验的 Jekyll 主题。剔除一切多余的装饰，只留下骨骼般的结构与纯粹的内容。

![Sora Preview](https://via.placeholder.com/1200x600/F3F5F3/473D40?text=Sora+Theme+Preview)

## Features (特性)

- **Bone & Ink**：极致的纸张噪点肌理与淡墨配色。
- **Minimal & Sharp**：硬朗的 1px 细边框与绝对克制的网格系统。
- **Typography**：针对中文排版优化的 `Noto Serif SC` 与无衬线体混排。
- **Responsive**：完美适配移动端与桌面端，长代码和表格自动折叠滚动。
- **Pure CSS**：没有复杂的 JavaScript 依赖，加载极速。

## 快速开始 (基于 GitHub Pages)

1. Fork本仓库
2. 在你的仓库中，打开 `_config.yml`，修改成你自己的信息：
   ```yaml
   title: 你的博客名
   description: 你的博客描述
    author: 你的名字
   ```
3. 前往仓库的 **Settings -> Pages**。
4. 在 **Build and deployment** 下，**Source** 选择 `Deploy from a branch`。
5. **Branch** 选择 `main`，文件夹选择 `/(root)`，点击 **Save**。
6. 等待 1-2 分钟，访问 `https://你的用户名.github.io/你的仓库名/`，你的博客就上线了！

## 如何写文章

1. 删除 `_posts` 目录下的示例文章。
2. 在 `_posts` 文件夹中新建一个文件，文件名格式必须为：`年-月-日-标题.md`（例如：`2026-11-01-hello-world.md`）。
3. 在文件开头添加以下配置：
   ```yaml
   ---
   layout: post
   title: 我的第一篇文章
   tags: ["日常", "随笔"]
   description: 这是首页卡片上显示的摘要描述。
   ---
   ```
4. 在下方使用 Markdown 语法开始写作。只要推送到 GitHub，网页就会自动更新。

## 🛠️ 本地开发 (可选)

如果你需要在本地预览和修改样式：

```bash
# 克隆你的仓库
git clone git@github.com:你的用户名/你的仓库名.git
cd 你的仓库名

# 安装依赖
bundle install

# 启动本地服务器
bundle exec jekyll serve
```
打开浏览器访问 `http://localhost:4000`。

## License
本项目采用 [BSD 3-Clause License](LICENSE) 协议。