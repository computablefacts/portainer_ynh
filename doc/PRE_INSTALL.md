ATTENTION: this app change the LDAP configuration to make it available to the
Docker container of portainer.
Thus it opens the port 389 on the firewall and the LDAP is externally accessible.
It could be a major security concern if your YunoHost server is directly accessible
on Internet without another firewall or a box in front of it that block the port 389.
In this case, it's highly recommended to not install this app on your YunoHost instance.
