# ansible-SP
Docker &amp; Docker compose on Ubuntu 20.04(LTS)

Host file needed.
```
echo "target_IP" > hosts
```

Use this playbook
```
ansible-playbook -i hosts docker-on-ubuntu20.04.yml
```
