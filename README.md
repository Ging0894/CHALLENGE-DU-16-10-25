⌨️ Challenge 16/10/25

ENONCER :

Au programme ce soir, un peu de maths 😱
Pour les adresses IP et masques de sous-réseau suivants, calculez :
•	l’adresse de réseau
•	l’adresse de broadcast
•	le nombre d’adresses utilisables par des machines
•	la plage d’adresses disponibles
Certains utilisent la notation « classique », d’autres la notation CIDR :
•	192.168.13.67/24
•	172.16.0.1 – 255.255.255.0
•	172.16.27.32/23
•	10.7.5.1 – 255.255.128.0
•	10.42.0.82/12
Essayez de calculer tout à la main (avec la méthode de votre choix, idéalement essayez d’utiliser les deux !), puis vérifiez vos calculs avec une calculatrice en ligne (exemple) –

REPONSE :

-	192.168.13.67/24 : 
Adresse réseau : 192.168.13.0
Adresse de diffusion : 192.168.13.255
Nombre d’adresses utilisables : 254
Plage d’adresses disponibles : 192.168.13.1 → 192.168.13.254

-	172.16.0.1 – 255.255.255.0 : 
Adresse réseau : 172.16.0.0
Adresse de diffusion : 172.16.0.255
Nombre d’adresses utilisables : 254
Plage d’adresses disponibles : 172.16.0.1 → 172.16.0.254

-	 172.16.27.32/23 :
Adresse réseau : 172.16.26.0
Adresse de diffusion : 172.16.27.255
Nombre d’adresses utilisables : 510
Plage d’adresses disponibles : 172.16.26.1 → 172.16.27.254

-	 4. 10.7.5.1 – 255.255.128.0
Adresse réseau : 10.7.0.0
Adresse de diffusion : 10.7.127.255
Nombre d’adresses utilisables : 32 766
Plage d’adresses disponibles : 10.7.0.1 → 10.7.127.254

-	 5. 10.42.0.82/12
Adresse réseau : 10.32.0.0
Adresse de diffusion : 10.47.255.255
Nombre d’adresses utilisables : 1 048 574
Plage d’adresses disponibles : 10.32.0.1 → 10.47.255.254


