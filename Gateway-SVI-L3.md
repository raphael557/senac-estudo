enable
  conf t
  ip routing
  interface vlan 10
    description Interface Gateway vlan-10
    ip address 172.16.0.158 255.255.255.224
    no shutdown
    end
wr

shw ip interface brief
