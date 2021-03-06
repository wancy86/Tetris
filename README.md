##项目背景
在折腾ES6，突然想起大学时用c语言写过俄罗斯方块，本项目中主要是利用ES6的Class特性进行面向对象编程。同一时间，我在看约翰.霍兰的《涌现》和KK的《失控》，产生了对人工智能的莫大兴趣，也对面向对象思想有了更深入的理解，终极目标是想写一个自动玩俄罗斯方块的小机器人。
##设计思路
- 全面应用面向对象的设计思想，让功能内聚性强。
- 把七种方块想成独立的“生物”对象，让它能“看”到周围的世界。
- 没有使用传统的大的二维数组来表示游戏场面状态，而是让tetris自己去“看”。
- 使用html5的canvas来完成，比较象cgi编程。
- 使用最少的canvas特性，只用了fillRect,strokeRect,getImageData,clearRect等几个函数。

##运行方法
项目采用node.js v6.2.0 + electron v1.1.0 进行桌面开发，因此请先安装相关系统：
```
npm install electron-prebuilt -g
```
注：本项目采用方案能跨所有平台运行，遇权限问题，请在命令行自行添加sudo 。

请下载源代码：
```
git clone https://git.oschina.net/zhoutk/Tetris.git
```
进入项目目录：
```
cd Tetris
```
运行程序：
```
electron .
```
##交流博客
我会把心得体会写在我的博客中，地址如下：
```
https://segmentfault.com/blog/zhoutk
```