# kali之Arp局域网断网攻击

 局域网断网攻击又称arp攻击，即使局域网内目标IP断开网络连接

 arp的基本概念：ARP（Address Resolution Protocol，地址解析协议）是一个位于TCP/IP协议栈中的网络层，负责将某个IP地址解析成对应的MAC地址。

 arp的攻击原理：ARP攻击就是通过伪造IP地址和MAC地址实现ARP欺骗，能够在网络中产生大量的ARP通信量使网络阻塞，攻击者只要持续不断的发出伪造的ARP响应包就能更改目标主机ARP缓存中的IP-MAC条目，造成网络中断或中间人攻击。

 攻击工具：  Arpspoof （该工具在kali系统已内置）
    
 攻击所需信息：
 目标ip地址
 攻击者网卡编号
 局域网网关地址
    
# 攻击命令形式：
 Arpspoof -i 网卡 -t 目标IP 网关
    
