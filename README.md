# WIP (work in progress)

Les ressources rassemblées ici constituent une base de connaissances permettre aux équipes clientes de s'autoformer pour acquérir rapidement un maximum d'autonomie sur l'offre cloud native portée par le Ministère de l'Intérieur s'appuyant un environnement du Cloud souverain Pi (offre "Cloud Pi Native"). Dans une logique d’amélioration continue, vous pouvez proposer vos commentaires en:
- Faisant des pulls request sur le repository 
- Faisant des issues

# Que contient cette section?
**Une "valise" de ressources d'autoformation** pour accompagner la montée en compétences et embarquer"pas à pas"**. Elle est destinée aux personnes ou organisations souhaitant comprendre et/ou consommer l’offre [Cloud Pi Native](https://dnum-mi.github.io/) du MIOM pour réaliser une transformation de son socle de production vers le "cloud native".


# Pour quoi faire ?
- **Pour se former à titre individuel** sur les technologies cloud native en consultant des ressources d'autoformation disponibles à chaque étape (voir le périmètre correspondant à ses responsabilités dans la section "se former à titre individuel");
- **Pour embarquer une équipe projet/produit** sur l'offre Cloud Pi Native du MIOM en consultant, à chaque étape du parcours, le "mode d'emploi" et la documentation ainsi que les connaissances théoriques et pratiques nécessaires.

Le parcours comporte 5 étapes, de la prise de connaissance à l'utilisation en autonomie qui correspondent à des degrés de "maturité" croissant (i.e. type de questions que les utilisateurs se posent).

![alt_text](images/embarquement-formation.jpg)

<details>

<summary> Voir les hypothèses du parcours </summary>

