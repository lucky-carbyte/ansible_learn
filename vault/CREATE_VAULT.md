### in order to create vault
` ansible-vault create vault/cisco.yml `
### if using vault do not forget
` ansible-playbook -i inventory.yml get_int.yml --ask-vault-pass `
