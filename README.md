# Interface et traduction françaises corrigées

Ce mod s'adresse avant tout aux joueurs utilisant la version française de Crusader Kings III. Il corrige diverses erreurs et incohérences de localisation, ainsi que quelques problèmes d'affichage dans l'interface.

Lorsque c'est possible, les corrections sont appliquées aux textes plutôt qu'aux éléments d'interface, afin de conserver une compatibilité maximale avec les autres mods.

## Interface

- Couronnements : le texte d'intention "Impressionner les personnes présentes" ne dépasse plus du bouton.
- Intrigue : taille des colonnes et des éléments de la liste des agents potentiels corrigée pour se caler sur l'UI des fantoches.
- Paramètres des messages : l'interface ne dépasse plus de la fenêtre.
- Personnage : les emblèmes des pays mercenaires n'affichent plus une décoration dans la partie diplomatie qui décale tout l'affichage.
- Personnage : les emblèmes de la diplomatie ne sortent plus de leur cadre si les personnages ont plus de 7 revendications
- Religions : le texte d'attitude envers les rites est affiché en entier.

![Paramètres des messages avant et après correction](screenshots/screenshot1.jpg)

![Rites religieux avant et après correction](screenshots/screenshot2.jpg)

![Emblèmes des pays mercenaires avant et après correction](screenshots/screenshot3.jpg)

![Liste des agents potentiels avant et après correction](screenshots/screenshot4.jpg)

![Intentions de couronnement avant et après correction](screenshots/screenshot5.jpg)

## Articles des titres

Correction des articles devant les titres mal accordés dans les évènements et les interfaces.

Les titres concernés sont :

- Tous les titres ecclésiastiques ("L'Prince-Archevêque", "L'Cardinal", "Le Archevêque", "du Abbé", etc)
- Les titres de régents japonais ("à l'Shogun", "l'Kampaku", etc)
- Les titres de conseillers chinois ("L'Ministre", "de l'Grand Chancelier", etc), ainsi que leurs vassaux
- Les dirigeants coréens (Jipjeong)
- Les Chanoinesses sont appelées ainsi et non plus "Princesses"

## Localisation

- Artéfacts : retrait des termes "Pin" / "Badge" résiduels de la localisation anglaise en fin de nom pour les insignes de pèlerin.
- Collège des cardinaux : les noms des principes ont bien tous une majuscule.
- Collège des cardinaux : correction du nom du rite dominant affiché à la place du rite du personnage.
- Correction de "au Papauté" en "au Pape" ou "à la Papauté" selon les cas, dans l'interface et les décisions.
- Intrigue : correction de l'infobulle du Retrait de la vie publique qui affichait un "')]".
- Inventaire : le nombre de revendications n'empiète plus sur le libellé du bouton.
- Personnage : le nom du rite a bien une majuscule.
- Religions : le texte d'attitude envers les rites est correctement mis en forme et n'est plus tronqué.

## Événements

- `coronation_events.0100` "Un serment historique" : correction des libellés tronqués des serments "Subvenir aux besoins des pauvres", "Subvenir aux besoins des fidèles" et "Devenir le meilleur chasseur".
- `ecumenical_council_events.0010` "Notre position sur XXX" : correction de la clé de relation manquante ("m <nom>" devient "mon vassal <nom>" ou "ma vassale <nom>").
- `pam_decision_events.0006.desc.secret_sin` "Derniers sacrements" : reformulation d'une phrase maladroite pour la confession d'une liaison
- `pam_secular_faith_events.0014` "Jugement prophétique" : correction de l'affichage de l'option 1, dont tout le texte est désormais visible.
- `pam_the_christian_church.*` : correction de toutes les occurrences de "l'Chrétienté" en "la Chrétienté".

## Divers

- Fix préfixe `Need` anglais devant les warnings de conditions
