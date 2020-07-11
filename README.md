# Unifi
Unifi Samples


Unifi Controller Firewall Rules
```
New-NetFirewallRule -DisplayName "Unifi Allow Inbound TCP" -Direction Inbound -LocalPort 5514,8080,8443,8880,8843,6789,27117 -Protocol TCP -Action Allow
New-NetFirewallRule -DisplayName "Unifi Allow Inbound UDP" -Direction Inbound -LocalPort 3478,5656-5699,10001,1900 -Protocol UDP -Action Allow
```

Java Download:
https://www.java.com/en/download/manual.jsp

Unifi Controller Download
https://www.ui.com/download/unifi/default/default/unifi-network-controller-51332-windows

UniFi - Run the Controller as a Windows Service
https://help.ui.com/hc/en-us/articles/205144550-UniFi-Run-the-controller-as-a-Windows-service

Unifi Controller Port
https://help.ui.com/hc/en-us/articles/218506997


