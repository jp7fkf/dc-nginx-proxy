# nginx-proxy using docker compose

## systemctl compose
```
vim dc-nginx-proxy.service # optional (ex. path to workingdir)
sudo ln -s /home/composer/dc-nginx-proxy.service /etc/systemd/system/
cp docker-compose.yml docker-compose.override.yml # optional
sudo systemctl daemon-reload
sudo systemctl status dc-nginx-proxy.service
sudo systemctl [start/stop/restart] dc-nginx-proxy.service
```

