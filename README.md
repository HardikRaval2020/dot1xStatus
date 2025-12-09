Overview :

This script enables users to retrieve the 802.1X status of switches managed by Cisco Catalyst Center, exporting the results in XLS format (see attached sample). The script has been validated in a Cisco lab environment. (CC ver 2.3.7.9)


Features :

Verifies whether 802.1X is globally enabled on each onboarded switch.
If 802.1X is enabled globally, inspects interface-level configuration and reports the 802.1X status for each interface.

Usage Instructions :

Install Python on your system.
Install the required dependencies:
pip install -r requirements.txt
Execute the script in a Python-enabled environment:
python CC_dot1x_5f.py

Required Input :

Please ensure to provide your Catalyst Center IP address, username, and password within the configuration file before running the script.

<img width="769" height="338" alt="image" src="https://github.com/user-attachments/assets/ff6a11f0-8dd3-45bd-ba8c-db143c8d8daa" />
<img width="684" height="282" alt="image" src="https://github.com/user-attachments/assets/c8747e5b-3ee9-4b3c-b088-e075872883e9" />
