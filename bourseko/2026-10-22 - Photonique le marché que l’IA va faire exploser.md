---
date: 2026-10-22
heure: "19:17"
source: Bourseko
objet: "Photonique : le marché que l’IA va faire exploser"
tags:
  - bourseko
---

# Photonique : le marché que l’IA va faire exploser

**Reçu le :** jeudi 22 octobre 2026 à 19:17

En mars dernier, Nvidia a annoncé un investissement de **2 milliards de dollars dans Lumentum et autant dans Coherent**, deux entreprises que peu d’investisseurs particuliers connaissent, mais que le géant des puces juge désormais stratégiques.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/21937ddb-49e8-49f5-867a-cbaa0b38dc3c/Capture_d_e%CC%81cran_2026-10-21_a%CC%80_10.05.40.png?t=1792569958)

Si Nvidia engage de telles sommes dans ces deux spécialistes de la photonique, c’est que **cette technologie devient critique pour la prochaine phase de développement de l’IA**. Son déploiement pourrait transformer en profondeur les infrastructures sur lesquelles repose le secteur, avec un potentiel de marché gigantesque dans les années à venir.

Pour mesurer l’importance de cet enjeu, il faut comprendre ce sujet extrêmement technique. C’est pourquoi nous avons demandé à **Julien Martin-Prin**, qui avait déjà signé notre article sur le MOAT de Nvidia, de coécrire cette newsletter avec nous afin d’expliquer le plus simplement possible ce qui se joue pour les infrastructures d’IA.

## Pourquoi l'IA a besoin de lumière

Vous le savez, faire tourner l’intelligence artificielle demande énormément de puissance de calcul. Et à ce jeu, Nvidia s’est imposé avec ses GPU.

Cependant, même un GPU extrêmement puissant peut passer une partie de son temps à attendre des données. En effet, les plus grands modèles nécessitent de répartir le travail entre de nombreuses puces, qui doivent échanger leurs résultats pour avancer ensemble. Lorsque ces échanges sont trop lents, une partie de la puissance disponible reste donc inutilisée.

Pour l’illustrer, prenons le cas d’un chantier. Même avec les meilleurs maçons, les travaux avanceront difficilement si les matériaux arrivent en retard et si les consignes circulent mal. Embaucher davantage de monde ne résoudra donc pas le problème tant que les équipes ne pourront pas travailler efficacement ensemble.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/bc9d3ec2-6461-4d2a-bca1-262fe6f60200/image.png?t=1792682113)

Dans un data center, cette coordination repose sur le réseau, c’est-à-dire l’ensemble des câbles et des équipements qui permettent aux puces de communiquer entre elles. Pour comprendre son fonctionnement, deux notions sont essentielles :

- **La bande passante** correspond à la quantité de données que le réseau peut transporter chaque seconde. Plus les puces ont d’informations à échanger, plus elles ont besoin de bande passante.

- **La latence** mesure le délai nécessaire pour que les données arrivent à destination. Elle est particulièrement importante lorsque les puces ont besoin des résultats des autres pour poursuivre leurs calculs, car tout retard les oblige à patienter.

Pour faire circuler ces données, deux solutions coexistent : **des signaux électriques dans des fils de cuivre, ou des signaux lumineux dans de la fibre optique.** Dans ce second cas, le signal électrique est converti en lumière au départ, puis reconverti à l’arrivée. C’est à cette utilisation de la lumière pour transmettre l’information que nous faisons référence en parlant de photonique.

Sur de très courtes distances, le cuivre conserve un avantage majeur, car il permet de relier directement des puces qui fonctionnent déjà avec des signaux électriques. Il évite ainsi les conversions en lumière et les composants nécessaires pour les réaliser, ce qui se traduit généralement par un coût et une consommation d’énergie plus faibles.

**En revanche, lorsque la distance augmente, le signal électrique s’affaiblit et se déforme.** Le transmettre correctement devient d’autant plus difficile que le débit demandé est élevé, et continuer à utiliser le cuivre nécessite alors d’ajouter des composants capables de compenser ces dégradations. Le coût et la consommation électrique augmentent donc à mesure que l’on cherche à prolonger sa portée.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/cbf6ef7d-f0bc-4b0e-8cec-ffa4f10957c6/photonique-02-cuivre-fibre_1.png?t=1792683650)

