This script will bounce ports. You can add device information to the script, including IP addresses/hostnames, usernames, passwords, and ports that need to be bounced. The script will then connect to the devices, bounce the designated ports, and provide the result in a new window when you click the "Done" button. Additionally, a Microsoft Teams Webhook URL may receive the outcome.  The script connects to the devices using the Netmiko library and builds the user interface using the PySimpleGUI module. Concurrent.futures is used for port bouncing. The bouncing function is executed concurrently for each device via ThreadPoolExecutor.

This application only supports the following device type: "device_type": "cisco_ios",

Features I am looking to add in the future:
Output logging: Add a feature that logs the output of the port bouncing process to a file, so that users can review it later if needed.
Error handling: Add better error handling, for example by catching specific exceptions and displaying error messages that are more meaningful to the user.
Integration with other tools: Add support for integrating with other tools, such as chatbots, ticketing systems, or databases, to make it easier to use the tool in a real-world environment.
