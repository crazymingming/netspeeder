# netspeeder
仅限 centos6 系统试用

警告！vps 使用可能导致ban机！警告！vps 使用可能导致ban机！警告！vps 使用可能导致ban机！


wget -N --no-check-certificate https://raw.githubusercontent.com/crazymingming/netspeeder/master/netspeeder.sh
sh netspeeder.sh
然后通过 ps -A 查看 是否有netspeer 的进程有就ok
杀掉所有 netspeeder 进程：killall net_speeder
手动启动命令：service netspeederd start
停止则是：service netspeederd stop
