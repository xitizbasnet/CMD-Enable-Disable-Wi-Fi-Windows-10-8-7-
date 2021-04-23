# CMD-Enable-Disable-Wi-Fi-Windows-10-8-7
CMD : Enable / Disable Wi-Fi Windows 10/8/7 

1. Run CMD as an administration
2. Type: "netsh interface show interface"
3. ping 8.8.8.8
4. if reply comes the network is fine and enable
5. Type: "netsh interface set interface "Wi-Fi" disable"
6. ping 8.8.8.8
7. if reply does not comes back from the network then the network is  disable
8. DONE

-----------------

To ENABE the network 

1. Type: "netsh interface set interface "Wi-Fi" enable"
2. ping 8.8.8.8
3. if reply comes the network is fine and enable
4. DONE

------------------------

