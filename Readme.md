# *Apache - Sys1

---

This YAML script is specifically designed to handle the configuration management of an Apache2 server on a designated host. It encompasses all aspects related to the provided domain names.


# Get started 

- Set `PermitRootLogin` to `yes` on the file `/etc/ssh/sshd_config` in the server+.

- Then `sudo sytemctl restart ssh`.


- on the file `ip_server` :

```sh
192.168.0.127
``` 
- on the file `url`:

```sh
www.titre.com
jeso.donovan.jeso
``` 

- Run the script.yaml with the following commands: 

```sh
ansible-playbook -i ip_server script.yaml -k
```