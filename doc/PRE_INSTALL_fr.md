ATTENTION: Cette app change la configuration du LDAP afin que le container Docker
de portainer puisse y accéder.
Pour cela, elle ouvre le port 389 dans le firewall donc le LDAP devient accessible
de l'extérieur.
Cela peut être un trou de sécurité majeur si votre serveur YunoHost est directement
accessible depuis Internet sans un autre firewall ou une box devant lui qui bloquent
le port 389.
Dans ce cas, il est fortement recommandé de ne pas installer cette application
sur votre serveur YunoHost.
