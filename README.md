Overview :

This script enables users to retrieve the 802.1X status of switches managed by Cisco Catalyst Center, exporting the results in XLS format (see attached sample). The script has been validated in a Cisco lab environment.


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

