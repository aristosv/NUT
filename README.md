# Network UPS Tools

Network UPS Tools provides a common protocol and set of tools to monitor and manage UPS devices. For more information visit the [project website](https://networkupstools.org).

This has been tested on a virtual machine running Debian 10. The UPS is physically connected on the ESXi server. A USB controller v2.0 and a USB device have been added.

<p align="center">
  <img width="800" height="524" src="https://raw.githubusercontent.com/aristosv/network-ups-tools/main/screenshots/esxi-vmguest.png">
</p>

## install
clone repo & run install
```
git clone https://github.com/aristosv/network-ups-tools.git
bash ~/network-ups-tools/operations/install
```

## access
```
http://computer_ip/cgi-bin/nut/upsstats.cgi
```

## update
run update script
```
~/network-ups-tools/operations/update
```

## screenshots
<p align="center">
  <img width="800" height="138" src="https://raw.githubusercontent.com/aristosv/network-ups-tools/main/screenshots/web1.png">
</p>

<p align="center">
  <img width="800" height="453" src="https://raw.githubusercontent.com/aristosv/network-ups-tools/main/screenshots/web2.png">
</p>

<p align="center">
  <img width="600" height="1893" src="https://raw.githubusercontent.com/aristosv/network-ups-tools/main/screenshots/web3.png">
</p>