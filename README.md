# pihole-dnsovertls

```git clone https://github.com/Expand-sys/pihole-dnsovertls```

```cd pihole-dnsovertls```

Edit `inventory` to be the ipaddress of your pihole server
Edit `vars/default.yml` to have your chosen domain name and your email for ssl certs

```ansible-playbook -i inventory main.ansible.yml -k```
