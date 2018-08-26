# UniPi | Universal Pi-hole Settings
# Install
To install UniPi Updater, please issue the following command on your system. Please check the code to make sure it was not tampered with at the time of execution. 
```bash
$ curl -sSL https://raw.githubusercontent.com/jaykepeters/UniPi/master/Install/install.sh | bash
```
# Directory Tree Structure (For Development)
```
├── cron
│   └── jobs.crontab
├── etc
│   ├── cron.monthly
│   │   └── geoip-updater
│   ├── crontab
│   ├── dnsmasq.conf
│   ├── dnsmasq.d
│   │   └── 05-restrict.conf
│   ├── dnsmasq.hosts
│   ├── fail2ban
│   │   ├── filter.d
│   │   │   └── iptables-dns.conf
│   │   └── jail.local
│   ├── iptables.conf
│   ├── lighttpd
│   │   └── external.conf
│   ├── pihole
│   │   ├── blacklist.txt
│   │   ├── pihole-FTL.conf
│   │   ├── regex.list
│   │   └── whitelist.txt
│   ├── ssh
│   │   ├── banner
│   │   └── sshd_config
│   └── UniPi
│       ├── downloads
│       └── packages
├── Install
│   └── install.sh
├── LICENSE
├── README.md
├── usr
│   └── local
│       └── bin
│           ├── crontab.sh
│           ├── fix-apt
│           ├── restart-cron
│           ├── speedtest-cli
│           └── UniPi
└── var
    └── www
        └── html
            ├── gcping.php
            ├── phpinfo.php
            ├── services
            │   └── index.php
            └── status.php
```
Pi-hole | Network-wide ad blocking via your own Linux hardware

# Custom Features
* Google SafeSearch and Bing Strict Search Options Enforced
* OpenDNS to block adult content, academic dishonesty, proxies & VPN, etc. 
* DNS Amplification attack protection

# Public Pi-hole A (Production)
#### Provider:	Google Cloud Platform
#### Location:	Council Bluffs, Iowa, U.S.A.
#### IP Addr.:	35.188.83.81
#### Statistics:	https://dns-a.jpits.us/admin

# Public Pi-hole B (Production)
#### Provider:	Google Cloud Platform
#### Location:	North Virginia, U.S.A.
#### IP Addr.:	35.188.238.162
#### Statistics:    https://dns-b.jpits.us/admin

# Public Pi-hole C (Production)
#### Provider:	Google Cloud Platform
#### Location:	St. Ghislain, Belgium
#### IP Addr:	35.205.187.166
#### Statistics:	https://dns-c.jpits.us/admin

# Public Pi-hole (Beta Testing)
#### Provider:	Google Cloud Platform
#### Location:	Council Bluffs, Iowa, U.S.A
#### IP Addr.:	35.188.66.94
#### Statistics:	https://dns-test.jpits.us/admin

## Note to Users:	This service is provided “as-is”  and we cannot guarantee 100% uptime. By using this service, you accept that we may perform maintenance at any time for any reason. We recommend using two of our servers in case one was to go down. Please note that your traffic may be logged to help build better block lists. If you do not consent to this, please use servers “B” or “C” which have query logging disabled. 

