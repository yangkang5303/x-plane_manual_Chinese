第五章 在x-plane里面飞行

x-plane是个飞行模拟器，一个典型的飞行大概包括以下全部（或者部分）步骤
选择一个飞行器
寻找一个地点（飞机场，离飞机场不远即将降落或者随机某个地方）
设置天气与时间
开飞！
除此以外，你在飞行前或者飞行过程中，还可以利用一些模拟器的功能，这些功能包括使用飞机面板上的仪器，切换你的视角，虚拟化你的飞行（二维或者三维），以及创建一些记录文件等和别的飞友分享你的成果。
5.1 打开一个飞行器
当你第一次打开x-plane，系统自动载入默认机型，再次之后，系统将默认打开你上次退出模拟器之前使用的飞机。
1.移动鼠标到x-plane顶部，出现菜单栏
2.选择Aircraft-Open_Aircrft
3.再弹出的对话框顶部是一个下拉菜单，显示了你当前正在看的目录（文件夹）的名字（一开始你看到的是打开的飞机的目录），这些菜单是分层的，最顶部的是x-plane总目录（下层目录被上层目录包含）
例如，你打开的是F22战斗机 你在点开下拉菜单你就会看到
X-System folder
Aircraft
Fighters
FA 22 Raptor
4.点击 Aircraft文件夹，进入飞行器主目录
5.飞行器不同的类别分别放在不同的文件夹里面，点击你感兴趣的飞行器
例如general aviation craft（一般飞机）, gliders（滑翔机）, helicopters（直升机）, seaplanes(海上飞机) Experimental(实验性的) Radio Control（遥控飞机）等等。
6.现在左下放的格子里面就是这个类别的全部飞机了，双击进入。
7.x-plane飞机文件，是acf为结尾的文件，选中看预览图（有的没有），双击载入这个飞机（在最近的跑道）

5.1.1 选择涂装
把鼠标移动到菜单栏，点Aircraft-open livery,如果有可选涂装，你可以选择，然后重新载入这个新涂装。

5.2 选择机场或者地点
X-plane的飞行器可以放置在虚拟地球的任何一个地方，跑道，停机坪，空中，或者是离跑道3海里，即将降落。
要选择一个机场，首先移动光标到顶部，点“Location”选择“Global Airport”你可以使用名字或者ICAO来搜索数据库里面的飞机场（目前超过32000个）。
选择机场 的对话框分为三个部分，上方左边是每个机场的列表，左边是名字，右边是机场标识。再往右是机场的鸟瞰图。下面是快速开始，“take off”栏（最左边） 将会把你的飞机传送到指定的跑道，在这些按钮的右边是“Fianl Approach”的一些按钮，可以把飞机传送到离机场指定距离的空中。最后”Ramp Start”的按钮可以把飞机传送到指定跑道起飞。
要搜索机场，可以输名字或者ID号。比如搜索“KLAX”和“Los Angeles Intl”效果是一样的,你甚至可以输入“Los Angeles”然后往下翻，找到洛杉矶国际机场。
也可以在全列表的情况下按方向键向下。找到想要的机场，点一下使之高亮，然后点“Go to this airport”.
注意，如果你选择的机场周围没有安装地景，你的跑道将被海洋所包围，

5.2.1 选择地点的其他方法
1.Location-Get Me Lost（让我迷路）
2.Location-planet map 出现一个3D 的地球，自己点击地球上的任何一处将把飞行器放到最近的一个机场，点击上方那个的叉叉，不做任何改变。

5.3 改变环境
环境包括 天气，时间，日期，都可被修改。
5.3.1
X-plane的天气模拟有高度的定制性和真实性。有四种设置天气的方式
1.静态天气，在版本10之前的许多人都使用这个选项
2.随机天气，随机产生云层，温度，压强。
3.自定义天气，甚至可以用鼠标在需要云的地方“画”云
4.真实天气，从互联网上下载数据，让系统模拟这个天气。
移动 光标点击 Environment-Weather来设置

