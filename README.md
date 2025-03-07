# ict720-porject-2025
Rep for demo idea, and code fo ICT720 cource of 2025

# Our Members
Mr. Chananyu Kamolsuntron 

Mr. Intouch Wangtrakoondee

Mr. Lihour San

# User stories 
US1: Device Setup & Connectivity

    As an owner, I want to register my toilet paper monitoring device with my home/business WiFi, so that I can receive data remotely.
        Acceptance Criteria:
            I can input the WiFi SSID and password to connect the device.
            I can verify that the device is online.
            I receive a confirmation message when the device successfully connects to the server.

US2: Toilet Paper Level Detection

    As an owner, I want my device to measure toilet paper levels, so that I know when I need to refill it.
        Acceptance Criteria:
            The system detects and records the current level of toilet paper.
            The system updates data in the IoT server/database via MQTT.
            I can view the real-time toilet paper level on the web server.

US3: Low Toilet Paper Notification

    As an owner, I want to receive a notification when toilet paper is running low, so that I can refill it before it runs out.
        Acceptance Criteria:
            The system sends a notification when the toilet paper level is below a set threshold.
            I receive an alert on my mobile app/web interface.
            I can customize the threshold level for low-paper alerts.

US4: Refill Status Monitoring

    As an owner, I want to mark when I have refilled the toilet paper, so that the system resets its tracking.
        Acceptance Criteria:
            I can manually reset the toilet paper status in the web app.
            The system automatically detects a refill and updates the status.
            I receive a confirmation message when the refill is detected.

US5: Public Restroom Monitoring (For Businesses)

    As a facility manager, I want to monitor the toilet paper levels in multiple restrooms, so that I can ensure they are stocked for customers.
        Acceptance Criteria:
            I can view the status of all devices (full, low, empty, offline).
            I can see a map of restroom locations with real-time status.
            I receive a daily summary report of toilet paper usage.

US6: Maintenance & Support

    As a facility manager, I want to receive alerts if a device goes offline, so that I can fix any issues.
        Acceptance Criteria:
            The system detects when a device is offline.
            I receive a notification when a device is unresponsive.
            I can check historical uptime and status logs.
