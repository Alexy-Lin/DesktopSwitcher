🖱️ 一键切桌面 · SwitchDesktop
轻量级 AutoHotkey 工具，支持通过鼠标中键一键切换到左侧虚拟桌面。适用于 Windows 10/11，无需安装，即开即用。

📦 文件结构
plaintext
📂 SwitchDesktopTool
├── AHK.exe               ← 可执行文件，双击运行
├── AHK.ahk               ← 脚本源文件（供修改使用）
├── switchdesktop.ico     ← 托盘图标文件
├── 使用说明.txt          ← 中文使用文档
🚀 快速开始
运行工具 双击 AHK.exe 启动，托盘区将出现图标并提示“SwitchDesktop 已启动”。

切换桌面 按下鼠标中键（滚轮按下）即可快速切换到左侧虚拟桌面。

退出工具 右键点击托盘图标，选择“退出”即可关闭脚本。

🔧 开机自启动设置（推荐）
按下 Win + R，输入 shell:startup 并回车

回到本工具所在目录

右键拖动 AHK.exe 到启动文件夹

松开鼠标后选择“创建快捷方式”

✅ 设置完成后，每次开机将自动运行该工具。若移动程序目录，请重新添加快捷方式。

❌ 取消自启动
按下 Win + R，输入 shell:startup 并回车

删除名为 ahk.exe 的快捷方式即可

⚠️ 注意事项
请勿删除 switchdesktop.ico，否则托盘图标无法显示

如需修改快捷键或功能，请编辑 AHK.ahk，使用 AutoHotkey v2 打开

本工具仅支持 Windows 10/11 的虚拟桌面功能

🧠 技术说明
使用 AutoHotkey v2 编写，支持托盘菜单、快捷方式创建等功能

鼠标中键触发逻辑基于 SendMessage 切换虚拟桌面

可扩展为 GUI 工具或加入日志记录功能

📮 联系与反馈
如需定制功能、图标设计或脚本优化，欢迎提交 Issue 或联系作者。
