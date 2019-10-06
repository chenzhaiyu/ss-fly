Script for shadowsocks/shadowsocksR/V2Ray + bbr
---

“In your life there are a few places, or maybe only the one place, where something happened, and then there are all the other places.”

## Usage

```bash
# Set up server services
# substitute "password" and "port" with your own settings
ss-fly/ss-fly.sh -i password port
```

```bash
# Start service
/etc/init.d/ss-fly start
# Stop service
/etc/init.d/ss-fly stop
# Restart service
/etc/init.d/ss-fly restart
# Check status
/etc/init.d/ss-fly status
# Check link
ss-fly/ss-fly.sh -sslink
# Edit configuration file 
vim /etc/shadowsocks.json
```

```bash
# Setting BBR
ss-fly/ss-fly.sh -bbr
```

```bash
# Uninstall server services
ss-fly/ss-fly.sh -uninstall
```