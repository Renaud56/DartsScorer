# Dart Master

Application web de comptage et de suivi de parties de fléchettes, conçue pour être utilisée sur téléphone comme sur ordinateur. L’interface est en français et s’adapte aux écrans mobiles. (100% vibe codée)

## Captures d’écran

Captures mobiles réalisées avec des données de démonstration.

<details>
<summary>Afficher les captures</summary>

### Accueil et configuration

![Accueil et configuration d’une partie](screenshots/accueil.png)

### Partie X01

![Saisie d’une partie X01 sur mobile](screenshots/partie-x01.png)

### Statistiques des joueurs

![Statistiques X01 et Cricket séparées par joueur](screenshots/statistiques-joueurs.png)

</details>

## Fonctionnalités

- **X01** : parties en 301, 501 ou 701, avec option de sortie en double.
- **Cricket** : modes Standard et Inversé, avec saisie rapide ou détail des fléchettes.
- **Joueurs et manches** : de 1 à 4 joueurs, gestion des joueurs, parties amicales ou compétitives, formats en une manche ou en BO3, BO5 et BO7.
- **Suivi de partie** : scores, tours et manches, multiplicateurs simple/double/triple, annulation de la dernière action et reprise d’une partie sauvegardée.
- **Historique** : résultats consultables par mode, avec analyse de partie et cible pour revoir les fléchettes.
- **Statistiques par joueur et par mode** : moyenne PPD et meilleures performances en X01; MPR et marks en Cricket; série actuelle et meilleure série de victoires calculées séparément pour chaque mode.
- **Graphiques d’évolution** : PPD en X01 et MPR en Cricket, chacun accompagné de son bilan victoires-défaites.
- **Sauvegarde** : export et import de l’historique au format JSON.
- **Navigation mobile** : le bouton « précédent » ferme d’abord l’écran ouvert et permet de revenir au menu sans quitter la page.

## Utilisation

Aucune compilation ni installation de dépendances n’est nécessaire. Ouvrir `index.html` dans un navigateur récent. Pour y accéder depuis Android, la page peut être publiée sur un hébergement statique ou servie sur le réseau local.

Tailwind CSS, Chart.js, Font Awesome et la police Playfair Display sont chargés depuis des CDN; une connexion Internet est nécessaire pour leur chargement.

Les réglages, joueurs et parties sont stockés dans le `localStorage` du navigateur. Ils ne sont pas synchronisés entre appareils. Utiliser **Exporter** et **Importer** pour transférer une sauvegarde, et en conserver une copie avant d’effacer les données du navigateur.