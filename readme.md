1. Create file in systemd directory

```
   sudo nano /etc/systemd/system/service-name.service
```

2. Create file in sbin directory

   sudo nano /usr/sbin/service-name.sh

3. Add execute permissions

   sudo chmod +x /usr/sbin/service-name.sh

4. Reload systemd

   sudo systemctl daemon-reload

5. Enable service

   sudo systemctl enable service-name.service

6. Start service

   sudo systemctl start service-name.service
