```
git clone --depth=1 https://github.com/sswensen/motd.git ~/tmp/motd
sudo mv ~/tmp/motd/95-lolcat /etc/update-motd.d
```

Add this to `/etc/update-motd.d/`

Requires fortune, cowsay, lolcat. 
