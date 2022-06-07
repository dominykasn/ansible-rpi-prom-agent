# ansible-rpi-prom-agent
Basic ansible playbook for prometheus agent on raspberry pi

Please change hosts file to your raspberry pi hostnames which you wish to install prometheus agent on.
```
[raspberrynodes]
rasp1.local
rasp2.local
...
```

Run the playbook with:
```
ansible-playbook -i hosts site.yml
```

Also if you wish you can always change group_vars/all file which includes my personally preferred variables, enjoy :)
