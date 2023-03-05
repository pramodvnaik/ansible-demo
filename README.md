# ansible-demo


## Get Started

### Install Ansible
``` sudo  yum install -y ansible ```

or 

``` sudo  apt install ansible ```

#### Set up Inventory File
- Create a folder. ex: ansible-demo
- Create inventory file with name inventory (no extension)
- Define the hosts in inventory file, for simple usecase define localhost
- Create ansible.cfg
- Define the inventory file in ansible.cfg file

### First Command 
``` ansible all -m ping ```

Output:
```

localhost | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python"
    },
    "changed": false,
    "ping": "pong"
}

```
