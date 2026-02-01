🧰 AudioTech ToolKit (SOS-INFO-LUDO)

Une boîte à outils numérique portable pour le diagnostic et la réparation d'amplificateurs audio (spécialisé Ibiza AMP300).

Ce projet est une application web autonome (un seul fichier HTML) conçue pour aider les techniciens et amateurs à réparer du matériel de sonorisation sans danger.

🔗 ACCÈS À L'OUTIL

[Lien ICI](https://lerapeurdu62280-debug.github.io/AudioTech_ToolKit)

Lien alternatif vers le guide : ([GUIDE_REPARATION](https://github.com/lerapeurdu62280-debug/SOS-INFO-LUDO/blob/main/GUIDE_REPARATION.md))

🚀 Fonctionnalités Actuelles

L'application contient 7 modules principaux accessibles via des onglets :

1. 📝 Cahier d'Atelier (Notes)

Sauvegarde automatique : Vos notes sont enregistrées localement dans le navigateur.

Permet de noter les mesures (V+, V-, Offset) pendant la réparation sans les perdre si vous fermez la page.

Modèle pré-rempli pour le diagnostic standard.

2. ⚡ Calculateur Loi d'Ohm

Calcul instantané de la Tension, Courant, Résistance ou Puissance.

Idéal pour vérifier la puissance nécessaire d'une résistance de remplacement.

3. 💡 Calculateur LED (Nouveau)

Calcule la résistance de protection nécessaire pour vos LEDs témoins en façade.

Indique la puissance dissipée pour choisir la bonne résistance (1/4W, 1/2W, etc.).

4. 🌊 Calculateur de Filtres

Visualisation graphique de la courbe de réponse en fréquence (-3dB).

Indispensable pour le dépannage des étages de préamplification.

5. 🖍️ Outils Composants

Code Couleurs Résistances : Sélecteur interactif pour lire les valeurs sans tableau.

Brochage Transistors : Schéma visuel des 2SC5200 / 2SA1943 (communs sur les amplis Ibiza).

Convertisseur de Capacités : Aide-mémoire rapide (ex: 104 = 100nF).

6. 🛡️ Sécurité & Condensateurs

Calculateur de temps de décharge pour les gros condensateurs de filtrage.

Prévient les risques d'électrocution liés à l'énergie résiduelle dans l'ampli.

7. 🔊 Générateur de Signal

Génère des fréquences pures (Sinus, Carré) de 20Hz à 2000Hz.

Permet de tester le chemin du signal audio une fois l'ampli réparé.

🛠️ Installation et Utilisation

En ligne (Recommandé)

Cliquez simplement sur le lien en haut de cette page. Aucune installation n'est requise, cela fonctionne sur PC, Mac et Mobile.

Hors ligne (Local)

Téléchargez le fichier index.html.

Ouvrez-le avec n'importe quel navigateur web (Chrome, Edge, Firefox).

L'outil fonctionne immédiatement, même sans connexion internet.

🗺️ Roadmap

Voici les fonctionnalités prévues ou terminées :

[x] Ajout d'un calculateur pour résistances de LED.

[x] Guide de réparation consultable (https://github.com/lerapeurdu62280-debug/SOS-INFO-LUDO/blob/main/GUIDE_REPARATION.md).

[ ] Base de données des pannes courantes (Wiki).

[ ] Mode sombre/clair manuel.

🤝 Contribuer

Les contributions sont les bienvenues !

Forkez le projet.

Créez votre branche (git checkout -b feature/AmazingFeature).

Committez vos changements (git commit -m 'Add some AmazingFeature').

Pushez vers la branche (git push origin feature/AmazingFeature).

Ouvrez une Pull Request.

📄 Licence

Distribué sous la licence MIT. Voir LICENSE pour plus d'informations.

Projet développé pour l'assistance au dépannage électronique.
