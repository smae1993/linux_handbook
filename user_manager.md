add user:
```
sudo adduser username
```

for set sudo permission for user:
```
sudo usermod -aG sudo username
```

for change password:
```
sudo passwd username
```

change root password:
```
passwd
```

for rename user:
```
sudo usermod -l newname oldname
sudo mv /home/oldname /home/newname
sudo usermod -d /home/newname -m newname
```
