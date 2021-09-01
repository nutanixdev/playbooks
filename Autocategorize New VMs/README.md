# Auto Categorize New VMs

Export Version: pc.2021.7

The Prism Central version the Playbook was exported from - This is important because Playbooks cannot be imported to an older version of PC than they were exported from. Example a Playbook from a pc.2021.1 version cannot be imported into a PC on pc.2020.11 version for compatibility reasons.

Description: This playbook uses the VM created event trigger along with a set of branching actions to add VMs to categories based on their naming conventions. This can be used to auto categorize new VMs so that alert policies, protection policies, security policies can be auto applied. It is also useful to organize VMs.

Steps to Enable:
Import the playbook
Update the regex within the branch actions to match VMs based on your naming convention.
Update the category actions to apply the categories you would like.
Save and Enable



