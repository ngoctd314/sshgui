# SSH GUI

## Who i am

support ssh with up/down (j/k) then enter

## How to download

On gateway paste (download sshgui code)

```bash
wget https://github.com/ngoctd314/sshgui/blob/master/run?raw=true && mv run\?raw\=true sshgui && chmod +x sshgui
```


Create ssh folder navigation
```bash
cd
mkdir ssh_nav # or any name you want
```

Then create your own ssh server
```txt
├── ssh_nav
│   ├── ssp
│   │   └── ssp@192.168.1.1
│   └── trino
│       └── trino@192.168.1.1
```

Run
```bash
cd
./sshgui # in case you create ssh_nav dir
./sshgui -dir=custom # in case you create custom dir
```