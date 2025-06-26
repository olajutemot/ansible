# ansible
ansible playbook to install and start Ngnix

## To launch ansible play-book 
```
ansible-playbook -i inventory first-playbook.yml
```
note: the `-i inventory` is included because i have created an inventory folder to save all my host ip addresses, else it would not be needed because ansible would pick information automatically from the default saved inventory position.

## To read or debug your play book
```
ansible-playbook -vvv -i inventory first-playbook.yml
```
note: `-v` variable is called verbosity, and this is used as a debugging tool and the number of v you write will define the degree of verbosity or debugging you want, and `-vvv` is the hightest level of verbosity

