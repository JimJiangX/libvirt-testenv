sysctl -w net.ipv4.ip_forward=1
iptables -t nat -F
iptables -t nat -X
iptables -t filter -F
iptables -t filter -X
