# WebStorm 使用文档

## [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#概述)概述

号称最好用的前端IDE，Win7 和 Mac 上各用了一段时间，感觉确实不错分享出来。版本上从8一直用到10，在设置上9到10有一次比较大的调整，下面的设置从10的使用中记录整理而来。WebStorm在下面简写为WS。

## [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#快捷键)快捷键

下面介绍的快捷键和上面皮肤和快捷键风格的设置有关，如果你和我设置的不一样会有很大的不同。第一批给出的快捷键是10个，以后每批不多于5个，因为一般人的短暂记忆量是3-7个，我记快捷键的方式是每天开始编码先看一眼快捷键，但是不多看3-5个足够了，一天的编码中尽量去用一般两到三天就不用刻意去想了基本可以达到肌肉记忆的层度。

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#1---基本)1 - 基本

**编辑窗口的常用操作**

*   撤销，Undo， Win:Ctrl + Z; Mac:Com + Z

*   恢复，Redo， Win:Ctrl + Shift + Z; Mac:Com + Shift + Z

*   查找，Find， Win:Ctrl + F; Mac:Com + F

*   在某一文件夹下查找内容，Find in Path， Win:Ctrl + Shift + F; Mac:Ctrl + Shift + F

*   替换，Replace， Win:Ctrl + R; Mac:Com + R，

*   格式化代码，Reformat Code， Win:Ctrl + Alt + L, Mac: Alt + Com + L

**对当前光标所在行 或者 选中部分做操作**

*   向下复制一行或一个代码块，Duplicate Line or Block， Win:Ctrl + D; Mac: Com + D

*   剪切，Cut， Win:Ctrl + X; Mac: Com + X

*   删除，Delete Line， Win:Ctrl + Y; Mac: Com + Y，需要注意的是选中字符所在的行会被删掉

*   上下移动行，Move Line Up/Down， Win:Alt + Shift + 上/下箭头;Mac:Alt + Shift + 上/下箭头

*   上下移动代码块，Move Statement Up/Down， Ctrl + Shift + 上/下箭头，大括号内的，块状注释等都是代码块，遇到代码块也会一次跳到上面。代码块的识别有时会和想象中的不一样，所以比较适合跨代码块移动单行

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#2---tab操作)2 - Tab操作

*   关闭当前的Tab，Close Active Tab， Win:Ctrl + F4; Mac:Com + F4

*   左右切换Tab，Select Previous/Next Tab， Win:Alt + 左右箭头; Mac:Ctrl + 左右箭头，但是这和Mac系统左右切屏的快捷键有冲突，另外左右切屏可以通过在触摸板上三指左右滑动来切屏，其实我平时也是这么用的，所以我禁用了系统切屏快捷键。禁用方式：系统偏好设置/快捷键/Mission Control/向左移动一个 space。

*   最大化编辑窗口(隐藏所有工具窗口)，Hide All Toll Windows Win:Ctrl + Shift + F12; Mac:Com + Shift + F12，我超级喜欢的快捷方式，可以让我专注的写好当前代码块

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#3----光标移动)3 - 光标移动

*   前后跳单词，Move Caret to Previous/Next Word Win:Ctrl + 左右箭头; Mac:Alt + 左右键

*   跳到行首行尾，Move Caret to Line Start/End Win:Home/End; Mac:Com + 左右箭头，其实这是Mac系统的快捷键也补充到这里

*   在下一行书写，Start Next Line Win:Shift + Enter; Mac:Shift + Enter，当你在一行的中间部分改完代码需要进行下一行书写时次快捷键可以一步到位。比移先将光标到行尾再Enter换行感觉要好得多，速度也快得多

*   在上一行书写，Start New Line Before Current， Win:Ctrl + Alt + Enter; Mac:Alt + Com + Enter

*   跳到指定行， Win:Ctrl + G; Mac:Com + G

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#4---折叠代码)4 - 折叠代码

*   折叠当前代码块，Collapse， Win:Ctrl + Num-; Mac:Com + Num-，Num-就是键盘顶部数字键旁边的减号

*   展开当前代码块，Expand， Win:Ctrl + Num+; Mac:Com + Num+

*   折叠全部代码块，Collapse All， Win:Ctrl + Shift + Num-; Mac:Com + Shift + Num-，这也是我超喜欢的一个快捷方式，如果代码写的规整，折叠起来可以看到代码的组织方式，在参考注释很容易找到对应的功能模块

*   展开全部代码块，Expand All， Win:Ctrl + Shift + Num+; Mac:Com + Shift + Num+

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#5---选中)5 - 选中

*   选中的超级扩展，Extend Selection， Win:Ctrl + W; Mac:Com + W，请原谅我给这个快捷键起这么夸张的称谓，因为这个快捷方式是我超级超级喜欢的一个，按一次选中一个单词，两次一行，三次一个代码块，太好用了！！

*   重命名，Rename， Win:Shift + F6; Mac:Shift + F6，这是一个有多张面孔的快捷键。在js代码中此快捷键是变量重命名，给变量起名真是一个费劲的事情，随着业务的变动变量名一定要跟着作调整，否则代码的寿命不好太长远；在html和css以及文档文件中，此快捷键重命名当前文件；在资源文件目录下，此快捷方式是给资源重命名，而且会智能同步引用。

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#6---粘贴)6 - 粘贴

