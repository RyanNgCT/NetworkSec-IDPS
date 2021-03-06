# NetworkSec-IDPS

* Demonstrating Intrusion Detection and Prevention capabilities through Suricata IDPS.
* Pfsense version and demonstration video coming soon!

## Navigation

```
[Config File]
/etc/suricata/suricata.yaml

[Rules]
/usr/share/suricata/rules

[Logs]
/var/log/suricata
```

## Poster

![poster_png](https://github.com/RyanNgCT/NetworkSec-IDPS/blob/main/poster-files/NS%20eposter.png)

## Setup
* Windows 10 Host w WSL or any Linux/Mac OS Distribution
* VMware Workstation for Linux/Windows or VMware Fusion for Mac
* Ubuntu 20.04+ and Kali Linux (you can use pfsense too - steps will be updated soon)
* Suricata tar `.deb` file (compile from source)
* [XAMPP for Linux](https://www.apachefriends.org/download.html) or LAMP (I was lazy to install LAMP)
* Download mutillidae on Ubuntu as per this guide (and start it with XAMPP):
     * Follow this video for XAMPP: https://www.youtube.com/watch?v=SUuYq1Gt_as
     * For LAMP: https://kavishgr.gitlab.io/posts/deploy-mutillidae-on-a-ubuntu-server-18.04/ 

## Network Config

* Note: Make sure Kali and Ubuntu w Suricata are in `NAT mode`.

## Software Config

* Download files in [final_config](https://github.com/RyanNgCT/NetworkSec-IDPS/tree/main/suricata) folder and add them to the respective files (or replace the different areas).
