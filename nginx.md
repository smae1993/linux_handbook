install nginx:
```
sudo apt update
sudo apt install nginx -y
```

check status:
```
sudo systemctl status nginx
```
allow nginx ports in firewall:
```
sudo ufw allow 'Nginx Full'
sudo ufw enable
```