**La fibre devient particulièrement intéressante dans ces conditions, car elle peut transporter de grandes quantités de données sur de longues distances avec peu d’atténuation du signal.** Elle est également insensible aux perturbations électromagnétiques qui affectent les liaisons en cuivre, ce qui contribue à expliquer son utilisation déjà très répandue pour relier des bâtiments ou des équipements éloignés au sein des data centers.

La fibre n’a donc pas attendu l’IA pour trouver sa place. Elle est utilisée depuis des décennies dans les télécommunications, et vous en profitez probablement déjà pour votre connexion Internet. Mais son intérêt sur certaines liaisons ne justifie pas de remplacer tous les câbles en cuivre, car tant que ceux-ci assurent le débit demandé sur la distance à parcourir, à moindre coût et avec moins d’énergie, les fabricants ont toutes les raisons de les conserver.

Dans l’industrie, cet arbitrage se résume par le mantra ***« Use copper if you can, optics if you must »***, autrement dit, « du cuivre quand on peut, de l’optique quand il le faut ».

Cependant, avec l’IA, les volumes de données échangés entre les GPU et les débits nécessaires augmentent tellement que cet équilibre se déplace et que le cuivre atteint ses limites sur des connexions de plus en plus courtes, là où il suffisait jusqu’ici. **L’IA crée ainsi les conditions pour rapprocher la lumière des puces, alimentant un marché qui se chiffre en dizaines de milliards de dollars.**

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/c0929c1b-8b98-4229-8235-b869073247a7/photonique-v2-b-frise.png?t=1792569275)

## Le cuivre face au mur de la vitesse

Pour savoir jusqu’où la lumière peut se rapprocher des puces, il faut entrer dans un data center, qui abrite plusieurs réseaux. Celui qui le relie à Internet, le *front-end* , est hérité des télécoms et fonctionne depuis longtemps en fibre optique.

Les enjeux se concentrent surtout sur le *back-end* , qui relie les puces entre elles pour qu’elles calculent ensemble. Ce réseau, presque inexistant avant l’IA, s’organise aujourd’hui en trois étages :

- Le **scale-up** relie un groupe de puces pour qu’elles fonctionnent comme un seul ensemble de calcul, au sein d’une même armoire de serveurs, appelée *rack* , ou d’un petit groupe d’armoires.

- Le **scale-out** relie ces ensembles entre eux au sein d’un même data center pour former des *clusters* , c’est-à-dire des grappes de dizaines de milliers de GPU.

- Le **scale-across**, apparu en 2025, étend cette logique à plusieurs data centers. Faute de place, d’électricité et de capacités de refroidissement suffisantes sur un seul site, les géants de la tech les relient par des liaisons à très haut débit, à l’échelle d’un État américain, voire d’un pays, pour les faire fonctionner comme un seul méga-cluster.

*Fairwater* , chez Microsoft, et *Prometheus* , chez Meta, sont les deux premiers exemples publics de cette dernière approche. Leurs déploiements sont prévus en 2026 et 2027, avec des puissances de 2 à 5 gigawatts, soit l’équivalent de deux à cinq réacteurs nucléaires.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/8535ecc8-ad21-4763-a3a5-780db2325fde/photonique-03-trois-etages_1.png?t=1792688008)

Pour comprendre comment les données circulent, suivons celles d’un GPU. Elles passent sous forme électrique par la carte réseau du serveur, qui les transmet à un **transceiver, ou émetteur-récepteur optique**. Ce module transforme les signaux électriques en lumière grâce à un laser pour les transmettre dans la fibre et effectue la conversion inverse à la réception.

Les données parcourent ainsi la fibre jusqu’à un second transceiver, qui les reconvertit en signaux électriques pour la puce du switch, l’équipement qui les aiguille vers leur destination. Ces modules forment le cœur du marché de l’optique.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/da5482a8-c5ab-4e5d-acec-15c256198e6c/image__2206___1_.png?t=1792680400)

Un transceiver

À l’intérieur de l’armoire, en revanche, les échanges sont particulièrement intenses et les distances beaucoup plus courtes, si bien que le cuivre règne encore sans partage. Le GB200 NVL72 de Nvidia relie ainsi ses **72 GPU grâce à environ 5 000 câbles DAC en cuivre par rack**.

Même Google, qui fait figure d’exception avec son réseau ICI, conserve le cuivre à l’intérieur de l’armoire et ne passe à l’optique que pour relier ses TPU, les puces d’IA du groupe, d’une armoire à l’autre.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/82ab59fb-6cce-4442-a988-4f824dba0f33/image.png?t=1792682445)

