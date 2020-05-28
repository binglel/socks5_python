# socks5_python
socks5 server based on socket

# run
options
```
python socks5.py -h
```
Usage: start|stop|restart|status [options]
Options:
  --port=<val>         Sets server port, default 1080
  --log=true|false     Logging on, default true
  --allowed=IP         set allowed IP list
  --auth:<user:pwd>    Use username/password authentication
                       Example:
                         Create user "admin" with password "1234":
                           --auth=admin:1234 
                         Create tow users:
                           --auth=admin:1234,root:1234
  -h                   Show Help

server start
```
python socks5.py start --port=8080 --auth=admin:123456
```
# NOTE
forked from [pysocks](https://github.com/fengyouchao/pysocks)
