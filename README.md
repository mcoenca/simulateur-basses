# Simulateur de basses

Outil pédagogique en HTML/JS pur pour visualiser les interférences entre caissons de basses identiques, façon EASE Focus mais simplifié.

## Utilisation

Ouvrir `index.html` dans un navigateur (aucune dépendance, aucun serveur requis). Compatible desktop et mobile (tactile).

## Fonctionnalités

- Carte de niveau relatif en dB par superposition des ondes de chaque source (atténuation en 1/r)
- 1 à 8 caissons déplaçables à la souris ou au doigt
- Réglages par caisson : délai (ms), phase (°), puissance (W, réf. 500 W RMS), filtre passe-bas (fc + pente 12/24/48 dB/oct, type Butterworth avec déphasage), inversion de polarité, mute
- Fréquence de 25 à 160 Hz avec repères d'écoute (ressenti corps, vibration, kick torse, haut sub) et couvertures typiques 18" / 15"
- Mode Play : balayage automatique de toute la plage pour juger une géométrie sur l'ensemble du spectre
- Grille en mètres paramétrable, graduée tous les 5 m avec lignes fines au mètre
- Position précise : x/y éditables au clavier, suivi en direct pendant le glisser
- Sauvegarde et rappel de configurations complètes dans le navigateur (localStorage)
- Configurations types : 2 côte à côte, ligne, arc électronique, end-fire, cardioïde

## Limites

Simulation 2D à une seule fréquence, sources omnidirectionnelles parfaites, sans réflexions de salle ni directivité de boîte. Outil de compréhension, pas de calage professionnel.
