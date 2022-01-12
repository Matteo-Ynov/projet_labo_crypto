# Projet fil rouge - Labo Cryptomonnaies

## Techno utilisée : Smart contract

* Cas d'utilisation : élections présidentielles.
* Utilité : garantir une élection juste et sans trucage grâce à la transparence de la blockchain. L'anonymat des votes reste conservé étant donné que les noms sont remplacés par des adresses. Chaque vote peut être relié à une adresse et n'est pas falsifiable. De plus aucun temps de décompte des voix n'est nécessaire étant donné qu'il est géré par smart contract.
* Fonctionnement : chaque personne en âge de voter se voit attribuer un wallet. Ce dernier recevra un coin (sans véritable valeur, faisant simplement office de bulletin de vote ) avant chaque tour de l'élection qu'il pourra envoyer au candidat de son choix (uniquement si ce dernier s'est bien présenté ). Le ou les candidats en recevant le plus pourront passer au tour d'après, en suivant les règles d'une élection présidentielles classiques. Le smart contract consistera à déterminer les candidats ayant le plus de voix. Ainsi, personne ne pourra contester les votes ou dire que l'élection était truquée.

* Cas particulier :
    * L'électeur ne vote pas : les tokens ne sont distribués avant chaque tour qu'aux utilisateurs ayant un wallet vide
    * L'électeur vote blanc : une adresse "blanche" est mise à disposition pour les électeurs ne souhaitant pas se prononcer
    * Ou vont les coins après chaque tour ? : les coins sont retirés des wallets des candidats ( possiblement par smart contract également ? ) après chaque tour, puis envoyer à une adresse spéciale qui brûlera les coins
    * DM discord si autre question :)
