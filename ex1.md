**_EX1_** 


Q1.1 : L'adresse de sous réseau du serveur est 172.16.10.10/24. Cela correspond au sous-réseau 172.16.10.10 où le dernier octet peut être utilisé pour définir les adresses du sous réseau. En clair, sur ce sous-réseau toute machine aura une adresse IP du type 172.16.10.X où X prends pour valeur un entier entre 1 et 254 (les première et dernière étant par convention réservé respectivement au sous-réseau et à la diffusion).
Par conséquent, l'adresse du PC client 172.16.100.50/24 ne peut appartenir à ce sous-réseau. Pour changer l'adresse IP en commande graphique, il suffit d'aller dans paramètres, internet et réseau, allez dans la connexion ethernet(ou wifi) et ouvrir ses paramètres puis d'allez dans ceux d'IPV4 et la de changer manuellement l'adresse IP.\
Q1.2 : Une des possibilités est que le nom de l'utilisateur ne se trouve pas dans le DNS. Il faudrait alors utiliser les commandes suivantes ipconfig / flushdns, puis ipconfig / registerdns.\
Q1.3 : Le client ne récupère pas la première adresse que celle-ci est réservé au sous-réseau. \
Q1.4 : A priori rien ne l'empêche d'être compatible dans un sous-réseau de type 172.16.10.10/24. \

