# ansible-openvpn
add vpn server host to "inv" file to group "vpn"

run
```
ansible-playbook setup.yml -u root -v
```

start openvpn client
```
cd ~/openvpn/vpn.server/
sudo openvpn conf.ovpn
```
