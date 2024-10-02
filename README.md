# CMP_TABLEFIX

Composant WebDev pour corriger les Tables WebDev avec Rupture.

## Bug corrigé par ce composant

Les Tables WebDev avec Rupture ont un bug au niveau du scroll qui fait que les dernières lignes ne sont pas affichés et restent invisibles.

Ce composant permet de fixer ce bug, en attendant que PC Soft déploie un correctif officiel.

## Installation

Télécharger le fichier ZIP de la version la plus récente dans ce dépôt Git.
- Le suffix TXT contient le composant en format texte
- Sans le suffix contient le composant en format binaire

Dézipper le contenu dans le dossier de votre projet et importer le composant dans WebDev.

## Utilisation

L'importation seul du composant ne suffit pas.

Pour appliquer le fix sur vos tables, il faut :

- Ajouter l'évènement "Initialisation de TABLE_Exemple (Navigateur)" à votre table
- Ajouter le code `CMPTF_FixTableRupture(MoiMême..Alias)` dans cet évènement.
- C'est tout ! Cette table possède maintenant le fix !
