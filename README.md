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