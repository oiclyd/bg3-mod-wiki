# Mod不生效 + Mod自动跑管理器右边

1. 首先检查你的C盘Mods文件夹里面是否套娃（Mods里面还有Mods之类的情况）
2. 然后检查你的C盘Mods文件夹里面是否存在json文件，如有请删除，然后管理器排序好，启动游戏
3. 如果无效请尝试切换游戏启动项（比如本来用DX11启动，就切换另一个启动）
4. 如果无效请关闭杀毒软件，以管理员身份运行管理器
5. 如无报错：一般与mod无关

#### 方法一

检查管理器Settings -> Open preferences（第三栏第一个选项）

- 检查 Game Data Path 是否为：`/Steam/steamapps/common/Baldurs Gate 3/Data`
- 检查 Game Executable Path 是否为：`Steam/steamapps/common/Baldurs Gate 3/bin/bg3.exe`

#### 方法二

删除C盘`AppData\Local\Larian Studios\Baldur's Gate 3\PlayerProfiles\Public`里面的modsettings，然后在mod管理器里面export导出。

如有报错：检查mod排序和冲突
