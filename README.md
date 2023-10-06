# About
This script interates through all Ansible Collections which are available from the Ansible Automation 
Hub (console.redhat.com) in both the validated content and the certified content and creates a requirement.yml
file of all collections to be imported into a Private Automation Hub.

It provides rudimentary options via a config.yml to exclude certain collections, repositories and namespaces.

# Get started
```
pip3 install -r requirements.txt
python3 automation_hub_generate_requirements_yaml.py <your commandline arguments here>
``` 
