## nginx-proxy
os is centos 7.4

```
git clone https://github.com/yanchangyou/nginx-proxy
cd nginx-proxy
./run
```
default port is 61180

## test

```
curl https:/github.com -x 127.0.0.1:61180 -v
```

## power by
https://github.com/chobits/ngx_http_proxy_connect_module#example
