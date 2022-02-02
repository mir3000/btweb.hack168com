源码来自：http://www.hack168.com
机房推荐：http://www.jifang.vip


这个是自用的宝塔面板一键优化补丁，主要有以下优化项目：

1.去除宝塔面板强制绑定账号

2.去除各种删除操作时的计算题与延时等待

3.去除创建网站自动创建的垃圾文件（index.html、404.html、.htaccess）

4.关闭未绑定域名提示页面，防止有人访问未绑定域名直接看出来是用的宝塔面板

5.关闭活动推荐与在线客服

适用宝塔面板版本：7.7

wget -O optimize7.7.sh https://raw.githubusercontent.com/mir3000/btweb.hack168com/master/optimize7.7.sh && bash optimize7.7.sh


全部使用补丁的方式，而不是替换文件的方式，方便后续升级版本的修改。

适用宝塔面板7.8版本的命令（7.8版本不支持去除强制绑定账号）：

wget -O optimize7.8.sh https://raw.githubusercontent.com/mir3000/btweb.hack168com/master/optimize7.8.sh && bash optimize7.8.sh