5.3.1.1 设置统一的，静态天气（全世界的）
点击 set weather uniformly for the whole world
cat-III,设置为第三类ILS（仪表降落系统），极其糟糕的天气，可见度和最高飞行高度为0，
cat-II,第二类ILS，可怕的可见度和安全高度。
cat-I,第一类ILS，可怜的可见度。
n-prec，会造成降落的不精准，3英里可见度，400英尺安全高度。
MVFR，VFR（目视飞行规则）的临界天气状况，可见度4英里，安全高度1500英尺
VFR，可以很好地目视飞行，晴朗的天气。
CAVOK 天气很好，飞行员们称之为“CAVU”意思是晴好，可见度无限远。

下面的选项可以快速自定义
visibility 可见度
precipitation压强
thunderstorms 雷暴天气的可能性
turblnc风，乱流
左下角是最近机场的气温和气压（海平面）
中间控制风 分三层，可以拖动改变风向。
窗口右上角的点击进入 thermal tops（上升极限）, thermal coverage（上升范围）, and thermal climb rate（上升率）这些对飞行滑翔机特别有用，不过普通飞机也要注意，控制自己的飞机不要被下降气流所害。
runway condition(跑道状况)可以设置为 干净 中等潮湿 非常潮湿
wave height 浪高，direction方向
Regenerate weather now (重新生产天气) 点击之后 根据设定参数生成需要的天气

5.3.1.2 设置随机，真实的天气
和上面一样进入菜单，选择set random and only semi-controlled weather patterns
左边显示
Coverage  云层覆盖
Intensity 暴风雨
Temperature 温度
System size 小的天气系统还是大的天气系统
Randomness  随机性
Regenerate weather now (重新生产天气) 点击之后 根据设定参数生成需要的天气
5.3.1.3
用鼠标来画天气
5.3.1.4 下载真实天气
选择grab real weather from the net
给Download Real Weather file ‘METAR.RWX’ from the net 打勾，系统自动下载你所在地的天气，可以选择下载节奏，或者随时点击Download right now立即下载

5.3.2 设置时间和日期
移动鼠标到Environment-Date&Time，用鼠标来拖动本地时间或者UTC时间，注意极昼和极夜。
点选always track real date and time让x-plane系统与你的电脑时间同步。

5.4 怎么飞？
你的处女飞最好驾驶一架相对简单的飞机。C-172就是个很好的选择，世界上百万记的飞行员就是这么做的。
在开始飞之前，配置好你的控制设备（键盘，鼠标，还是摇杆，更高级设备？）
怎么用鼠标点出十字来控制，我不再赘述。

C-172的起飞过程如下：
先少加油门(F2)，当油门加到一半的时候松开停机刹车（b），继续加油门，如果飞机稍微左右偏移，就用yaw轴修正（单螺旋飞机容易往左偏）。
学着让飞机一直在跑道上跑，C-172也可以在草地上（跑完这个跑道也没关系，继续跑）。修正一下参数之后，往后拉操纵杆。（C-172在60节可以拉），一旦飞机离开地面，稍微往前推，放低机头来获得一些速度。到达80节的时候再往后拉，继续爬升。用着样的方法爬升可以避免失速（stall).
注意：如果坠机导致飞机受损严重，x-plane会重新在最近的一个跑道打开飞机，（这也解释了为什么会出现在草地跑道的现象:-)），如果不严重，飞机就停在那里冒烟。
请手动点击Aircraft-Open aircraft，要是在真实世界也这么方便就好了。

5.5 使用仪器和航空电子设备

在机舱视角里面，鼠标可以用来控制仪器（就像飞行员用手来操作飞机按钮一样）
要按按钮，鼠标 点击—释放，操作开关（如起落架）也是一样。记住：键盘“G”也可以用来放下，收起落架。
要调整旋钮 移动光标到旋钮的左边（一般是减号）点击以减小，右边（加号）来增加。要快速旋转，连续点击！
要想知道这个开关或者旋钮是什么作用，点击菜单About，选中Show instrument instructions in the cockpit 那么光标在某一按钮停留的时候就会有标签（告诉你这个是神马）。

