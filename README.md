# ict720-porject-2025
Rep for demo idea, and code fo ICT720 cource of 2025

# Our Members
Mr. Chananyu Kamolsuntron 

Mr. Intouch Wangtrakoondee

Mr. Lihour San

# User stories 
US1: Device Setup & Connectivity

As an owner, I want to register my toilet paper monitoring device with my home/business WiFi, so that I can receive data remotely.

    acceptance criteria #1
    I can input the WiFi SSID and password to connect the device.

    acceptance criteria #2
    I can verify that the device is online.

    acceptance criteria #3
    I receive a confirmation message when the device successfully connects to the server.

US2: Toilet Paper Level Detection

As an owner, I want my device to measure toilet paper levels, so that I know when I need to refill it.

    acceptance criteria #1
    The system detects and records the current level of toilet paper.

    acceptance criteria #2
    The system updates data in the IoT server/database via MQTT.

    acceptance criteria #3
    I can view the real-time toilet paper level on the web server.

US3: Low Toilet Paper Notification

As an owner, I want to receive a notification when toilet paper is running low, so that I can refill it before it runs out.

    acceptance criteria #1
    The system sends a notification when the toilet paper level is below a set threshold.

    acceptance criteria #2
    I receive an alert on my mobile app/web interface.

    acceptance criteria #3
    I can customize the threshold level for low-paper alerts.

US4: Refill Status Monitoring

As an owner, I want to mark when I have refilled the toilet paper, so that the system resets its tracking.

    acceptance criteria #1
    I can manually reset the toilet paper status in the web app.

    acceptance criteria #2
    The system automatically detects a refill and updates the status.

    acceptance criteria #3
    I receive a confirmation message when the refill is detected.

US5: Public Restroom Monitoring (For Businesses)

As a facility manager, I want to monitor the toilet paper levels in multiple restrooms, so that I can ensure they are stocked for customers.

    acceptance criteria #1
    I can view the status of all devices (full, low, empty, offline).

    acceptance criteria #2
    I can see a map of restroom locations with real-time status.

    acceptance criteria #3
    I receive a daily summary report of toilet paper usage.

US6: Maintenance & Support

As a facility manager, I want to receive alerts if a device goes offline, so that I can fix any issues.

    acceptance criteria #1
    The system detects when a device is offline.

    acceptance criteria #2
    I receive a notification when a device is unresponsive.

    acceptance criteria #3
    I can check historical uptime and status logs.
