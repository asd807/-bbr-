https://roov.org/2020/03/bbr-bbrplus-bbr2/
使用推荐该脚本：bash <(curl -Lso- https://git.io/kernel.sh )
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
BBRplus 加速:wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
系统自带 BBR 加速:1. echo "net.core.default_qdisc=fq" >> /etc/sysctl.conf  2. echo "net.ipv4.tcp_congestion_control=bbr" >> /etc/sysctl.conf  3.  sysctl -p
