# IV. Guide to run ansible playbook
- Step 1: Input password to .vault file
```
$ touch .vault
```

- Step 2: Input IP host to labhok_infra/inventory/staging


- step 3: Run playbook file for staging
```
$ ansible-playbook -i inventory/staging playbook-stg.yml
```
