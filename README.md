# eMuleTrayIcon
Tray Icon for eMule

![eMuleTrayIcon](https://github.com/qkdummy/eMuleTrayIcon/blob/master/eMuleTrayIcon2.jpg)

前两天突然想换换皮肤，可是从网上能找到的皮肤打包基本都是10年前的产物，其中不少因为新旧emule版本的ini配置文件命令不同，导致工具栏图标不显示或不完全显示，主要是以下两种错误：

需把download改成transfer，把files改成sharedfiles。

![1](https://github.com/qkdummy/eMuleTrayIcon/blob/master/1.jpg)

需把前面的“bn_"全部删除。

![2](https://github.com/qkdummy/eMuleTrayIcon/blob/master/2.jpg)

14行关于顶端工具栏的命令最终正确如下：

![3](https://github.com/qkdummy/eMuleTrayIcon/blob/master/3.jpg)

另外这些皮肤包的系统托盘图标大多制作成32位颜色的ico文件，这会导致右边的速度条不能显示，必须24位及以下才能正确显示，但16×16的图标改成24位足够颜色细节的丢失，所以本人挑选了十几组既有的图标作像素级编辑优化，以求细节过渡自然，同时在深浅色任务栏都尽量适配，最后自己也在其他素材拿灵感设计了十几组，两天后几乎眼瞎完成了这30组。食用方法如下，选定一组ico去除文件名前面的数字序号，复制粘贴到正在使用的皮肤文件夹下，打开对应ini配置文件搜索”tray"字眼，找到这3行，没有的自己添加，检视全部路径文件名对应正确：

![4](https://github.com/qkdummy/eMuleTrayIcon/blob/master/4.jpg)
