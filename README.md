# 官场现形记
一个模拟公务员的游戏。
游戏体量小,时间短,没有设置存档功能。

学习过编程的朋友可以自定义一些事件、功能,只需要def一个eventx,然后在
#时间判定与游戏结束判定函数,也就是time_trigger中,
在events=[]的列表里增加eventx,在for循环内将randint的值域扩大即可。
