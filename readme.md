#This is an Ansible Role. 

###Make sure to follow the following Directory structure.
```
YOUR-FOLDER/
├── playbook.yml
└── roles
    └── LogRotation
        ├── defaults
        │   └── main.yml
        ├── tasks
        │   └── main.yml
        └── templates
            └── conf.j2
```


###To Run the Ansible-Playbook

```
 #To run on local host
 >sudo ansible-playbook your_playbook.yml 

 #To run on machines.
 >ansible-playbook -i inventory.yml -u <user_name> --key-file <location of ssh file> \
  your_playbook.yml

``` 