- Respect de l'ordre chronologique : le niveau de maturité requis augmente au fur et à mesure des étapes d'embarquement, jusqu'à l'autonomie dans la gestion des évolutions en production;
- Acessibilité : les premières étapes (comprendre l'offre et préparer un projet) ne nécessitent aucune connaissance théorique ou pratique préalables;
- Reconnaissance des acquis : plutot que des formations par métiers, dont les intitulés ne correspondent pas toujours à la réalité des missions exercées sur le terrain, nous distingons de façon macroscopique, des périmètres de responsabilités.

</details>


# Quelle "maturité" requise pour quelle étape d'embarquement?

Le plan d'embarquement permet d'avancer étape par étape de la découverte à l'utilisation en autonomie: 
- Pour être guidés dans les questions et critères à valider avant de passer à l'étape suivante, consultez [la checklist](./checklist.md).
- Vous savoir à quel type d'accompagnement vous etes éligibles, débutez en consultant la [politique d'accompagnement](https://github.com/cloud-pi-native/embarquement-autoformation/blob/main/eligibilite.md).

| | | | | 
|-|-|-|-|
|**N° étape**|**Stade d'avancement du projet** |**Ressources et mode d'emploi de cloud Pi Native**|**Si éligible à un accompagnement**|
|1|Qualifier son besoin, analyser l'opportunité du Cloud Native|Consulter la [page de présentation l'offre](https://dnum-mi.github.io/) et le [support de sensibilisation aux enjeux](./sensibilisation.md)/ spécifier son besoin/ S'assurer du soutien de la démarche (sponsor)|[Décrire son besoin et prendre contact avec le programme Cloud Pi Native](https://www.demarches-simplifiees.fr/commencer/prequalification-cloud-pi-native)/**RDV de préqualification de votre besoin avec l'offre avec l'équipe Adoption** |
|2|Préparer son projet/produit en "cloud native"|Utiliser le [Cadre de cohérence Technique "Cloud Native"](https://github.com/cloud-pi-native/cct-cloud-native/blob/main/README.md) pour définir son plan projet/évaluer son degré de préparation|Completer  le [formulaire de demande d'accès à la console](https://www.demarches-simplifiees.fr/commencer/cloud-pi-native)/ **RDV de qualification technique avec un tech lead du programme**|
|3|Lancer un MVP dans un environnement de développement "Cloud native"|Consulter la [documentation de l'offre](https://github.com/cloud-pi-native/documentation)/ s'exercer avec les tutoriels/ provisionner et déployer son environnement de développement "cloud native"|Préparation de l'architecture projet/ **RDV de lancement avec la Service Team**|
|4|Passer son projet/produit en production, construire dans le respect de normes "Cloud Native"|Consulter la [documentation de l'offre](https://github.com/cloud-pi-native/documentation)/ provisionner et déployer son environnement de production "Cloud native"/ prise en main des outils d'observabilité|S'intégrer aux processus nominaux (demande d'hébergement, homologation, certification, …)/ **Suivi technique avec la service team**|
|5|Atteindre les meilleurs standards du "Cloud Native", évolution continue|(à venir)|(à venir)|


# Valise d'autoformation
Ces ressources sont non-spécifiques à l’offre, disponibles en appui pour comprendre et utiliser Cloud Pi Native. Elles sotn distinguées selon la nature des responsabilités exercées (voir plus bas) et la "maturité" requise par l'étape d'embarquement ("maturité" = type de questions qui se posent aux utilisateurs). 

## Nature de responsabilités
Dans sa version actuelle, le plan de formation distingue 3 types d'apprenants en fonction de leur domaine de responsabilités: 

1- **"Réalisation technique"**: équipes techniques responsables de la prise en main de l'offre pour construire, opérer et gérer des produits numériques, tout au long de leur cycle de vie. Directement, pour développer et opérer des produits (équipe DevOps) ou indirectement, pour mettre en place et assurer la fiabilité des systèmes de production nécessaires (SRE, ingéniérie de plateforme) dans un environnement "cloud native".

2- **"Pilotage MOE"**: personnes responsables de la structuration et de la mobilisation d'une équipe projet/produit (compétences, roles, organisation, choix technologiques, ..) son organisation et son suivi (contractuel, budgetaire, UO, livrables, ...), pour saisir les opportunités du paradigme "cloud native".

3- **"Gouvernance/décision"**: personnes responsables de l'orientation de projets numériques vers une offre  de service donnée pour comprendre les spécificités du "nouveau monde logiciel" et les opportunités du paradigme "cloud native". 

<details>
<summary> Voir les exemples de profils </summary>

- **Réalisation technique**: responsables de la qualité des produits/SI. Selon la taille et de l'organisation, ce périmètre peut recouvrir des personnes responsables de la fiabilité des services & des systèmes (plateformes de services, pipelines de livraison DevSecOps, services d’hébergement, environnements, réseaux, etc.). Exemples: développeurs, opérateurs, DevOps, SRE, architectes solution, etc.
- **Pilotage MOE**: responsables de l'intégrité des équipes assurant le développement ou les opérations sur les produits et de l'intégrité des projets (cadrage, bonne utilisation et suivi des ressources, orientations techniques...). Exemples:  pilotage/chefferie de projets/programmes, responsables d'unités de conception, de bureaux d'étude, MOE, etc.
- **Gouvernance/décisionnaire**: responsables de la pertinence des décisions stratégiques ce qui recouvre, plus largement, les personnes chargées de les conseiller. Exemples: pilotage et gouvernance des organisations, directions générales ou métiers, stratégie d'achat, stratégie RH, etc.
</details>

## Ressources d'autoformation


| | | | | |
|-|-|-|-|-|
|**N° étape**|**Maturité de l'équipe**|**Ressources d'autoformation Périmètre décision/stratégie**|**Ressources d'autoformation Périmètre pilotage MOE**|**Ressources d'autoformation Périmètre  réalisation technique (produit ou système de production)**|
|1|[Quels sont les enjeux/risques des mutations du numérique et en quoi suis-je concerné?](./sensibilisation.md)  |Comprendre les enjeux du "nouveau monde logiciel" pour la transformation du numérique public|Opportunités du "nouveau monde numérique" : technologies "cloud native", méthodologies, approches et mode d'organisation, culture...|Opportunité d'un socle de production à l'état de l'art "Cloud Native" pour le développement et la gestion de produits numériques|
|2|[Comment comprendre les concepts derrière le "cloud native" et comment m'en saisir à mon niveau?](./formation_step2.md)|Comprendre comment les grands acteurs du numériques/grandes organisations ont tirés parti des nouvelles opportunités|Comprendre les technologies portées par le cloud native (orchestration et conteneurisation)|Comprendre les différents services d'un socle de production Cloud Native à chaque étape du cycle de vie d'un produit|
|3|[Comment me préparer, à mon niveau de responsabilité, pour mettre en place une offre cloud native?](./formation_step3.md)|Mesurer l'impact de ces nouvelles opportunités sur les organisations produisant du numérique (stratégie, financement, gouvernance budgétaire, programmation, ...) |Organiser et préparer une équipe produit pour mettre en place et utiliser des outils "cloud native" (contractualisation, provisionnement, compétences, ...) |Réaliser un premier "hello world", puis construire un MVP avec un socle de production Cloud Native|
|4|[Comment réaliser le potentiel du cloud native, à quoi m'engage le respect des différentes normes (techniques, organisationelles, etc.)?](./formation_step4.md) |Assurer la qualité et la sécurité au niveau des organisations dans le "nouveau monde logiciel" (zero-trust)|S'organiser pour concevoir et gérer des produits de A à Z dans un cadre Cloud Native (sécurité k8s)|Déployer en production, puis mettre en service un produit cloud native|
|5|[Comment garantir, en évolution permanente, l'intégration/pérénnité des bonnes pratiques et la maitrise des standards?](./formation_step5.md) |Manager un patrimoine numérique pour rester autonome et performant sur la durée (anti patterns, organisation en mode produit et cloud-agile)|Tirer le plein potentiel et contribuer aux technologies du CNCF Landscape (dont charts helms/operators)|Assurer la disponibilité et la continuité, MCO/MCS, garder des options ouvertes sur les transitions futures|





