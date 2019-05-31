## nginx-proxy
os is centos 7.4

```
# stop firewall
systemctl stop firewalld

# install git
yum install -y git

# clone nginx-proxy code
git clone https://github.com/yanchangyou/nginx-proxy

# run nginx-proxy
cd nginx-proxy
./run.sh

#test port
curl http://127.0.0.1:8888/

# print log
tail -f access.log

```
default port is 8888

## test

```
curl https://github.com -x 127.0.0.1:61180 -v
```

## power by
https://github.com/chobits/ngx_http_proxy_connect_module#example