GB200 NVL72 et ses câbles en cuivre

Le cuivre doit cette résistance aux très courtes distances en jeu, car dans une armoire, le GPU se trouve rarement à plus d’un mètre et demi du switch. À cette échelle, de simples câbles en cuivre passifs, appelés *DAC* , suffisent et consomment **25 à 30 fois moins d’énergie** qu’un transceiver optique classique pour transmettre la même quantité de données. Ainsi, tant que le cuivre assure ces échanges correctement, les fabricants ont donc tout intérêt à le conserver.

Cependant, cet avantage devient plus difficile à préserver à mesure que les débits augmentent. Une connexion transporte ses données sur plusieurs voies parallèles, un peu comme les files d’une autoroute. La plupart des équipements installés font aujourd’hui passer 100 gigabits par seconde sur chaque voie, tandis que la génération à 200 gigabits se déploie et que l’industrie prépare déjà des prototypes à 400 gigabits. Chaque doublement impose des contraintes bien plus fortes que le simple changement de chiffre ne le laisse penser, et **le cuivre peine déjà à suivre à 200 gigabits par seconde par voie.**

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/a89da4e0-7764-464e-96f7-8c1f695ce5fc/photonique-v2-c-jauge_1.png?t=1792684087)

Par ailleurs, comme on l’a vu, le signal électrique se déforme avec la distance, d’autant plus que les impulsions sont courtes et rapprochées. Un mètre de câble qui ne posait aucun problème à une génération donnée peut ainsi devenir un obstacle à la suivante.

Pour simplifier, avec la technologie actuelle, on estime que la limite du cuivre sur une distance utilisable se situe autour de 400 gigabits par seconde par voie. Les démonstrations présentées cette année à l’ECOC, la grande conférence européenne de l’optique, ont d’ailleurs montré qu’à ce niveau, le signal devient trop bruité pour dépasser une trentaine de centimètres sans changer de technique d’encodage.

Il reste possible de prolonger cette portée grâce au cuivre actif, dont les extrémités embarquent des circuits électroniques chargés d’amplifier et de nettoyer le signal. Mais ces circuits consomment de l’électricité, dégagent de la chaleur et épaississent les câbles, qui deviennent plus lourds et moins pratiques à installer. L’avantage du cuivre s’amenuise donc à mesure que les débits augmentent, jusqu’au moment où l’optique s’impose et où l’on retrouve notre *« optics if you must »* (optique quand il le faut).

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/da6321a4-1a64-4197-ad2f-21efbb4cbdd0/photonique-05-tableau-cuivre-optique.png?t=1792684529)

Pour les fabricants de composants optiques, cette bascule ajoute un second moteur de croissance au premier. Le scale-out et le scale-across continueront de se développer avec la multiplication des racks et des data centers, mais aussi avec la hausse des débits.

Le scale-up ouvre, quant à lui, un débouché entièrement nouveau, puisque l’optique pourra y remplacer des connexions aujourd’hui assurées par le cuivre. **Les besoins pourront donc augmenter même à nombre de GPU constant.** On estime ainsi que la valeur des composants d’interconnexion par puce dans le scale-up, aujourd’hui comprise entre 1 000 et 2 000 dollars, pourrait atteindre **20 000 à 25 000 dollars en 2030**.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/7cf7c38c-cbf2-40bf-bccb-6c60eb50e9e7/image.png?t=1792683897)

Source : Yole Group

Encore faut-il trouver de la place pour toutes ces connexions, car le pourtour des puces, par lequel entrent et sortent les données, est déjà presque entièrement occupé.

## Rapprocher la lumière de la puce

Ce rapprochement commence par les switchs du scale-out, qui aiguillent les données entre les groupes de GPU et utilisent déjà la fibre, avant de pouvoir s’étendre un jour aux GPU eux-mêmes. Dans leur configuration traditionnelle, les transceivers prennent la forme de **modules enfichables, appelés pluggables**, qui se branchent en façade, un peu comme une clé USB. Cet emplacement facilite leur maintenance, puisqu’un module en panne peut être retiré et remplacé individuellement.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/635042d8-2745-45e4-a297-1440afdf2934/image.png?t=1792682578)

*La façade d'un switch avec ses dizaines de modules enfichables branchés.*

