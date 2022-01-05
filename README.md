# ansible-galaxy

https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1

create new ansible role:
```bash
ansible-galaxy init magma
```

list all collections:
```bash
ansible-galaxy collection list
```

Install collection package:
```bash
ansible-galaxy collection install community.general
```

Install all requirements:
```bash
ansible-galaxy install -r requirements.yaml
```
