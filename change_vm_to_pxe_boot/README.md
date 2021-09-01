# Change VM to PXE Boot

Export Version: pc.2020.11.0.1
The Prism Central version the Playbook was exported from - This is important because Playbooks cannot be imported to an older version of PC than they were exported from. Example a Playbook from a pc.2021.1 version cannot be imported into a PC on pc.2020.11 version for compatibility reasons.

Description: This playbook uses REST API calls to pull the MAC address and cluster VIP, then uses an SSH action to login to the cluster VIP and run the acli command to update the VM to PXE boot. The machine is hard powered off beforehand and then powered on at the end.

Steps to Enable:
Import the playbook
Change the Prism Central username and password in the following steps:
REST API (Get VM Info)
REST API (Get Cluster Info)
Change the admin Prism Element password in the following step:
IP Address SSH (Update VM to Boot from PXE)
Save and Enable


Anything Else:
This is manually triggered. DO NOT switch the trigger to “Update VM” as you will get a “wonderful” loop of the playbook triggering over and over.
There is a 1 minute wait between the update command and power on due to issues where the power on would sometimes happen while the VM was still being updated.
You must use the admin PE user in the SSH step. The nutanix user does not have the proper python paths set in bash.



