#修改同步服务器时间
# update time!
yum -y install ntpdate

echo "请稍微正在同步北京时间，需要十秒左右" 
ntpdate asia.pool.ntp.org 

cp -rf  /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
echo "yes"
