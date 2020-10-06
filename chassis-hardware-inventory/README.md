
Playbook collects chassis inventory facts from device(s) using 'show version' and 'show chassis hardware' commands , parses them using Jinja2 template and store to a temporary directory, then create a report with predefined header and save it to .csv file. 


/etc/ansible/

├── playbooks/

│   ├── juniper/

│   │   ├── get_chassis_inventory.yaml

│   │   ├── facts/

│   │   ├── templates/

│   │   │   ├── device-facts.j2

│   │   │   ├── device-facts-columns.txt


