![Logo](https://github.com/izhangguapi/ShawzinBot-Chinese/blob/a85d01dce7b50335bb2cf8d72c1a489a0b2d8011/ShawzinBot/Resources/Shawzin.png)

此软件是一个将MIDI输入信息或文件转换为星际战甲三线琴按键的程序。任何MIDI输入的信息（MIDI键盘、虚拟MIDI频道等）或[标准MIDI文件(SMF)](https://www.midi.org/specifications/category/smf-specifications)都可以使用这个程序。


# 下载
您可以点击[这里](https://github.com/zhangguapipi/ShawzinBot_Chinese/releases)下载最新版.

# 关于

### 这是一个什么软件？

ShawzinBot 是一个第三方软件，它可以将MIDI文件（.mid）或者输入的MIDI信息在星际战甲的三线琴模拟按键演奏出来。

### 安全吗？

ShawzinBot 不会以任何方式干扰游戏的正常玩法，也不会注入新代码或修改现有代码，更不会以任何方式篡改内存。因此它不能被归类为作弊软件，可以安全使用。

### 它是如何工作的？

ShawzinBot 它是基于 melanchall 的 [DryWetMIDI](https://github.com/melanchall/drywetmidi)库构建的，作用是加载一个 MIDI 文件并播放。ShawzinBot 会拦截每个音符，并根据音符在星际战甲按下不同的键组合来播放声音。ShawzinBot 还允许使用外部 MIDI 设备（键盘、合成器等）。

# 入门
它可以处于计算机中的任何位置且无需安装，您只需双击exe程序即可！

## 用法

程序运行后，您会看到下面这个窗口：

[![主界面](https://pic.imgdb.cn/item/60e2bb2a5132923bf821660d.png)](https://pic.imgdb.cn/item/60e2bb2a5132923bf821660d.png)

在左上角有一个“文件夹”样式的按钮，您可以单击以打开用于播放的 MIDI 文件。选中所有音轨，单击播放并重新进入游戏。多条音轨可能会有放不出来的声音，您可以自行选择关闭某条音轨。

要使用外部 MIDI 设备，您所要做的就是从下拉菜单中选择是否并开始播放。如果您没有看到您的设备，只需单击下拉列表右侧的重新加载按钮。

*  MIDI 输入设备 - 基本上用不上。
*  MIDI 音轨 - 打开文件后一般是全选。
*  颤音 - 我也不知道有什么用，默认关闭。
*  音阶转换 - 关不会使音阶不能自动转换，默认开启。
*  播放速度 - 在游戏里面演奏音乐的速度，默认为1.0的速度。

# 鸣谢
* [@ianespana](https://github.com/ianespana) - 制作出国际版星际战甲三线琴演奏器。
* [@lilggamegenius](https://github.com/lilggamegenius) - 帮助找出游戏中的按键。
* [/u/T2k5](https://www.reddit.com/user/T2k5/) - 用于制作原始全键盘脚本。
