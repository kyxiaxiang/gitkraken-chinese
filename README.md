# gitkraken-chinese

GitKraken的中文汉化补丁

# 说明

~~自从用上了GitKraken就爱上了，卸载了其他相关git的gui，它的界面非常合我的胃口，但是苦于官方没有中文简体，于是便有了汉化的想法.~~
本人写代码布局太过混乱，时常不写注释，每次肝出来Bug都会痛苦万分，所以投入GitKraken的怀抱，试图挽救我糟糕的编程习惯。
原项目:[https://github.com/yk47g/gitkraken-chinese](https://github.com/yk47g/gitkraken-chinese) 许久不更新，所以本人来更新~，如果有后续的版本可以提出来，我看到就会更新翻译~
# 更新

更新于2024.01.23 适配 9.5.1 版本。

# 原理

通过修改软件目录下English语言对应的一个json文件内容来完成汉化目的

# 操作步骤

将项目中的 strings.json 替换到 GitKraken 语言目录下的 strings.json.
(实际目录可能会不一样,但文件名一定是strings.json)

Windows: `%程序安装目录%\gitkraken\app-x.x.x\resources\app\src\strings.json` (x.x.x 是你的GitKraken版本)

Mac: `/Applications/GitKraken.app/Contents/Resources/app/src/strings.json`

Linux: `/usr/share/gitkraken/resources/app.asar.unpacked/src` (感谢[@lyydhy ](/lyydhy ) 10.31补充 Gitkraken是deepin 通过deb 安装的) 

Linux: `/opt/gitkraken/resources/app.asar.unpacked/src/strings.json` (Arch Linux AUR 安装的路径在这)

重启GitKraken.

# issue

GitKraken有的版本目录不一样，应该是以下目录：

Windows: `%程序安装目录%\gitkraken\app-x.x.x\resources\app.asar.unpacked\src\strings.json` (x.x.x 是你的GitKraken版本)

Mac: `/Applications/GitKraken.app/Contents/Resources/app.asar.unpacked/src/strings.json`
