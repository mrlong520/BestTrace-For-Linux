# BestTrace-For-Linux
VPS回程路由追踪工具使用说明：
先安装解压工具
mkdir -p mtr && cd mtr && wget --no-check-certificate https://raw.githubusercontent.com/mrlong520/BestTrace-For-Linux/main/besttrace4linux.zip
unzip besttrace4linux.zip
chmod +x besttrace
./besttrace -q 1 58.248.20.98 
./besttrace -q 1 120.196.167.30
./besttrace -q 1 14.116.225.60

示例：
./besttrace -q 1 xxx.xxx.xxx(IP或域名,支持ipv6)