5.5.1无线电旋钮参考意见

 真实的航空无线电设备通常使用双层旋钮，大旋钮作用小数点左边的整数，小旋钮作用小数点右边的（小数）。例如要调节COM1通信频率为128.00MHz，调节大旋钮到128.然后调节小旋钮，直到小数部分出现00.
X-Plane也是同样的方法，当把鼠标悬浮在旋钮上方的时候 就会在旋钮左边出现两个逆时针的半圆箭头，右边出现两个顺时针的半圆箭头，物理上靠近旋钮的箭头比外圈的小些，大的调节整数部分频率，小的调节小数部分的频率。

5.6使用不同的视角

你可以使用View menu里面的选项来切换视角，或者使用键盘的快捷键,注意：菜单的选项里面恰好包含了键盘快捷键的用法，例如，要切换到forward view, 按W键, 向左转45度，按Q 键.
使用这两个方法的切换视角，会在你当前所在的视角引起效果。
例如，你可以先进入驾驶舱视角，看着你的仪表盘，或者你切换到最近的一个ATC塔的视角，看着你的飞机。
你选定一个视角之后，你可以作前后左右的移动，旋转或者缩放。
大多数情况下，前后移动比缩放更需要。
系统提供两种3维驾驶舱视角，其中一种可以按下Shift + 9 ，这种只能用键盘来控制左右看，这样就可以让鼠标来随便点击按钮，而不会影响到视角；另一种按下Shift + 0 你的鼠标到哪里，你的视角就会转向哪里。在两种方式下，键盘的view类快捷键都是有效的。

5.7 让x-plane的飞机自己飞

x-plane可以使用人工智能，让一驾飞机自己起飞，然后飞来飞去。
激活这个功能，把光标移动到菜单栏，选择Aircraft-A.I. Flies Your Aircraft.
在人工智能接管你的飞机的时候，你可以做许多事情：例如放下起落架，收放襟翼，减速板，甚至让引擎停转！这个时候，你可以练一练调节无线电。
你也可以让人工智能控制你的视角，打开方法：光标移动到菜单栏，选择Aircraft-A.I. Flies Your Views。

5.8得到快速帮助的方法

你在x-plane里面执行简单的任务的时候，如果想得到简明快速的帮助，可以光标移动到菜单栏，选择About-Instructions.将出现“Flight Controls,（飞行控制）” “Cockpit Control,（驾驶舱控制）” “Keyboard,（键盘）” “ATC,（空管）” 以及 “Tech Support（技术支持）”这些选项卡。
勾选Show mouse click regions in the cockpit复选框可以打开驾驶舱的鼠标悬浮简明帮助。

5.9 保存和分享你的飞行经验

x-plane提供了许多保存和分享的方法
• Situations（快照）,记录当前的地点，环境状况，使用的机型等
• Replays（回放）, 一个生成一个只能由x-plane播放的“记录”，回放可以改变视角，适合用来做录像再传到视频网站让飞友们欣赏。
• Movie ﬁles（视频文件）,从你开始录到你停止录制之间的，屏幕上的画面总和，可以直接拿视频播放器播放。
• Screenshots（屏幕截图）你懂的。
尽情分享你的作品吧。

5.9.1 创建一个可以反复使用的快照

快照是一个只能被x-plane正确读取的文件，记录了保存那一刻的所有的变量或参数
要保存一个situation ：把光标移动到菜单栏，选择File-Save Situation. 默认情况下，快照将保存在这个文件夹：
X-Plane 10/Output/situations/
知道这个目录的重要性非常重要，这样你就可以反复练习某一个进近，或者覆盖掉一个不要的快照，和别人分享，只需要把这个后缀名为“.sit”的文件拷贝到别人电脑上（用x-plane打开）。
要打开一个situation ：把光标移动到菜单栏，选择File-Load Situation.找到那个文件，双击。
5.9.2 创建一个回放

replay 即回放，是一个文件，从你上次载入一个飞行器，抑或你降落在某机场，直到你按下“Save Replay”，这个过程，全部记录下来了，这个“全息电影”的信息太多了，以至于你用x-plane载入回放的时候，你可以变换视角来观看每一处细节。
replay的保存的文件是“.smo”为后缀名的。可以和飞友分享。
如何保存replay:把光标移动到菜单栏，选择File-Save Replay,文件默认保存在
X-Plane 10/Output/replays/

