# Udacity-Jacks-Version

### 1. Exercise: Define Ansible Playbook
Files relevant for this exercise are:
```bash
├── main2.yml   # Playbook file
└── roles
    └── print
        └── tasks
            └── main.yml
```

### 2. Exercise: Remote Control Using Ansible
**Prerequisite**: 
- A linux (Ubuntu 20.04) EC2 instance with port 3000 open for the inbound access. 
- Public IP address of an EC2 instance in your AWS account.
- A key pair to connect your EC2 instance

Files relevant for this exercise are:
```bash
├── main4.yml     # Playbook file
└── roles
    └── setup
        ├── files
        │   └── index.js
        └── tasks
            └── main.yml
```
### 3. Exercise: Infrastructure Creation
Files relevant for this exercise are:
```bash
└── template.yml            # Change the KeyName property value, as applicable to you
└── .circleci
    └── config.yml          # Look for the create_infrastructure Job
```


### 4. Exercise: Config and Deployment
**Prerequisite**: 
- Create an EC2 instance and note it's public IP address
- Add the contents of your PEM file to the SSH keys in your Circle CI account to get the fingerprints

Files relevant for this exercise are:
```bash        
├── ansible.cfg             
└── .circleci
    └── config.yml          # Look for the configure_infrastructure Job
```


### 5. Exercise: Smoke Testing
Files relevant for this exercise are:
```bash           
└── .circleci
    └── config.yml          # Look for the smoke_test Job
```