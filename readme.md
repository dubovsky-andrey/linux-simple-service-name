1. Change `service-name` to your name

2. Create file in systemd directory

```
   sudo nano /etc/systemd/system/service-name.service
```

3. Create file in sbin directory

```
   sudo nano /usr/sbin/service-name.sh
```

4. Add execute permissions

```
   sudo chmod +x /usr/sbin/service-name.sh
```

5. Reload systemd

```
   sudo systemctl daemon-reload
```

6. Enable service

```
   sudo systemctl enable service-name.service
```

7. Start service

```
   sudo systemctl start service-name.service
```
