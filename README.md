[⬆]一般问题
↗ 你昨天/或者本周学习了什么新知识？
↗ 谈一下你最擅长的开发环境(OS, Editor, Browsers, Tools etc.)
↗ 谈一下你最近完成的一个linux项目
↗ 谈一下你在工作中犯过的最大错误，以及你后续的改进，得到了什么经验
↗ 我们为什么要选择你？
↗ DNS的功能是什么？
↗ 什么是HTTP？
↗ 什么是HTTP代理？都有哪些类型？它是怎么工作的？
↗ 简单描述一下HTTPS是怎么工作的
↗ SMTP是什么？简单描述一下一个邮件是怎么通过SMTP送达的
↗ RAID是什么？ RAID0, RAID1, RAID5, RAID10 呢?
↗ 什么是level0备份？什么是增量备份?
↗ 简单描述下Linux系统的目录结构

[⬆] 基本的Linux问题
↗ 超级管理员的用户的UID和名称是什么
↗ 在一个目录中怎么查看所有文件，包括隐藏文件
↗ 如何删除一个文件夹和里面的所有内容
↗ 怎么查看内存信息
↗ 怎么在一个目录中递归的查找包含“bj xxx"的文件
↗ 通过SSH怎么登录一台远程主机，怎么配置免密登录
↗ 怎么查看你正在用到的所有环境变量
↗ 找不到ifconfig命令怎么办
↗ 按下TAB-TAB会发生什么情况
↗ 怎么查看硬盘容量的使用情况
↗ 用什么命令能够检测DNS的情况
↗ 用什么命令修改文件所属组和文件权限
↗ chmod +x * 什么意思
↗ 权限为0750的文件表示什么
↗ 权限为0750的目录表示什么 
↗ 怎么加入一个没有登录权限的系统用户
↗ 怎么将某用户加入/取消加入某个组
↗ alias命令能够做什么
↗ 怎么设置一个linux用户的邮箱地址
↗ CTRL-c表明什么？CTRL-d呢
↗ /etc/services 文件是干什么用的
↗ 怎么重定向STDOUT和STDERR (> /dev/null 2>&1)
↗ UNIX和Linux有什么不同
↗ Telnet和SSH有什么不同
↗ 说明一下load averages的含义
↗ 都有什么命令能够看到load，怎么保持到文件
↗ 什么是Linux的内核模块
↗ 如何进入"single user mode"模式去排查问题
↗ 你如何去排查一个普通的404问题

[⬆] 中级的Linux问题
↗ 下面的命令都是干什么用的，请说明
```
 tee
 awk
 tr
 cut
 tac
 curl
 wget
 watch
 head
 tail
```
↗ 一个命令行后的 & 是做什么用的，有什么问题?
↗ "packet filter"是什么？它是怎么工作的?
↗ 什么是 Virtual Memory?
↗ SWAP是什么，如何禁用?
↗ A record, NS record, PTR record, CNAME record, MX record都表示什么意思?
↗ 水平分割（Split-Horizon） DNS是什么意思?
↗ linux中的粘滞位(sticky bit)是什么意思?
↗ 不可变位对一个文件是什么影响？chattr命令是做什么的?
↗ 软链和硬链有什么区别？当你删除它们的源时，会发生什么？
↗ inode是什么？里面存放的是什么内容？
↗ 如何在下次操作系统重启时强制开启文件系统检测？
↗ SNMP是干什么的？
↗ linux的"runlevel"是什么，如何查看当前的级别？
↗ SSH端口转发是什么？如何做？
↗ 怎么手动添加一个用户到系统中（不可以使用useradd等命令）?
↗ Linux系统设备(device)的major和minor number指的是什么？
↗ mknod了解么？什么时候用过？
↗ 当系统提示"filesystem is full" ，是什么原因引起的？
↗ 什么时候当你删除一个文件，但是"df"命令发现空间并没有释放？
↗ ps命令是如何工作的？
↗ 简短说明一下进程的状态意义（如S、R、D）
↗ 怎么查看是什么进程在监听某个端口？
↗ 僵尸进程是怎么产生的？
↗ 如果你运行了一个命令，你看到执行结果输出在终端，现在你想同时把执行结果保存到文件里，该如何去做？
↗ echo "1" > /proc/sys/net/ipv4/ip_forward 是什么意思
↗ 简单描述下你如何给 sayhiai.com 安装一个https证书
↗ 你能使用同一个IP配置多个虚拟HTTPS主机么
↗ 什么是通配符证书？
↗ 你都知道哪些linux文件类型，如何查看？
↗ linux进程和线程有什么区别？
↗ exec和fork命令有什么区别？
↗ nohup是什么命令？
↗ 下面连个命令的区别是什么？
 ```
 myvar=hello
 export myvar=hello
 ```
↗ ntp是什么？你配置了几个ntp服务器？
↗ 加入你要升级1000台服务器的内核，你将如何做？
↗ 怎么去限制某个进程的内存使用？
↗ 除了bash你还用过哪些shell，有什么特点？
↗ 从一台机器拷贝所有文件到另一台机器？包括软硬链接、设备等
↗ 怎么去判断apache是否已经安装？怎么列出系统中已经安装的软件包？

