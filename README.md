This script will bounce ports. You can add device information to the script, including IP addresses/hostnames, usernames, passwords, and ports that need to be bounced. The script will then connect to the devices, bounce the designated ports, and provide the result in a new window when you click the "Done" button. Additionally, a Microsoft Teams Webhook URL may receive the outcome. 

This application only supports the following device type: "device_type": "cisco_ios",

Features I am looking to add in the future:
1. Output logging: Add a feature that logs the output of the port bouncing process to a file, so that users can review it later if needed.
2. Advanced Error handling: Add better error handling, for example by catching specific exceptions and displaying error messages that are more meaningful to the user.
