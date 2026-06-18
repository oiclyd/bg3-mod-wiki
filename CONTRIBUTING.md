# 贡献指南

感谢你对 夜独整合包 Wiki 的兴趣！本指南将帮助你快速参与贡献。

## 如何贡献

### 报告问题

如果你发现文档中的错误或有改进建议：

1. 点击页面右上角的 **编辑此页** 按钮
2. 或者前往 [GitHub Issues](https://github.com/你的用户名/仓库名/issues) 提交问题

### 直接编辑（推荐小修改）

1. 在 GitHub 上打开要编辑的 `.md` 文件
2. 点击右上角的铅笔图标 **编辑此文件**
3. 进行修改
4. 滚动到底部，填写修改说明
5. 选择 **创建新分支并开始拉取请求**
6. 提交 Pull Request

### 本地编辑（推荐大修改）

```bash
# 1. Fork 本仓库（在 GitHub 页面上点击 Fork）

# 2. 克隆你的 Fork
git clone https://github.com/你的用户名/仓库名.git
cd 仓库名

# 3. 安装依赖
pip install mkdocs-material

# 4. 本地预览
mkdocs serve

# 5. 创建新分支
git checkout -b fix/描述你的修改

# 6. 修改文档...

# 7. 提交更改
git add .
git commit -m "fix: 修正XX职业的装备描述"
git push origin fix/描述你的修改

# 8. 在 GitHub 上提交 Pull Request
```

## 文档规范

### Markdown 格式

- 使用标准 Markdown 语法
- 标题使用 `#` 符号，`#` 为页面标题，`##` 为章节，`###` 为小节
- 代码块使用三个反引号 ``` 包裹
- 表格使用标准 Markdown 表格语法

### 内容规范

- 保持客观、准确的描述
- 技能/装备数据请与游戏内实际效果核对
- 攻略内容请基于实际游戏体验
- 避免剧透内容（如需剧透请使用折叠块）

### 文件组织

```
docs/
├── index.md              # 首页
├── ch1-start.md          # 新手入门
├── ch1-bugs.md           # 注意事项与BUG规避
├── ch1-corrupt.md        # 坏档原因分析
├── ch1-honor.md          # 荣誉模式风险
├── ch1-drop-overwrite.md # 掉落覆盖说明
├── ch1-exp.md            # 30级经验曲线参考
├── ch2-mod.md            # MOD工具与教程
├── ch2-name.md           # 管理器显示MOD中文名
├── ch2-mp.md             # 联机说明
├── ch2-transmog.md       # 装备幻化
├── ch2-mcm.md            # MCM角色预设导入导出
├── ch2-se.md             # SE控制台代码
├── ch3-faq.md            # 常见问题汇总
├── ch4-miefa.md          # 职业攻略-灭法之影
├── ch6-exile.md          # 种族攻略-谪仙
├── ch7-divinity.md       # 专长攻略-封神之路
├── ch8-talisman.md       # 装备攻略-12符咒
├── ch9-summon.md         # 召唤攻略
├── ch11-dota.md          # 难度攻略-Dota难度
├── ch12-alchemy.md       # 炼金术
└── ch10-mod.md           # 自选模组说明
```

## 审核流程

1. 提交 Pull Request 后，维护者会进行审核
2. 如有修改意见，请在分支上继续提交更改
3. 审核通过后，更改将被合并到主分支
4. GitHub Pages 会自动部署更新

## 社区规范

- 保持友善和尊重
- 接受建设性的批评
- 关注社区利益

## 需要帮助？

如有疑问，请在 [Discussions](https://github.com/你的用户名/仓库名/discussions) 中发起讨论。