Cet emplacement présente toutefois une limite, car le signal électrique doit encore parcourir quelques centimètres de cuivre entre la puce du switch et le module. À très haut débit, même ce court trajet suffit à le dégrader, si bien qu’il faut ajouter des circuits électroniques plus complexes pour compenser ces pertes, avec à la clé une consommation d’énergie et un dégagement de chaleur supplémentaires.

Pour limiter ces contraintes, les fabricants cherchent à rapprocher de la puce le **moteur optique**, c’est-à-dire l’ensemble des composants qui assure la conversion entre signaux électriques et lumineux. Deux architectures permettent ce rapprochement, avec des degrés d’intégration différents :

- Dans le **NPO**, pour *Near-Package Optics* , le moteur optique est placé juste à côté du *package* , le boîtier qui accueille et protège la puce.

- Dans le **CPO**, pour *Co-Packaged Optics* , le moteur optique est intégré dans le même package que la puce.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/d1cc56fc-d5e8-45c9-8352-31420e92326b/photonique-06-pluggable-npo-cpo.png?t=1792230901)

En raccourcissant le trajet électrique, on réduit les besoins de compensation du signal, et avec eux la consommation et la latence, tout en faisant entrer et sortir davantage de données dans un espace limité. Broadcom annonce ainsi une réduction de **65 % de la consommation de la partie optique** pour sa solution CPO par rapport aux modules enfichables. À terme, un CPO entièrement linéaire, c’est-à-dire sans circuit de compensation, pourrait même consommer aussi peu qu’un câble en cuivre passif.

### Quelle architecture privilégier ?

Ces gains ont toutefois une contrepartie, car l’intégration rend la fabrication plus complexe et certaines interventions plus coûteuses. Plus les composants sont étroitement associés, plus la panne d’une seule pièce risque d’imposer le remplacement d’un ensemble complet.

Pour limiter ce risque, la quasi-totalité des architectures conservent le **laser dans un module extérieur et remplaçable**, car il est à l’origine d’environ 95 % des pannes. Son rôle est de produire la lumière, qui est ensuite acheminée jusqu’au moteur optique pour y inscrire les données. Cette séparation permet de garder le laser, sensible à la chaleur, à distance de la puce et de le remplacer facilement lorsqu’il tombe en panne.

La situation est plus délicate lorsque le moteur optique lui-même est défaillant. En NPO, il reste séparé du package de la puce, même si son remplacement peut nécessiter une intervention sur la puce. Avec un CPO fortement intégré, en revanche, il peut être nécessaire de remplacer un ensemble beaucoup plus coûteux, voire une puce complète.

Les résultats des essais menés chez Meta sont néanmoins rassurants, avec une durée moyenne d’environ un million d’heures entre deux pannes pour le CPO et le NPO, contre 250 000 heures pour les modules traditionnels. Ils doivent toutefois être mis en regard du coût d’une intervention et de l’interruption de service qu’une panne, même rare, peut entraîner.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/0510c62b-1b57-4233-8da6-520d7d4a3c10/photonique-v2-e-pannes.png?t=1792569425)

Au-delà de la maintenance, cette intégration change aussi les rapports entre fournisseurs et clients. Avec les modules en façade, un exploitant peut acheter un switch équipé d’une puce Broadcom, puis choisir ses modules optiques auprès de plusieurs fabricants compatibles pour faire jouer la concurrence. Le NPO conserve une partie de cette souplesse, alors que le CPO la supprime complètement, puisque le client achète un bloc unique dont le concepteur de la puce a lui-même choisi les composants.

Nvidia et Broadcom peuvent ainsi renforcer leur maîtrise du système et capter une plus grande part de sa valeur, tandis que les fabricants de modules risquent de perdre une partie de leur rôle. Cette évolution explique la méfiance des géants du cloud, qui n’accepteront cette dépendance que si les gains sont considérables.

Le NPO offre donc un compromis intéressant, puisqu’il rapproche l’optique tout en conservant une certaine séparation entre les composants. Tant que les modules enfichables ou le NPO répondent aux besoins dans de bonnes conditions économiques, les exploitants ont peu de raisons de précipiter le passage au CPO, dont l’adoption pourrait être bien plus lente que ne le suggèrent les annonces. Pour notre part, au-delà des switchs du scale-out, **nous ne voyons pas le CPO se déployer à grande échelle au plus près des GPU, dans le scale-up, avant l’horizon 2030-2032.**

