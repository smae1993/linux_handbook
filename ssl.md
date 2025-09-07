install certbot:
```
sudo apt install certbot python3-certbot-nginx -y
```

get ssl for a domain:
```
sudo certbot --nginx -d yourdomain.com -d www.yourdomain.com
```
