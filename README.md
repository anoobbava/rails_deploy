## To test connectivity

`ansible-playbook connection_test.yml -i inventory.txt`

## To Deploy application

`ansible-playbook build.yml -i inventory.txt --ask-vault-pass`
