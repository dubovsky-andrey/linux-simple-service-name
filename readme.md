# Create file in systemd directory

    ```
    sudo nano /etc/systemd/system/service-name.service
    ```

# Create file in sbin directory

    ```
    sudo nano /usr/sbin/service-name.sh
    ```

# Add execute permissions

    ```
    # sudo chmod +x /usr/sbin/service-name.sh
    ```

# Enamble service and start

    ```
    sudo systemctl daemon-reload
    ```

    ```
    sudo systemctl enable service-name.service
    ```

    ```
    sudo systemctl start service-name.service
    ```
