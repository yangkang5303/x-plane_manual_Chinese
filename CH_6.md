第六章 x-plane的高级模拟

x-plane是迄今为止世界上最牛X的的飞行模拟软件，当然不能只是做一些简单的起飞，降落。她还可以用来做一些复杂的事情：例如，飞行日志，事件清单（checklist），设备的故障模拟，损坏模型的构建。

6.1 飞行日志

Each time an aircraft is ﬂown in X-Plane, the program logs the ﬂight time in a digital logbook. By
default, X-Plane creates a text ﬁle called “X-Plane Pilot.txt” in the 
每次运行x-plane，这个软件都会生成一个数字日记，名字叫 “X-Plane Pilot.txt”，默认存放在：
X-Plane 10/Output/logbooks
directory. Inside this text ﬁle are the following details of previous ﬂights:
目录下，文件记录如下详情：

Dates of ﬂights——飞行的日期
Tail numbers of aircraft——飞机的尾号
Aircraft types——飞行器类别
Airports of departure and arrival——飞离或者飞抵的机场
Number of landings——降落数
Duration of ﬂights——飞行时间
Time spent ﬂying cross-country, in IFR conditions, and at night——飞机在夜间用IFR飞过某州的时间
Total time of all ﬂights——所有的飞行时间

做法：移动鼠标到菜单栏，About-Logbook,点击Choose Pilot Logbook，观看某一日志；
或者按New Pilot Logbook按钮，新建日志。

6.2 和空管协作(ATC)

如果你不是仅仅想要飞一飞，而是想要训练真实世界的飞行规则的话，x-plane10的强大和真实性就体现出来了。注意：AI机总是会听从ATC指挥，即使你不听指挥，它们也会让着你。
要听到ATC的声音：请确保，声音已经打开。
所有的和ATC的互动都是在ATC窗口进行的，打开方式：Enter键，再按关闭。
为了能够听到空管的声音，你必须打开COM1通信无线电到特定频率，然后提出申请(requset)。填写飞行计划和任何控制是独立的，所以随时可以使用飞行计划。
但是，一旦飞行计划被提交了，你必须联系 放行，地面或者塔台（申请起飞许可）
一般顺序是这样的：申请放行——滑行许可——（当你到达hold short line，地面把你交给塔台）——起飞许可——起飞 起飞之后要变换频率来和ATC保持联系
注意：Local Map里面总是显示了一些你需要用到的无线电频率

在真实的世界里，ATC互动总是从提交飞行计划开始的，所以，你第一次按Enter的时候，会问你飞行计划是什么。鼠标点击那一行字，打开飞行计划对话框
你可以选择IFR（仪表飞行规则）或者VFR（目视飞行规则）


在实际世界里进行仪表飞行，必须告知ATC仪器等级，这样可以让空管随时监视你的飞行，而且可以给你的仪表降落系统带来方便（特别是在恶劣的天气）。
 VFR飞行计划，任何飞行员都可以提交申请，如果要飞抵的机场只能目视进场的话。
下一步，你必须输入离开和到达的地点的代号（地图里面有），还有你的飞行高度，按 File
键向ATC提交！提交了飞行计划之后，再次打开ATC窗口，点击“Request Clearance（申请放行）.”

6.3 改变飞机怎么开始，以及在哪里开始

默认情况下，飞机都是引擎运行的，停在跑道的一头等待起飞，如果你希望飞机是停在停机坪上的，想自己滑行到跑道，你一个这么做：打开菜单Setting-Operations & Warnings.在“Startup“标签栏里面，关闭 Start each ﬂight with engines running或者勾选 Start each ﬂight on ramp。

6.4 使用检查单

x-plane可以显示简单的纯文本检查单，这个文本必须在游戏的某一个目录里面，后缀名为txt.
如何加载Checklist, 点击Special菜单-Open Checklist for Use.然后你将会看见屏幕上方出现了检查单，你可以点击上一页或者下一页，在Special菜单里面Toggle Checklist可以关闭检查单。
如果想全部显示检查单，你可在Special菜单里面点Toggle Text File for Viewing。

6.5 损伤会不会飞机
默认你的飞机是无敌的，但那是不现实的。打开一些真实性，可以打开Settings-Operations & Warnings里面看到如下选项：
	
• remove ﬂying surfaces in over-speed,（飞机超速的时候部件脱落） 
• remove ﬂying surfaces in over-G（飞机的受到过大的力时导致部件脱落）, 
• remove ﬂaps in over-Vfe , （超过安全速度导致襟翼脱落）襟翼放下的角度和速度之间的限制在空速表里面有显示。
• remove gear doors in over-Vle （在起落架放下的时候超速导致起落架脱落）
开启这些真实性可以让你避免 不切实际的动作^ ^，锻炼你飞得更加准确，让飞行更有挑战性！

6.6设置机重(weight)，平衡(balance)，燃料(fuel)

设定方法：移动鼠标到上方菜单栏点击Aircraft menu- Weight and Fuel.
滑条自己看得懂吗，拖拖看。
尽管飞机在天上飞重一点感觉不出来问题，但是起飞时候会有困难。
把飞机的重心调节到比较奇怪（太靠前或者靠后）的位置会引起飞行不稳定。
前面说过了，x-plane是实时计算飞机的每一项参数来模拟的（至于你信不信，我反正信了），所以燃料的消耗速度也是根据引擎的使用来计算的。所以燃油的重量，分布，携带是有章可循的。

6.7 模拟设备故障
x-plane里面有数不清的设备故障情况可以模拟，大到引擎停转，小到仪器失灵。
在Aircraft-Equipment Failures里面有许多可选故障其中有一项是World/MTBF
World/MTBF改变的是飞机外面的变化因素
use mean time between failures 这个是确定的事故
use mean time between random failures这个是随机发生事故，概率在下面的滑条控制。
假如MTBF设置为1000，那么飞机所有的部件在一个小时内，发生故障的概率就是千分之一。飞机如果有几百个零件，那么，每隔5到20个小时就会发生一次故障。
还有一些选项卡 翻译如下
Equipment——设备
Engines——引擎
Flying Surfaces——飞机表面
G1000 (if you have a real G1000 attached to X-Plane)——外接设备
All Instruments, and NAVAIDs——其他设备和通信仪器

6.8 打开引擎烟雾

按x键开或者关。
