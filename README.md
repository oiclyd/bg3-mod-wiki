# 夜独整合包 Wiki

> 博德之门3 MOD整合包攻略站

本仓库是 [夜独整合包](https://space.bilibili.com/) 的开源 Wiki 项目，使用 MkDocs 构建，托管于 GitHub Pages。

## 在线访问

**https://oiclyd.github.io/bg3-mod-wiki**

## 本地预览

```bash
# 安装依赖
pip install mkdocs-material

# 本地预览
mkdocs serve

# 构建
mkdocs build
```

## 目录结构

```
.
├── docs/               # Wiki 文档内容
│   ├── index.md        # 首页
│   ├── ch1-start.md    # 新手入门
│   ├── ch1-bugs.md     # 注意事项与BUG规避
│   └── ...
├── mkdocs.yml          # MkDocs 配置文件
└── README.md           # 本文件
```

## 参与贡献

欢迎提交 Issue 和 Pull Request！

### 快速开始

1. Fork 本仓库
2. 克隆到本地：`git clone https://github.com/oiclyd/bg3-mod-wiki.git`
3. 创建分支：`git checkout -b fix/你的修改`
4. 修改文档
5. 提交更改：`git commit -m "描述你的修改"`
6. 推送分支：`git push origin fix/你的修改`
7. 提交 Pull Request

### 文档规范

- 使用 Markdown 格式编写
- 保持原有章节结构
- 图片放在 `docs/images/` 目录下
- 遵循 [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines)

## 免责声明

本整合包由B站UP主 **"在下夜独"** 制作发布，**永久免费**，任何付费渠道均为盗传。

## 许可证

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
