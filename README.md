# Inventory System
Developed with Unreal Engine 4

**-- Le système d'inventaire en mode blueprints --**

- Slot based Inventaire.
- Stackable.
- Inventaire principal (sac à dos) + inventaires secondaires (onglets) + Equipement.
- Système d'équipement (UMG + Player preview).
- Système USE/DROP/CRAFT (items).
- Système de librairie (items Livres) avec système de classement/tri des entrées.
- Poids items et inventaire
- Système de messages (widget) intégré.

**Options :**
- Prévisualisation des objets en rotation.
- Hotbar (touches 1 à 9).
- Journal widget.
- Skill Tree widget.

**L'inventaire principal (sac à dos)** stocke en vrac les items au fur et à mesure que le joueur les trouve.

**Les inventaires secondaires (onglets)** classent les items selon leur catégorie :
- Armes
- Armures
- Minerais
- Livres
- Plantes
- Potions
- Consumables
- Quest items
- Upgrades
etc.,

L'onglet **Livres** contient :
- la liste des livres trouvés (scroll box),
- un descriptif du livre (Titre ; Auteur ; Langue ; Année ; Genre)
- un résumé,
- une image de l'auteur,
- le statut du livre : Lu ;  Traduit
- Un bouton pour classer selon la Langue, les Auteurs, le Genre, Année, Titre
Cliquer sur un livre de la liste ouvre la page descriptive.
Une icone après le titre dans la liste indique le statut Lu et/ou Traduit

L'onglet **Plantes** permet de crafter des potions et des remèdes (mélanger deux plantes = un remède ou potion).

L'onglet **Minerais** permet de crafter les minerais (Raffiner le minerais donne du métal).

L'onglet **Armes** contient les armes trouvées par le joueur (Possibilité d'Upgrader les armes avec des upgrades).

L'onglet **Armures** contient les armures trouvées par le joueur (Possibilité d'Upgrader les armures avec des upgrades).

L'onglet **consumables** contient les consumables.

L'onglet **Upgrades** contient les Upgrades.

L'onglet **Quest Items** contient les objets de quêtes et artefacts spéciaux et objets de quête.
