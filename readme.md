## Requirements

* ansible
* python

```
pip install f5-sdk bigsuds netaddr deepdiff
```


## setup
edit files in `group_vars/f5-test.yaml` & `inventory/hosts`


## execute
```
ansible-playbook playbook.yaml -i inventory/hosts -vvv
```


## More info
see https://github.com/F5Networks/f5-ansible
