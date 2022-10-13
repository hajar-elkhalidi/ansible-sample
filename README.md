# Hello Ansible!

Hi! 
In this sample project, I set up a playbook that updates the hosts index in my home lab.
You can do much with Ansible to make it easier to manage your lab at home or in the office.
***keep learning!***

## Test
You can test this playbook by running this command:

    ansible-playbook --ask-become-pass update.yml
Make sure to: 
>* Change IPs to yours in **inventory**
>* Change the path to your ssh key in **ansible.cfg**
>* If you are using a Linux distribution that uses package management other than apt, change it in **update.yml**
>* YAML is **case sensitive**
