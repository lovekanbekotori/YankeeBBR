# YankeeBBR
来自Loc大佬Yankee魔改的BBR的Debian一键安装包

一键脚本wget -N --no-check-certificate https://raw.githubusercontent.com/lovekanbekotori/YankeeBBR/master/bbr.sh &amp;&amp; bash bbr.sh install
然后根据提示重启系统。
重启完成后，运行
bash bbr.sh start
即可启动魔改版BBR。
安装过程中如果出现这张图片，请选择NO 来删除其他内核：
![1](https://raw.githubusercontent.com/lovekanbekotori/YankeeBBR/master/bbr1.png)
查看魔改BBR状态
sysctl net.ipv4.tcp_available_congestion_control
如果看到有 tsunami 就表示开启成功！
![2](https://raw.githubusercontent.com/lovekanbekotori/YankeeBBR/master/bbr2.png)
