

## Install & Upgrade

```
bash <(curl -Ls https://raw.githubusercontent.com/SLCSTech/XUI-Sub-Temp/refs/heads/master/main.sh )
```

## Configuration File
```
nano /opt/DVHOST/dvhost.config
```
You must restart the service after changing the configuration file.
```
systemctl restart DVHOST_TEMPLATE
systemctl status DVHOST_TEMPLATE
```
**You should not have ports 2082 and 2083 involved.**

## Template File
```
nano /opt/DVHOST/views/sub.ejs
```

