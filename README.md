# BestTrace-For-Linux
VPS回程路由追踪工具

mkdir -p mtr && cd mtr && wget --no-check-certificate wget --no-check-certificate https://raw.githubusercontent.com/mrlong520/BestTrace-For-Linux/master/besttrace4linux.zip
yum install -y unzip && apt-get install unzip -y
unzip besttrace4linux.zip
chmod +x besttrace
./besttrace -q 1 gz1-dns.gdgz.cncnet.net && ./besttrace -q 1 gd.10086.cn && ./besttrace -q 1 10000.gd.cn

./besttrace -q 1 xxx.xxx.xxx(IP或域名,支持ipv6)
