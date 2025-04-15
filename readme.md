# Create file in systemd directory

    sudo nano /etc/systemd/system/service-name.service

# Create file in sbin directory

    sudo nano /usr/sbin/service-name.sh

# Add execute permissions

    sudo chmod +x /usr/sbin/service-name.sh

# Reload systemd

    sudo systemctl daemon-reload

# Enable service

    sudo systemctl enable service-name.service

# Start service

    sudo systemctl start service-name.service
