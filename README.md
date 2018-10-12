# lkl-bbr
超强bbr,需先开启tun/tap
iptables -t nat -A POSTROUTING -o venet0 -j MASQUERADE 注意要将venet0改为实际的