Le NPO, en revanche, est appelé à exploser bien plus tôt. Environ 80 % des Rubin Ultra, la future génération de puces de Nvidia, l’utiliseront, et il en ira de même pour les prochaines générations de Trainium, les puces d’Amazon, ainsi que pour la MI500 d’AMD. Parmi les grands concepteurs de puces pour l’IA, seul Google n’a pas encore vraiment de programme NPO.

### Les autres architectures

Les industriels cherchent donc à conserver les gains du rapprochement tout en limitant les contraintes de maintenance et la dépendance au fournisseur. C’est tout l’intérêt du **CPX, imaginé par l’américain Ciena**, qui consiste à monter le moteur optique sur un support plutôt que de le souder. Le moteur reste ainsi tout proche de la puce, mais peut être retiré et remplacé en cas de panne.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/800cfe12-fda9-4090-b603-88935697f9bc/image__2207___1_.png?t=1792680496)

Moteur optique CPX de Ciena

Cette approche peut s’appliquer aussi bien au NPO qu’au CPO, car ces deux termes décrivent l’emplacement du moteur optique par rapport à la puce, tandis que le CPX désigne une manière de le connecter. Il devient donc possible de rapprocher les composants sans les rendre tous indissociables.

Pour préserver également le choix des fournisseurs, les entreprises participantes définissent des caractéristiques communes dans un standard ouvert, **Open CPX, auquel plus de 50 entreprises ont déjà adhéré**. Plusieurs fabricants peuvent ainsi développer des composants compatibles et être mis en concurrence, tandis que cette base industrielle permet de construire un écosystème autour du format.

C’est à nos yeux l’approche la plus prometteuse à moyen et long terme, car elle répond à la fois aux difficultés de maintenance et à la dépendance commerciale, tout en accompagnant le mouvement de l’optique vers les puces. L’intervention reste plus lourde que le remplacement d’un module en façade, mais elle évite de changer tout un ensemble pour une seule pièce défaillante.

Enfin, **Arista Networks défend une autre voie avec le XPO**, qui conserve les modules en façade tout en augmentant fortement la quantité de données qu’ils peuvent transmettre. Les modules restent remplaçables et disponibles auprès de plusieurs fournisseurs, mais cette densité dégage tant de chaleur que chacun doit être raccordé à un circuit de refroidissement liquide. Une centaine d’entreprises ont rejoint le projet, mais nous y croyons peu pour deux raisons :

- **Le refroidissement complique le remplacement**, puisqu’il faut déconnecter puis reconnecter le circuit de liquide en garantissant à chaque fois son étanchéité. C’est envisageable sur quelques unités, mais le risque de fuite devient sérieux à l’échelle des 70 à 75 millions de modules optiques.

- **Le problème du cuivre demeure**, car les données parcourent toujours une liaison électrique entre la puce et le module. Le XPO accompagnera donc au mieux deux générations de produits, ce qui laisse peu de temps pour amortir les investissements.

## Conclusion

Ainsi, vous l’aurez compris, **la photonique devient indispensable à la poursuite du développement de l’IA**, car la puissance des puces ne suffit plus si les infrastructures ne permettent pas de faire circuler les données assez vite. En rapprochant progressivement la lumière des processeurs, c’est donc une transformation profonde des data centers qui se prépare.

Selon les estimations que l’on retrouve dans Baggr, voici le chiffre d’affaires attendu d’ici 2030 pour les valeurs que nous avons évoquées dans cette newsletter :

- Lumentum devrait voir son chiffre d’affaires passer de 3 milliards de dollars en 2026 à **plus de 20 milliards en 2030**.

- Coherent passerait de 7 à **plus de 28 milliards de dollars** sur la même période.

- Ciena passerait d’environ 6 milliards de dollars attendus en 2026 à **plus de 17 milliards en 2030**.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/c358c5d3-716a-4596-b470-55ac67514f1e/photonique-v2-i-ca-2030.png?t=1792688658)

Pour finir, nous avons volontairement simplifié un sujet extrêmement technique et laissé de côté de nombreuses technologies pour rendre cette transformation aussi accessible que possible.

Mais son déploiement soulève d’autres enjeux, notamment celui des **lasers qui produisent la lumière transportant les données**. Leur fabrication en quantité suffisante constitue un goulot d’étranglement et pourrait devenir l’une des grandes batailles industrielles de cette transition.

![](https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80,width=1920,height=3840/uploads/asset/file/9d170eba-d104-46db-999c-df777c5fabd5/image.png?t=1792683190)

*Une plaquette de phosphure d'indium de 6 pouces*
