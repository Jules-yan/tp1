# Answers

Nom : Descamps
Prénom : Jules-Yan

# 1.
Qu'est-ce qu'une instance EC2 ?

C'est un serveur virtuel hébergé dans EC2 (elastic compute cloud) pour exécuter des applications sur l'infrastructure AWS

# 2.
Qu'est-ce qu'un VPC ?

espece de bulle ou on défini notre réseau nous meme
Amazon Virtual Private Cloud (VPC) permet de lancer des ressources AWS dans un réseau virtuel défini. Ce réseau virtuel ressemble beaucoup à un réseau traditionnel et présente l'avantage d'utiliser l'infrastructure évolutive d'AWS. 

# 3.
A quoi sert un NSG ?

Un Network Security Group est constitué d'un ensemble de règles de contrôle d'accès décrivant les filtres de trafic. Ceux-ci peuvent être associés à une machine virtuelle ou à un sous-réseau de la même région. Les règles définies dans le NSG servent de filtres. Sur le chemin d'entrée, ils sont appliqués avant que le trafic entre dans la VM.

# 4.
Quelles sont les 5 propriétés désirables du cloud ?

Les 5 propriétés désirable du cloud sont le :
Paiement à l'usage (Le paiement à l’utilisation autorise les firmes à ne payer que pour les ressources consommées.)
Elastique (L’élasticité offre l’opportunité d’augmenter ou de réduire la consommation de ressources en fonction des besoins de l’entreprise.)
Ouvert
Mutualisé
Approvisionnement en Libre-service (L’approvisionnement en libre service permet aux utilisateurs finaux d’accéder à n’importe quelle ressource informatique à la demande.)

# 5.
Qu'est-ce que l'A/B Testing ?

L’A/B testing consiste à comparer deux versions d’une page web ou d’une application afin de vérifier laquelle est la plus performante. Ces variations, dénommées A et B, sont présentées de manières aléatoires aux utilisateurs. Une partie d’entre eux sera alors dirigée vers la première version tandis que l’autre sera affectée à la seconde. Une analyse statistique permet par la suite de tester l’efficacité de la version A et B sur différents indicateurs comme le taux de conversion.
b
# 6.
Comment programmer le cloud ?

Il faut utiliser la configuration Infrastructure as Code

# 7.
Quelle est la technique pour faire un déploiement sans interruption de service ?

En faisant du Canary Release

# 8.
Qu'est-ce que le Canary release ?

Le canary release est un pattern qui permet de faire tester les dernières modifications réalisées (appelée version N+1) à une tranche de population restreinte avant de réaliser un déploiement général de cette version.
Ce pattern permet de tester les modifications et de s’assurer qu’elles fonctionnent correctement.

# 9.
Comment changer de taille de machine virtuelle ?

Il y a une interface graphique sur le provider, Amazon Web Service par exemple. On peux manuellement augmenter la taille de sa Machine Virtuelle et automatiquement l'infrastructure est modifiée.
On va dans les paramètres de la machine et on modifie la taille de la VM comme on le souhaite.

# 10.
Qu'est-ce que le Blue/Green deployment ?

Le Blue Green Deployment repose sur deux environnements de production, qui doivent être à la base identiques. Supposons que notre application est déployée dans l’environnement de production Blue. Nous voulons procéder à un nouveau déploiement. Notre application sera déployée dans un premier temps dans le second environnement de production (Green). Une fois l’application déployée dans cet environnement, nous pouvons simplement router nos utilisateurs vers ce dernier, qui devient désormais notre environnement de production.
