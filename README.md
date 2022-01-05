# ansible-galaxy

https://galaxy.ansible.com/search?keywords=&order_by=-download_count&page=1

### Build collections

Create collection:
```bash
ansible-galaxy collection init shubhamtatvamasi.test-collection
ansible-galaxy collection build
ansible-galaxy collection publish
ansible-galaxy collection install
```

### Install collections

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

### Roles

create new ansible role:
```bash
ansible-galaxy role init magma
```
