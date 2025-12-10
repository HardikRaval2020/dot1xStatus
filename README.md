Overview :

This script enables users to retrieve the 802.1X status of switches managed by Cisco Catalyst Center, exporting the results in XLS format (see attached sample). The script has been validated in a Cisco lab environment. (CC ver 2.3.7.9)


Features :

Verifies whether 802.1X is globally enabled on each onboarded switch.
If 802.1X is enabled globally, inspects interface-level configuration and reports the 802.1X status for each interface.

Usage Instructions :

Install Python on your system.
Install the required dependencies:
pip install -r requirements.txt

Configure your Catalyst Center credentials:
Copy the .env.example file to .env:
cp .env.example .env

Edit the .env file and add your Catalyst Center IP address, username, and password:
DNAC_IP=your.catalyst.center.ip
USERNAME=your_username
PASSWORD=your_password

Execute the script in a Python-enabled environment:
python CC_dot1x_5f.py

Security Note :

The .env file contains sensitive credentials and should never be committed to version control. It is already included in .gitignore to prevent accidental commits.

<img width="769" height="338" alt="image" src="https://github.com/user-attachments/assets/ff6a11f0-8dd3-45bd-ba8c-db143c8d8daa" />
<img width="684" height="282" alt="image" src="https://github.com/user-attachments/assets/c8747e5b-3ee9-4b3c-b088-e075872883e9" />
