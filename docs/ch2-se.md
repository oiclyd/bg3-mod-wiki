# SE控制台代码

### A. 移除威尔的恶魔形态，恢复原来外观


```
Osi.RemoveTransforms("S_Player_Wyll_c774d764-4a17-48dc-b470-32ace9ce447d")
```


效果：会把威尔的"恶魔变身外观"移除掉；威尔会恢复到变身前的外观和头像；如果你用捏脸/自定义改过威尔，这里会恢复到你自定义后的样子。


### B. 移除影心的白发新发型，恢复老样子


以下三行都要输入并回车，缺一行都可能不会生效：


```
Osi.RemoveCustomVisualOvirride("S_Player_ShadowHeart_3ed74f06-3c60-42dc-83f6-f034cb47c679", "e05b0f79-d3af-41eb-b0b2-1164b6f0debf")
Osi.RemoveCustomVisualOvirride("S_Player_ShadowHeart_3ed74f06-3c60-42dc-83f6-f034cb47c679", "c7f78eb7-6858-4f02-836b-d8c8b56c34fc")
Osi.RemoveCustomMaterialOverride("S_Player_ShadowHeart_3ed74f06-3c60-42dc-83f6-f034cb47c679", "831f8c8a-4101-4265-ad55-1a57217d2af7")
```


效果：移除影心的"新白色斜刘海发型"和那一套染发材质；让影心回到原本的黑发老发型（或你之前自定义的发色/发型）。


### SE控制台使用方法


1. **什么是SE控制台？** 当你用Script Extender（脚本拓展器）启动博德之门3时，会自动弹出一个黑色的命令窗口，名为"BG3 Script Extender Debug Console"，这个黑色窗口就叫做SE控制台。
2. **怎么切到SE控制台？** 保持游戏在运行，不用退出到主菜单。把控制台切到最前面，用鼠标点一下黑色窗口内部，确保键盘输入焦点在这个窗口里。
3. **怎么输入命令？** 先按一次Enter（回车键），让光标跑到新的一行。把命令一行一行复制粘贴进去，每粘贴一行按一次Enter执行。执行成功不会有明显提示，只会在窗口里多出几行日志文字，这是正常的。