5.9.3 保存为视频

除了保存为只能用x-plane读取的回放的文件之外，可以保存为可以普通视频文件，使用quicktime来录制屏幕，也可以使用屏幕录像专家等win平台的录制软件，当然，我也不反对使用相机或者摄像机拍摄。

5.9.4 截屏
在游戏的任何时刻按下 Shift + 空格,这些图片后缀名为png。在x-plane的主目录或者是桌面上，自己找找看。

5.10 可视化和回放你的飞行

你可以在你当前位置打开可视化效果，有几种方式：在二维地图里面看你的飞行路线，或在主飞行模拟器中打开并观看3D飞行轨迹。
你也可以在回放里面 “倒带”“快进”（有专门按钮），甚至，你可以把真实飞机的数据转换成x-plane能够读取的文件（FDR文件），在虚拟世界里，回放真实世界飞机的飞行记录。cool~

5.10.1查看飞行轨迹
反复按Ctrl + P，可以看见飞机多了“尾巴”（在机舱外部视角看），再按可以看见不同的表达方式，再按这些线条就会消失，再按又出现，你可以把光标移动到菜单栏，选择Aircraft-Reset 3-D Flight Path重置飞行轨迹，或者按Alt+空格 来重置。第7章详细讨论这个轨迹。

5.10.2 回放的控制

You can replay your ﬂight, from the last time you loaded an aircraft or a location up to your
current location, by toggling the replay mode on. This can be done either by pressing Ctrl + ‘r’ or
by opening the Aircraft menu and clicking Toggle Replay Mode. In the top of the window, you will
see shuttle controls to (listed left to right):
你可以重新播放你的飞行（从上一次你在如这个飞行器开始或者取决于你现在所处的位置）打开回放功能（按Ctrl+r，载入某一个replay文件）之后，你将会看到控制键：
stop playback,——停止
play backward faster than real-time,——快退
play backward at real-time speed,——回退（一倍速度）
play backward slower than real-time,——慢退
pause playback,——暂停
play forward slower than real-time,——慢放
play forward at real-time speed,——播放
play forward faster than real-time, and stop playback.——快进到结束，并停止

此外，你可以拖动进度条，来快速定位（和视频播放器类似）
退出replay方法:Alt+,或者使用菜单，再次点击Aircraft-Toggle Replay Mode once .

5.10.3 使用飞行记录仪的数据来回放

最后一种可视化飞行时载入飞行记录仪的数据回放。
这是个有效并且首选的用来调查空难事故和重现真实飞行的方法：从“黑匣子”里面取出飞行记录（FDR，有某种格式的纯文本文件，x-plane可以读出你自己写的FDR文件），载入模拟系统进行回放（replay）。
做法：把光标移动到菜单栏，选择File-Load Flight Data Recorder File.
打开某FDR后，对话框的下半部分列出了一些数据头（文件版本，飞机型号，尾号等等），还有一些可以用数据表述的参数（用百分数表示？）这其中包括：时间戳，飞机的地点（经纬度，高度），指示空速等。
拖动滑条来看浏览数据，鼠标单击可以看某一参数的描述，注意，如果某个“状态”下，飞机没有给出一个具体的参数（如引擎压力），数据文件必须有一个预设数值来占位。在格式化好FDR文件之后。你就可以载入x-plane,如同上面提过的replay控制来回放。

5.11 观看牛顿视角

x-plane模型可以把飞机分成一块一块的，然后观看每一块部件上的受力情况，把光标移动到菜单栏，选择Special-Show Flight Model,或者直接按Ctrl+M快捷键，把视角切换到舱外，
每一块部件上的受力情况一目了然，如果在天气选项打开风和乱流，你甚至可以看见
机身周围有真实的速度矢量流，这些都是与飞机真实互动的力（绿色的线条），这里的线条都是真实模拟的，绝不是花把式。
	绿色的线条表示某一部位产生的升力，长度越长，力越大；红色的亦是如此，表示拖拽力；黄色的表示垂直控制板面的举力。