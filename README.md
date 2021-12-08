# ansible-poormans-vault

Check lookup is working:

```bash
ansible-playbook -i inventory main.yml
```

Encrypt password file:

```bash
ansible-vault encrypt passwords.ini
```

Check if lookup is working with encryption:

```bash
ansible-playbook -i inventory main.yml --ask-vault-password
```
