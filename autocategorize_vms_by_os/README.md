# Auto Categorize VMs by OS


Export Version: pc.2021.7
The Prism Central version the Playbook was exported from - This is important because Playbooks cannot be imported to an older version of PC than they were exported from. Example a Playbook from a pc.2021.1 version cannot be imported into a PC on pc.2020.11 version for compatibility reasons.

Description: This playbook uses the VM created event trigger along with a set of branching actions to add VMs to categories based on their OS. This can be used to auto categorize new VMs so that automation rules, alert policies, protection policies, security policies can be auto applied. It is also useful to organize VMs.When it comes to assigning the category there are currently 3 IF conditions, but change it as you need to and adjust the regex for your needs. You’ll see the final regex captures a NULL value and applies a category to match that. This way the customer could look at that category to determine which VMs “missed” being properly assigned.

Steps to Enable:
Import the playbook
Update the credentials in the API query to get the OS details
Update the category actions to apply the categories you would like.
Save and Enable



