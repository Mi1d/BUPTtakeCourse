# BUPTtakeClass
在教务系统登录后即可抢课，无需进入选课界面，必修选修公选通用。
F12打开Console控制台，粘贴代码回车。
以防万一（教务系统更新），建议抢课方式：
开始选课前提前10秒，在登陆后的教务系统界面开启抢课，开始选课后同时手动抢课，进入选课界面扫一眼是否自动抢课成功；
若失败则在Consloe输入stop()停止脚本运行，手动抢课。
如果不是第一时间进入抢课（捡漏模式），请不要设置过低的时间间隔。
推荐间隔：抢课模式: 50ms， 捡漏模式：300ms(够用就好）
请不要设置过低的抢课间隔，以免对脆弱的教务系统产生不必要的压力。
