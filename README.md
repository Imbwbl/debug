# debug
bash debug
## installation
install ![inotify-tools](https://security.archlinux.org/package/inotify-tools)
```
sudo -s
curl -sL https://raw.githubusercontent.com/Imbwbl/debug/main/debug > /usr/local/bin/debug
chmod +x /usr/local/bin/debug
exit
```

## usage
with 1 file to execute
```
debug file
```

with a command and a file
```
debug command file
```

with a compilator
```
debug compilator file executable
```
