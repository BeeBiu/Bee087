这只是一个快捷启动器，windows外壳增强小工具

![image](https://github.com/BeeBiu/Bee087/blob/main/res/test.gif)

![image](https://github.com/BeeBiu/Bee087/blob/main/res/test1.PNG)

简单说明



新建一个文件夹，丢进去，程序第一次运行会自动创建默认配置项，随便找个地方放好，右键创建一个快捷方式，复制快捷方式至以下目录即可实现开机自启动

%programdata%\Microsoft\Windows\Start Menu\Programs\Startup

基于windows shell实现，直接拖放资源管理器图标即可完成添加和移动，鼠标中键可弹出『设置』菜单，部分细节参数可在配置项直接修改


关于拖动，因为无法知晓最终目标路径，所以程序不会自动删除已经改变源路径的图标，当你再次访问的时候会检测如果不存在会提示删除，包括通过程序本身移动的文件也是如此







开发初衷是经常碰到win更新，远程分辨率重置等等会导致桌面图标会重新排列的问题，强迫症表示异常难受，疫情期间写的干脆放出来好了
