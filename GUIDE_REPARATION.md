📘 Manuel de Service Expert : Ibiza AMP300

⚠️ DANGER : HAUTE TENSION
L'ouverture de l'appareil expose à des tensions alternatives (230V) et continues ($\pm$45V) pouvant entraîner des chocs électriques mortels.
Toute intervention doit se faire hors tension. Déchargez les condensateurs de filtrage via une résistance de 1k$\Omega$/5W si nécessaire.

I. Anatomie du Signal

Le cheminement du son dans l'AMP300 suit cet ordre logique. Si le son coupe, vérifiez chaque étage :

Entrée : Connecteurs RCA ou Jack 6.35 à l'arrière.

Pré-amplification : Traitement du gain (potentiomètres de façade).

Étage Driver : Petits transistors (souvent A940/C2073) qui "pilotent" les gros.

Étage de Puissance : Transistors finaux (2SC5200 / 2SA1943) montés sur le radiateur.

Protection : Relais de sortie (clic au démarrage) qui connecte les HP.

II. Les Points Faibles Connus

Soudures sèches : Les vibrations du transformateur craquellent les soudures des borniers et des gros condensateurs. Refaites les soudures douteuses.

Pâte thermique : Souvent sèche ou mal appliquée d'usine, causant des surchauffes localisées sur les transistors.

Potentiomètres : Composants sujets à l'oxydation (grésillements). Un coup de spray contact suffit souvent.

III. Protocole de Mesures

Zone de test

Point de contrôle

Valeur attendue

Alimentation

Sortie du Pont de Diodes

$\pm$ 35V à $\pm$ 45V DC

Filtrage

Bornes des gros condensateurs

Tension stable (pas de chute)

Étage final

Jonction C-E des transistors

Résistance infini (OL) hors tension

Sortie HP

Bornier (sans charge)

DC Offset < 50mV

Masse

Châssis $\rightarrow$ Masse RCA

Continuité (0 $\Omega$)

IV. La Technique de la "Lampe de Série"

Utilisée après avoir remplacé des composants pour éviter de les griller à nouveau au premier allumage.

Fabriquez une rallonge électrique avec une ampoule à incandescence (60W/100W) connectée en série sur la phase.

Branchez l'ampli sur cette rallonge.

Allumez l'ampli :

L'ampoule s'allume fort puis s'éteint (ou rougeoie faiblement) : ✅ L'ampli est sain, le courant de repos est stable.

L'ampoule reste allumée à fond : ❌ Court-circuit franc ! Éteignez tout. L'ampoule a absorbé le courant et sauvé vos composants neufs.

Document généré par AudioTech ToolKit.
