
https://update.code.visualstudio.com/commit:e5a624b788d92b8d34d1392e4c4d9789406efe8f/server-linux-x64/stable


linux
0913 b1aa 4319 1d8a f0cc b4a1 33d9 a8d7 c1a8 1d69
win
c926 ed62 28f8 ebbf c9a3 6d40 2e5e 5a18 6102 4da3


linux
https://update.code.visualstudio.com/commit:0913b1aa43191d8af0ccb4a133d9a8d7c1a81d69/server-linux-x64/stable
win
https://update.code.visualstudio.com/commit:c926ed6228f8ebbfc9a36d402e5e5a1861024da3/server-linux-x64/stable


1、前提：已安装 Visual Studio Code, 并且已将其添加到了环境变量 path 中；
2、打开cmd，输入code --help, 显示帮助信息
3、启动时，指定插件安装路径
在 VS Code 的安装路径下创建一个 “extensions” 目录
启动一：
在 cmd 中, 输入命令：code --extensions-dir D:\VS Code\extensions
回车，启动 VS Code，加载指定路径下的插件，然后安装的插件会放到指定的目录
启动二：
（windows 系统）
在 VS Code 的快捷方式图标，右键-->属性
在打开的 VS Code 的属性，如上图，修改目标（T）的文本框中输入 "D:\VS Code\Code.exe" --
extensions-dir "D:\VS Code\extensions"


