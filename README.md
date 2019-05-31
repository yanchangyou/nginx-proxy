## nginx-proxy
os is centos 7.4

```
echo stop firewall
systemctl stop firewalld

echo install git
yum install -y git

echo clone nginx-proxy code
git clone https://github.com/yanchangyou/nginx-proxy

echo run nginx-proxy
cd nginx-proxy
./run.sh

echo test port
curl http://127.0.0.1:8888/

echo print log
tail -f access.log

echo end
```
default port is 8888

## test

```
curl https://github.com -x 127.0.0.1:61180 -v
```

## power by
https://github.com/chobits/ngx_http_proxy_connect_module#example
