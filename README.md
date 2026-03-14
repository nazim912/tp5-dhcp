# tp5-dhcp
avoir l'ip automatiquement

j ai mis un routeur un switch et 2 pc

routeur:

ip 192.168.1.1 mask 255.255.255.0

jai cree dhcp pool lan

network 192.168.1.0
default router 192.168.1.1
dns 8.8.8.8

sur les pc jai choisi dhcp

les pc ont pris une ip automatique

test ping 192.168.1.1

ca marche
