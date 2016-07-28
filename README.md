ansible-get_ssh_keys-role
=========================

Grabs local ssh keys and sends to ansible host for connecting to other servers. Use with caution!

The use-case for this is pushing and pulling private github repos on a vagrant box without needing to enter user name and password each time. Assumes that the key pair are passwordless.


Variables
---------

```
private_key: /path/to/your/private/key #default: ~/.ssh/id_rsa
 
public_key: /path/to/your/public/key  #default: ~/.ssh/id_rsa.pub
```

License
---

The project is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

---
