------------------------------
https://fr.minergate.com/faq
------------------------------

Pour lancer le miner avec les options d�sir�es -->  minergate-cli -user MON-EMAIL --bcn 4

O� MON-EMAIL correspond � mon adreese mail de login sur MinerGate, -bcn etant la monnaie min�e et 2 le nombre de cores utilis�s.

Exemple pour miner du Bytecoin avec 4cores -->  minergate-cli -user mon.adresse@email.com --bcn 4

----------------

Mais on peut �alement miner deux monnaies � la fois par exemple -->  minergate-cli -user mon.adresse@email.com -bcn 2 -xmr 2

O� ici on mine du Bytecoin sur 2 cores et du Monero sur 2 cores.

----------------

Vous pouvez �galement miner en monnaie et la faire "merged" sur une autre,

Exemple -->  minergate-cli -user mon.adresse@email.com -bcn 2 fcn+dsh 2

Dans cet exemple, on mine du Bytecoin sur 2 cores et du FantomCoin "merged" sur du Dashcoin �galement sur deux coeurs.


-------------------
Voici la liste des monnaies minabe avec la console:
Bytecoin    =  BCN
Monero      =  XMR
FatomCoin   =  FCN
QuazarCoin  =  QCN
DigitalNote =  XDN
MonetaVerde =  MCN
Dashcoin    =  DSH
-------------------