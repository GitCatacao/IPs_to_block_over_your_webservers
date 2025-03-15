# ⛑️ IPs to block over your webservers
## A list of known IPs that everyone should block on their webservers (static IP scanners)

This is a list of scanners that do nothing but check traffic and scan servers. They're not scrapers, spiders or crawlers, they do this with webservers as well as other services.
**Under the pretext of analyzing the network they perform checks and take information.**
There is no body that prohibits this practice so everyone sets themselves up as God and checks other people's servers by scanning files (sometimes even looking for file names that should be private). Anyone could open a service like this and scan other people's servers claiming to perform security checks.

After careful analysis of the logs, these are the known static IPs sorted that annoy webmasters and server system administrators.

The list will be updated as it will be on the managed servers as soon as possible.
<!-- This list should be called fuck these bastards -->
N.B. 0/24 is a [CIRD](https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing) notation to identify a group of IPs. When you see it at the end it means all the IPs from 0 to 255. If you are a server administrator you most likely already know this.
```
5.135.58.204
15.204.37.20
15.204.37.92
15.235.189.0/24
18.97.5.85
35.198.189.74
35.216.149.150
35.216.185.163
35.216.192.229
35.216.206.192
35.216.211.21
35.216.252.127
37.59.165.80
44.220.185.0/24
44.220.188.205
45.43.33.0/24
45.83.64.16
51.81.110.52
51.81.111.15
51.81.144.39
51.81.215.66
51.81.215.71
51.91.174.245
51.91.174.255
51.178.236.246
51.178.236.251
51.254.0.0/24
51.254.49.0/24
51.254.49.96
51.254.59.0/24
62.82.198.68
64.62.197.229
64.62.197.237
66.70.240.176
66.70.240.190
91.196.152.35
98.80.4.23
98.80.4.114
135.148.10.165
135.148.63.209
135.148.213.250
137.74.181.244
137.74.181.252
138.68.144.227
139.99.35.32
146.59.158.41
147.135.23.99
147.135.85.132
157.245.105.107
167.99.210.137
188.166.16.179
192.145.127.218
194.187.176.17
194.187.176.27
194.187.176.28
194.187.176.102
194.187.176.140
195.184.76.137
213.32.122.82

```

Feel free to do so or not.

For Apache HTTP Server you can use `.htaccess` and [set these IPs as forbidden](https://serverfault.com/questions/714270/how-to-block-ip-in-htaccess-on-apache-2-4#answer-750459).

In case you have more services use a firewall (eg [ufw](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-with-ufw-on-ubuntu) for Linux, [Windows Firewall](https://knowledge.civilgeo.com/configuring-windows-firewall-to-allow-or-block-ip-addresses/) for Windows).
