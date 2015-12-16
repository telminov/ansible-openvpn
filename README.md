# ansible-openvpn
add host to "inv" file to group "vpn"

run 
```
ansible-playbook setup.yml -u root -v
```
or
```
ansible-playbook setup.yml -u root -v --ask-sudo-pass

start openvpn client
```
cd ~/openvpn/vpn.server/
sudo openvpn conf.ovpn
```
