## Requirements

ansible
python
pip install f5-sdk bigsuds netaddr deepdiff



## setup
edit files in `group_vars/f5-test.yaml` & `inventory/hosts`



```
ansible-playbook playbook.yaml -i inventory/hosts -vvv
```

