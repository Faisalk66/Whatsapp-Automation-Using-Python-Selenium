# Whatsapp-Automation-Using-Python-Selenium

This is a simple Web WhatsApp Bot developed in python using Selenium. Selenium is used mainly for automating web applications for testing purposes, but is certainly not limited to just that. Boring web-based administration tasks can (and should!) be automated as well.

- Send messages to family, friends and contacts automatically

- Send specific message at specified time for a sepecific contacts

- Send the message in group also


# Features

- Send a specific message to a particular contact at any time of the day
- One can send a single message to single contacts over a specific time
- It offers a delay so that WhatsApp can detect your are sending a URL and show its pop-up description.
- It can search a contact from the list if the contact isn't present in the recent chats
- Save the contact name, number in a xls file and save it in the same directory.
- You can add multiple messages
- The Script can also search for the contact in the new chat list and then send message if the contact is not found in the recent chat list.


# Installation

Step 1: Install Selenium

$ pip3 install selenium


Step 2: Selenium requires a driver to interface with the chosen browser.

Edge Browser, Chrome Browser, FireFox Browser


Step 3: Extract the downloaded driver onto a folder


Step 4: Set path variable to the environment. Paste this command to the terminal

$ export PATH=$PATH:/home/path/to/the/driver/folder/

Eg: $ export PATH=$PATH:/home/faisal/Desktop/Whatsapp-Automation-Using-Python-Selenium


Step 5: When the browser is opened web.whatsapp.com will be opened and will ask to scan a QR code when you it first time


Step 6: After Scanning the QR code, you will be asked to press Enter Key in the terminal.



# Note

You can also add Names of the contact you want to send message. The contact name should match exactly with the name saved in your contacts.
