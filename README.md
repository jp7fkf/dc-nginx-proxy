# nginx-proxy using docker-compose

## systemctl compose
```
cp nginx-proxy.service /etc/systemd/system/nginx-proxy.service
cp docker-compose.yml docker-compose.override.yml # optional
sudo systemctl daemon-reload
sudo systemctl status nginx-service
sudo systemctl [start/stop/restart] nginx-service
```

