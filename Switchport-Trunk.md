enable
  conf t
  int range GigabitEthernet 1/0/1 - 9
  description int de Trunk
    switchport mode access
    switchport nonegotiate
    end
wr
