# Airport-toolkit
各類方便機場主進行安裝維護的shell腳本

安裝
yum install wget -y && wget https://raw.githubusercontent.com/forjustice/Airport-toolkit/master/ssr_node_c7.sh && chmod +x ssr_node_c7.sh && ./ssr_node_c7.sh

卸載
systemctl disable ssr_node && \rm /usr/lib/systemd/system/ssr_node.service && \rm -rf /soft/shadowsocks

設置開機啓動
systemctl enable ssr_node

服務啓動
systemctl start ssr_node

服務停止
systemctl stop ssr_node