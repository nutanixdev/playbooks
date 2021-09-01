Lookup Cluster VIP for VM


Export Version: pc.2021.1
The Prism Central version the Playbook was exported from - This is important because Playbooks cannot be imported to an older version of PC than they were exported from. Example a Playbook from a pc.2021.1 version cannot be imported into a PC on pc.2020.11 version for compatibility reasons.

Description: This playbook allows you to take a VM and lookup the corresponding cluster VIP. This requires that the cluster VIP has been configured from the PE ‘Cluster Details’ Settings. This can be useful when looking to query a REST API endpoint in the PE or looking to ssh in and run a command or script via cmd line.

Steps to Enable:
Import the playbook
Fill in your Prism Central UI login credentials to the REST API actions.
Modify playbook as needed for your use case (ie updating the trigger, or using the Parsed VIP from the final action in a REST API or SSH action)
Save and Enable

