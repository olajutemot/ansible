# ansible
ansible playbook to install and start Ngnix

## ansible script to launch play-book 
```
ansible-playbook -i inventory first-playbook.yml
```
note: the `-i inventory` is included because i have created an inventory folder to save all my host ip addresses, else it would not be needed because ansible would pick information automatically from the default saved inventory position.
