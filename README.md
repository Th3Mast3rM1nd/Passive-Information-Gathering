# Passive-Information-Gathering

```shell
whois target.com # or whois ip.address to make reverse lookups 
```

```
Google Droks 

filetype:php
-filetype:html
site:google.com 
-ext:js , ext:html , ext:jsp
intitle:"index of" "parent directory" 
inurl:"*admin | login" | inurl:.php | .asp
site:*.github.io intext:cheatsheet+offensive+pentesting
```
[ For more Google Droks ](https://www.exploit-db.com/google-hacking-database)


***Netcraft***

[Search Domain ] (https://searchdns.netcraft.com/ )



```shell
recon-ng
marketplace install all #install all modules 
modules load <name> # modules load profiler 

```

***shodan***
```

    country - filters by two letters country code (e.g. US, JP, FR, IT, RU);
    city - filters by city name;
    hostname - filters by hostname or domain;
    net - filters by IP range (CIDR notation);
    product - filters by technology (es. MySQL, Apache, IIS, Nginx);
    os - filters by operating system;
    port - filters by specific port;
    org - filters by organization;
    geo - filters by geographic coordinates;
    after/before - filters by date (format dd/mm/yyyy and dd-mm-yy).#
 ```
 ![Screenshot from 2022-01-07 13-28-03](https://user-images.githubusercontent.com/92652606/148550907-e2cb0a02-f6ff-484e-b17d-fd6818e8ca6c.png)






