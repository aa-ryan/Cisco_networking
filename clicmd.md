* en
* config t
* interface fastethernet 0/2
* shutdown
* no shutdown
* spanning-tree portfast
* spanning-tree vlan 1 priority 0
* spanning-tree bpguard enable/disable(shutdown and no shutdown)
* switchport mode trunk/access
* sh span
* vlan 2
* exit
* switchport access vlan 2
* ip route 0.0.0.0 0.0.0.0 (address to opp router)
