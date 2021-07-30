# HwcPlayer-CMake
四川大学2021暑期实训项目-音乐播放器（CMake工程结构测试版）

本repo为另一个项目-HwcPlayer (`https://github.com/Cybercalf/HwcPlayer`) 的测试版本，旨在测试可否将工程结构从VS项目改为CMake，以提升项目的层次感

整个测试与改编工作由原项目开发人员中的Cybercalf(`https://github.com/Cybercalf`)全权负责

## 相对于原项目的修改

1. 修改了头文件的引用路径

## 这次测试的收获

1. 去除了头文件的冗余引用
2. 修改时间处理模块的源文件名称，以解决编译器不区分大小写、混淆不同文件而可能导致的意外情况

## 注意事项

1. 推荐使用VS构建项目，编译器请选择`msvc-x86`，使用64位会失败
2. 编译器请勿使用`gcc`

以下为正式项目的README.md中的内容

# HwcPlayer

本项目为四川大学2021年7月21日至30日的实训项目，是基于Visual Studio 2019平台开发的、基于命令行的音乐播放器，支持播放列表、播放器等功能。

## 构建

使用VS克隆此存储库后构建即可

```powershell
git clone https://github.com/Cybercalf/HwcPlayer.git
```

## 注意事项
1. **使用VS构建运行本项目时，请务必将“解决方案配置”设置为`Debug`，“解决方案平台”设置为`x86`，否则可能出现意想不到的错误！**
2. 本播放器可能不能打开大部分嵌有封面的音乐文件
3. 如果想让播放器加载歌词文件，请将歌词文件和对应的歌曲文件放置于同一文件夹下，保证两个文件同名（除了后缀名不同）
4. 本项目仅供学习交流之用，请谨慎用于其他（如商业）用途，具体请参见项目内的`LICENSE`文件

## 开发人员

Cybercalf(https://github.com/Cybercalf)

SCU-SE2020-WangAo(https://github.com/SCU-SE2020-WangAo)

dobole(https://github.com/dobole)

这是三人一起完成的小项目，缺少任何人，这个小程序都不会像现在一样完整，感谢每一位伟大的开发者！

## 关于

有关本次实训与该项目的更多信息，请参阅`doc`文件夹下的有关内容

虽然这个项目可能不会做过多维护，但也欢迎您为我们的工作提出宝贵意见

Cybercalf(cybercalf@163.com)