*   粘贴，Paste， Win:Ctrl + V; Mac:Com + V，一个很普通的粘贴

*   从复制历史中粘贴，Paste form History， Win:Ctrl + Shift + V; Mac:Com + Shift + V，我超级喜欢的功能，有了它就不用反复的复制了

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#7---文件)7 - 文件

*   打开文件，File... Win:Ctrl + Shift + N; Mac:Com + Shift + N

*   保存全部，Save All， Win:Ctrl + S; Mac:Com + S

*   新建文件，New... Win:Alt + N; Mac:Alt + N，在当前文件同级或者选中的文件夹下

*   打开最近打开的文件，Recent Files Mac:Com + E，会给出一个最近打开的文件列表

## [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#设置)设置

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#1---基本设置)1 - 基本设置

*   打开设置

Win:File/Settings, 快捷键: Ctrl + Alt + S

Mac:WebStorm/Preferences, 快捷键: Com + ,

下面的配置默认都在“设置”中设置，不再多述。

*   皮肤

代码高亮是很必要的，个人喜欢配色柔和一点的皮肤，WS的皮肤设置分两层，第一层是大框架，第二层是编辑窗口。需要两个配合设置，不然可能出现外白里黑或者里黑外白这种诡异的界面。

第一层: Appearance & Behavior/Appearance ,在Theme下选风格，Win 和 Mac选项不一样，Win多一些，Darcula是都有的，Darcula偏黑色风格。两外建议把“Override default fonts”选中，个人认为Win下微软雅黑比较好，Mac下Baghdad字体比较好看，Size设置成14或16对眼睛好。

第二层：Editor/Colors & Fonts, 在Scheme选风格，个人同样喜欢Darcula这一风格，另外提醒一句只有把Scheme另存为自己的风格才可以修改其中的一些更详细的配置，详细配置的修改在下面第二批设置中作解释。

*   快捷键

KeyMap，可以选择快捷键整体的规则，支持了Visual Studio、Eclipse、NetBeans等IDE的快捷方式，个人建议Win下用Default，Mac下用Mac OS X。

在下面的搜索框可以搜索你想要的快捷键，跨系统或跨风格时想要找同一个快捷方式可以通过描述来查找。后面的放大镜可以通过快捷键查找描述。

下面的设置将快捷键分了组，Editor Action是编辑窗口中的快捷方式，Main menu是对文件、Tab、各种面板操作的快捷方式。

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#2---工程)2 - 工程

*   在新窗口打开工程

webstorm的一个缺陷就是不能在一个IDE打开多个工程，这也是它快的一个代价。如果一定要多窗口那就多IDE那就设置一下吧： Appearance & Behavior/ System Settings/ Project Opening / Open project in new window 在新窗口中打开webstorm

*   默认编码设置，Editor / File Encodings，IDE Encoding设置的是编辑器编辑的时候的时候按默认那种编码格式打开，Project Encoding设置的是新建一个项目此项目默认的编码格式，下面Default encoding for properties files设置上面选中的文件夹下新建文件时的默认编码格式。

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#3---代码格式)3 - 代码格式

**代码长度参考线**

真的不建议把一行代码写的太长，嵌套太深也是要避免的，毕竟代码是给人看的，偶尔交给机器执行以下，所以代码的可读性非常重要。所以就有了代码长度参考线。在 /Editor/General/Appearance 中 勾选Show right margin 考线出现，取消勾选参考线消失。参考线的位置其实是字符数量的体现，在 /Editor/Code Style 中 Right Margin 中调整字符数量，个人建议120。

**CSS空行**

默认CSS格式化之后会在两个样式块间加空行，去掉此空行的配置，Editor/Code Style/CSS/Other，将 Blank lines between blocks' 的值设为 0。

**MD文档默认换行**

MD文档默认不换行，可以在左边行号的位置右击勾选"Use Soft Wraps"，这种方式每次都要设置，还有一种一劳永逸的设置方法，Settings | Editor | General | Use soft wraps in editor

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#4---代码模板)4 - 代码模板

*   编辑新文件模板，Editor / File and Code Templates， 设置新建文件中的默认内容，也可以添加自己的格式模板

*   代码块模板，Editor / Live Templates, 代码块的模板，如果你写一个for循环还从左码到右那就太out了。定义模板的时候有几点注意：在最下面一行修改 applicable （适用范围），范围要尽量小，否则容易冲突；定义变量默认值的时候注意要加引号，否则手工输入必不可少；建议勾选 Reformat，这样就不用手动调整格式。

### [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#5---其他零碎)5 - 其他零碎

*   设置选中文字之后，点击双引号\单引号包围选中，Editor / General / Smart keys，勾选surround selection on type quote or brace

## [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#写在最后的牢骚)写在最后的牢骚

每天都在写代码，应该花点时间培养一下和IDE的感情，快捷方式，代码补全，插件，是几个重要考察的点。没有那个IDE绝对的好，熟练使用是关键。业务代码写的快一点才有时间研究新的东西，不然就沦落到一个经验用三年这种悲催的境地了。快速的写代码也是一种不错的感觉。

## [](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md#声明)声明

欢迎各方转载，但请注明出处： [https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md](https://github.com/longze/cellar/blob/master/web/articles/webstorm/main.md)
