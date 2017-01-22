# vagrant-template-basic
basig template for a vagrant machine allowing to setup a local domain + deployment by ansible

1. clone this project
2. customize Vagrantfile
3. customize ansible/playbook.yaml
4. run

```
vagrant box update
vagrant up
```

the content inside application will be mounted into /var/www/html
