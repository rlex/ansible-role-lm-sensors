##### Ansible role for lm-sensors

Installs lm-sensors and starts it.  
It will only install if it's baremetal machine (ansible_virtualization_role != "guest")  
Please note, however, that VM detection is partially [broken](https://github.com/ansible/ansible/issues/38947) in ansible

##### TBD

Parse sensors-detect output and load requested modules
