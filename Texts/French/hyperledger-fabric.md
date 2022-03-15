---
keywords: Investing,Cryptocurrency,Blockchain
title: Tissu Hyperledger
description: Hyperledger Fabric est une plate-forme permettant de créer divers produits, solutions et applications basés sur la blockchain à usage professionnel.
---

# Tissu Hyperledger
## Qu'est-ce que le tissu Hyperledger ?

Hyperledger Fabric est un cadre de [blockchain modulaire](/blockchain) qui sert de base au développement de produits, de solutions et d'applications basés sur la blockchain à l'aide de composants plug-and-play destinés à être utilisés dans des entreprises privées.

Hyperledger Fabric a été lancé par Digital Asset et IBM et est maintenant devenu une entreprise collaborative intersectorielle, qui est actuellement hébergée par la Fondation Linux. Parmi les nombreux projets Hyperledger, Fabric a été le premier à sortir du stade « incubation » et à atteindre le stade « actif » en mars 2017.

## Comment fonctionne Hyperledger Fabric

Les réseaux de blockchain traditionnels ne peuvent pas prendre en charge les transactions privées et les contrats confidentiels qui sont de la plus haute importance pour les entreprises. Hyperledger Fabric a été conçu en réponse à cela comme une base modulaire, évolutive et sécurisée pour offrir des solutions de blockchain industrielles.

Hyperledger Fabric est le moteur open source pour la blockchain et prend en charge les fonctionnalités les plus importantes pour évaluer et utiliser la blockchain pour les cas d'utilisation professionnelle.

Au sein des réseaux industriels privés, l'identité vérifiable d'un participant est une exigence primordiale. Hyperledger Fabric prend en charge les adhésions basées sur l'autorisation ; tous les participants au réseau doivent avoir des identités connues. De nombreux secteurs d'activité, tels que la santé et la finance, sont liés par des réglementations sur la protection des données qui imposent de conserver des données sur les différents participants et leur accès respectif à divers points de données. Fabric prend en charge une telle adhésion basée sur les autorisations.

### Architecture modulaire

L'architecture modulaire d'Hyperledger Fabric sépare le flux de travail de traitement des transactions en trois étapes différentes : [les contrats intelligents](/smart-contracts) appelés code de chaîne qui comprennent le traitement logique distribué et l'accord du système, la commande des transactions, ainsi que la validation et l'engagement des transactions. Cette ségrégation offre de multiples avantages :

- Un nombre réduit de niveaux de confiance et de vérification qui maintient le réseau et le traitement sans encombrement

- Amélioration de l'évolutivité du réseau

- Meilleures performances globales

De plus, la prise en charge par Hyperledger Fabric du plug-and-play de divers composants permet une réutilisation facile des fonctionnalités existantes et une intégration prête à l'emploi de divers modules. Par exemple, s'il existe déjà une fonction qui vérifie l'identité du participant, un réseau au niveau de l'entreprise doit simplement brancher et réutiliser ce module existant au lieu de créer la même fonction à partir de zéro.

Les participants au réseau ont trois rôles distincts :

- Endosseur

- Commis

- Consentement

En résumé, la proposition de transaction est soumise au pair endosseur conformément à la politique d'endossement prédéfinie concernant le nombre d'endosseurs requis. Après des endossements suffisants par le(s) endosseur(s), un lot ou un bloc de transactions est livré au(x) commiter(s). Les committers valident que la politique d'endossement a été suivie et qu'il n'y a pas de transactions en conflit. Une fois les deux vérifications effectuées, les transactions sont enregistrées dans le grand livre.

<!--6376536357DF4ADC77E5CAB266DCF459-->

Source de l'image : IBM

Étant donné que seules les instructions de confirmation, telles que les signatures et les ensembles de lecture/écriture, sont envoyées sur le réseau, l'évolutivité et les performances du réseau sont améliorées. Seuls les endosseurs et les committers ont accès à la transaction, et la sécurité est améliorée avec un nombre réduit de participants ayant accès aux points de données clés.

## Exemple de tissu Hyperledger

Supposons qu'un fabricant souhaite expédier des chocolats à un détaillant ou à un marché de détaillants spécifique (c'est-à-dire tous les détaillants américains) à un prix spécifique mais ne souhaite pas révéler ce prix sur d'autres marchés (c'est-à-dire les détaillants chinois).

Étant donné que le mouvement du produit peut impliquer d'autres parties, comme les douanes, une compagnie maritime et une banque de financement, le prix privé peut être révélé à toutes les parties concernées si une version de base de la technologie blockchain est utilisée pour soutenir cette transaction.

