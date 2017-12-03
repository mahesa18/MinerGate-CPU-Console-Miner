# MinerGate-CPU-Console-Miner
MinerGate CPU Console miner (Windows x64, Linux, Mac)

https://fr.minergate.com/faq
-

Pour lancer le miner avec les options désirées -->  minergate-cli -user MON-EMAIL --bcn 4
Où MON-EMAIL correspond à mon adreese mail de login sur MinerGate, -bcn etant la monnaie minée et 2 le nombre de cores utilisés.
Exemple pour miner du Bytecoin avec 4cores -->  minergate-cli -user mon.adresse@email.com --bcn 4

Mais on peut éalement miner deux monnaies à la fois par exemple -->  minergate-cli -user mon.adresse@email.com -bcn 2 -xmr 2
Où ici on mine du Bytecoin sur 2 cores et du Monero sur 2 cores.

Vous pouvez également miner en monnaie et la faire "merged" sur une autre,
Exemple -->  minergate-cli -user mon.adresse@email.com -bcn 2 fcn+dsh 2
Dans cet exemple, on mine du Bytecoin sur 2 cores et du FantomCoin "merged" sur du Dashcoin également sur deux coeurs.

```
Voici la liste des monnaies minabe avec la console:
Bytecoin    =  BCN; 
Monero      =  XMR; 
FatomCoin   =  FCN; 
QuazarCoin  =  QCN; 
DigitalNote =  XDN; 
MonetaVerde =  MCN; 
Dashcoin    =  DSH
```