[⬆] 高级linux问题
↗ tunnel是什么？怎么设置一个带密码的http代理
↗ IDS和IPS有什么区别？
↗ Linux标准是什么？
↗ 什么是原子操作？
↗ 你刚配置好的http服务器在系统重启后没有启动，你后续会做什么？
↗ 这个文件里存的是什么 `~/.ssh/authorized_keys` ?
↗ I've added my public ssh key into authorized_keys but I'm still getting a password prompt, what can be wrong?
↗ 你创建过软件包么？比如RPM、DEB等?
↗ 这条命令是什么意思 `:(){ :|:& };:` ?
↗ 怎么在SHELL脚本里捕捉Linux信号?
↗ 你能捕捉SIGKILL信号么？
↗ 当Linux启动OOM killer以后，它会选择哪个进程去杀死？
↗ 详细描述一下Linux系统的启动，越详细越好，从你按动电源直到显示登录
↗ chroot是什么用的
↗ 当unmount一个目录时，提示正在使用，怎么找出那个进程正在使用这个目录？
↗ `LD_PRELOAD`环境变量是干什么用的？
↗ 你尝试启动一个二进制文件，但是什么都没发生，接下来你如何进行调试？
↗ cgroups是什么？
↗ 怎么增加或者减少某个进程的优先级？

[⬆] 专业Linux问题
↗ A running process gets EAGAIN: Resource temporarily unavailable on reading a socket. 在不杀死进程的前提下，你怎么关闭这个 socket/file文件描述符?
↗ swapiness参数怎么修改？有什么影响？
↗ 怎么去改变TCP的缓冲区？你什么情况下去修改这些参数？
↗ 什么是hugepage，什么时候会用到？你都做过哪些优化？
↗ 什么是LUMA架构？对软件有什么影响？
↗ LUKS是什么? 如何使用? （磁盘加密）
↗ CPU亲和力是什么，如何配置？
↗ 怎么分析I/O，怎么判断达到瓶颈？

[⬆] 网络问题
↗ localhost是什么？如果ping localhost失败是什么情况？
↗ 用什么命令看系统所有开启的端口？
↗ 300.168.0.123是一个合法的ip地址么?
↗ VLAN是什么？
↗ ARP用来做什么？
↗ TCP和UDP有什么区别？
↗ 默认网关的作用是什么？
↗ 怎么看linux的网络路由表
↗ 怎么给某块网卡加IPv6地址？
↗ SNAT是什么？有什么作用？
↗ 怎么防范 DDoS 攻击?
↗ 怎么查看或者dump网络包的内容？如何分析？
↗ IPoAC (RFC 1149) 是什么?
↗ 当你把端口bind到0上，会发生什么 0?
↗ Linux支持的端口范围？能支持多少连接？

[⬆] MySQL 问题
↗ 怎么创建一个用户？
↗ 如何给某个用户某个库的读权限？
↗ 左连接和又连接有什么区别？
↗ InnoDB和MyISAM有什么区别？
↗ 简单描述下如何做一个简单的MySQL主从集群
↗ MySQL Cluster是什么？那个版本支持？
↗ mysql_secure_installation是什么意思？
↗ 怎么查看MySQL正在运行哪些job？
↗ 怎么排查慢日志？
↗ 你如何给MySQL做全量、增量备份？

[⬆] DevOps 问题
↗ 你写脚本一般怎么写？有哪些工具或者流程？
↗ git如何简单使用？
↗ 动态链接和静态链接有什么区别？
↗ "./configure && make && make install" 做了些啥？
↗ puppet/chef/ansible用过么？
↗ Nagios/Zabbix/Telegraf等做什么用的?
↗ 接触过Influxdb、OpenTSDB这些时序数据库么？
↗ CI/CD工具接触过什么？Jenkins?
↗ 容器Containers和VM有什么区别？
↗ 怎么创建一个postgres用户？
↗ virtual IP什么意思？
↗ python里有switch语句么？
↗ 你怎么控制云端和本地环境的权限？
↗ 你会给开发人员开放系统权限么？到什么程度？
↗ 用过跳板机么？有哪些？
↗ 为了增加开发和SRE的互动，你都引入过哪些工具？

[⬆] 有趣的问题
↗ 有个傻蛋运行了下面的命令`chmod 444 /bin/chmod`，你该怎么去修复它
↗ 我忘了我的ROOT密码，怎么找回来？
↗ 我远程启动了一台机器，10分钟过去了还没给我响应，发生了什么情况？
↗ 你被困在一个孤岛上，仅有机会选择5个命令，为了最大限对的掌控，你会选哪5个？
↗ 你随机看到一台开着终端的机器，你首先想到的是想输入啥？
↗ 你用SSH命令干过哪些创造性的事情？
↗ 当reboot命令没有响应，你怎么重启机器？

[⬆] 实践
↗ 解压 test.tar.gz 并输出内容.
↗ 在test文件夹内递归删除所有 "*.pyc" 文件?
↗ 替换所有 *txt 中的 "window" 为 "linux"
↗ 检测IP X.X.X.X 的 443端口是否开放
↗ 使用telnet或者nc获取某网页内容
↗ 使用命令行发送一个邮件

[⬆] Other Great References:
↗ Some questions are 'borrowed' from other great references like:
↗ https://github.com/darcyclarke/Front-end-Developer-Interview-Questions
↗ https://github.com/kylejohnson/linux-sysadmin-interview-questions/blob/master/test.md
↗ http://slideshare.net/kavyasri790693/linux-admin-interview-questions