Hyperledger Fabric résout ce problème en gardant les transactions privées privées sur le réseau ; seuls les participants qui ont besoin de savoir connaissent les détails nécessaires. Le partitionnement des données sur la blockchain permet à des points de données spécifiques d'être accessibles uniquement aux parties qui ont besoin de savoir.

## Critique de Hyperledger Fabric

Le paroxysme du crypto-enthousiasme a éclaté en 2018 après l'effondrement du prix du bitcoin (qui a atteint son apogée le 17 décembre 2017). Les affirmations trop optimistes sur la valeur de la nouvelle technologie ont été remplacées par du scepticisme, et les technologies connexes, y compris Hyperledger, ont également souffert de ce scepticisme.

### Concurrents d'Hyperledger Fabric

Hyperledger Fabric est en concurrence avec d'autres projets Hyperledger comme Iroha, Indy et Sawtooth. Il est également en concurrence avec Corda de R3, qui est également un DLT privé basé sur des autorisations.

La société de services Blockchain Chainstack a publié un article en janvier 2020 qui montre que le développement de Corda a été historiquement plus élevé que le développement de Fabric, bien que le développement de Fabric ait dépassé celui de Corda au troisième trimestre 2019 lorsque Fabric est passé à GitHub.

Le rapport Chainstack montre que bien qu'il y ait trois fois plus de développeurs travaillant sur Fabric, les développeurs Corda ont fait plus de deux fois plus de contributions au code, et les développeurs Fabric poussent beaucoup moins de code par développeur que les développeurs de Corda.

### Hyperledger Fabric n'est pas une blockchain et n'est pas efficace

Plusieurs critiques d'Hyperledger Fabric soulignent qu'une blockchain privée basée sur des autorisations avec les fonctionnalités d'Hyperledger Fabric n'est pas une blockchain, et les technologies actuelles non-blockchain sont beaucoup moins chères et offrent le même niveau de sécurité. Stuart Popejoy de Cointelegraph a présenté le cas comme ceci :

>

> L'architecture de Fabric est bien plus complexe que n'importe quelle plate-forme blockchain tout en étant moins sécurisée contre les falsifications et les attaques. On pourrait penser qu'une blockchain "privée" offrirait au moins évolutivité et performances, mais Fabric échoue également ici. En termes simples, les pilotes construits sur Fabric seront confrontés à un déploiement complexe et non sécurisé qui ne pourra pas évoluer avec leurs activités .

>

Hyperledger Fabric a également été critiqué pour son manque de résilience. Une équipe de chercheurs de la Sorbonne à Paris et du CSIRO - Data61, l'agence scientifique nationale australienne, a constaté que des retards importants sur le réseau réduisaient la fiabilité de Fabric : "[B] y retardant la propagation des blocs, nous avons démontré que Hyperledger Fabric ne fournit pas suffisamment de garanties de cohérence à déployer dans des environnements critiques. "

## Hyperledger Fabric 2.0 Sortie en janvier 2020

En janvier 2020, Hyperledger Fabric 2.0 a été publié pour répondre à certaines des critiques existantes. Selon Ron Miller de Techcrunch, « les mises à jour les plus importantes impliquent de forcer les parties à s'entendre avant que de nouvelles données puissent être ajoutées au grand livre, ce que l'on appelle la gouvernance décentralisée des contrats intelligents ».

Bien que la mise à jour ne soit pas un changement radical dans la simplicité ou l'applicabilité de Fabric, elle démontre que des progrès continuent d'être réalisés dans l'industrie de la crypto-monnaie au-delà de la crypto-manie qui s'est produite en 2018. Au cours des cinq à dix prochaines années, c'est s'attend à ce que la blockchain d'entreprise trouve sans aucun doute son bon usage.

## Points forts

- Hyperledger est un cadre de registre distribué open source de niveau entreprise lancé par la Linux Foundation en décembre 2015.

- Étant donné que Hyperledger Fabric est privé et nécessite une autorisation d'accès, les entreprises peuvent séparer les informations (comme les prix), et les transactions peuvent être accélérées car le nombre de nœuds sur le réseau est réduit.

- Fabric 2.0 est sorti en janvier 2020. Les principales caractéristiques de cette version sont des transactions plus rapides, une technologie de contrat intelligent mise à jour et un partage de données rationalisé.

- Fabric est une plate-forme de technologie de registre décentralisée (DLT) hautement modulaire qui a été conçue par IBM pour une utilisation en entreprise industrielle.

