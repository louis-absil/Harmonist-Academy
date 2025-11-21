# Harmonist Academy – Master Edition (Piano)

Harmonist Academy – Master Edition est une application web d’entraînement de l’oreille dédiée aux accords de 7ᵉ (qualité + renversement), pensée pour les étudiant·e·s en solfège, harmonie, et formation musicale… mais suffisamment ludique pour plaire aussi aux autodidactes.

L’objectif : reconnaître le type d’accord de 7ᵉ et son renversement, gagner de l’XP, monter de niveau, et gravir les rangs prestigieux allant de “Tourneur de pages enthousiaste” jusqu’à “Réincarnation de Bach”. 🎹

✨ Fonctionnalités principales

🎧 Entraînement aux accords de 7ᵉ

- Majeure 7 (Maj7)
- Mineure 7 (min7)
- Dominante 7 (7)
- Demi-diminuée (ø7)
- Diminuée (°7)
- Mineure majeure 7 (mMaj7)

🔁 Reconnaissance de renversements

- 7 – 65 – 43 – 2
- Gestion spéciale pour l’accord de 7ᵉ diminuée (sans renversement à choisir)

🧠 Deux modes de jeu

- Mode Zen : pas de limite de temps, idéal pour le travail concentré et la pédagogie en cours.
- Mode Chrono : 60 secondes, vies limitées, bonus de temps si réponse correcte – parfait pour se challenger.

🏅 Système de niveaux & rangs

- XP gagnée à chaque bonne réponse, avec bonus de série.
- Rang évolutif (géré en localStorage) :
  - Tourneur de pages enthousiaste → Auditeur curieux → Mélomane motivé … → Favori d’Euterpe → Réincarnation de Bach.

🛠 Personnalisation pédagogique

- Sélection des types d’accords à travailler.
- Sélection des renversements actifs.
- Option “Mode éclaté” (voicing ouvert) pour complexifier l’écoute (+50 % XP).

📊 Statistiques détaillées

- Précision globale.
- Statistiques par type d’accord et par renversement.
- Meilleur score en mode Chrono.

🔊 Audio & feedback

- Synthèse type piano électrique doux (Web Audio API).
- Réverbération intégrée pour un son agréable.
- Effets sonores légers pour : bonne réponse, erreur, montée de niveau.
- Petit visualiseur graphique et confettis lors des réussites.

⌨️ Raccourcis clavier

- Espace : écouter / réécouter.
- Entrée : valider / passer à la question suivante.
- H : indice (arpeggiation de l’accord).
- Chiffres (1–6) : choix du type d’accord (suivant les accords actifs).
- Lettres (A Z E R / Q W E R selon clavier) : choix du renversement.

🧱 Stack technique

- HTML / CSS / JavaScript vanilla (une seule page, aucun framework).
- Web Audio API pour la synthèse sonore.
- localStorage pour la sauvegarde :
  - niveau, XP, meilleur score
  - statistiques d’exercices
  - configuration des accords & renversements.

Interface responsive pensée pour :

- écran d’ordinateur
- tablette
- utilisation sur écran tactile (boutons larges, haptique sur mobile si disponible).

🚀 Installation & utilisation

- Clone le dépôt :
  
  git clone https://github.com/ton-compte/harmonist-academy.git
  cd harmonist-academy

- Ouvre simplement le fichier index.html dans ton navigateur :
  - soit en double-cliquant dessus,
  - soit via un petit serveur local (recommandé) :
    
    # exemple avec Python
    python -m http.server 8000
    # ensuite : http://localhost:8000 dans le navigateur

Clique sur “Écouter”, choisis :

- la qualité de l’accord (colonne de gauche),
- le renversement (colonne de droite),
puis Valider.

Surveille ton rang, ta série, ta précision et ton high score ! 🎼

🎯 Objectif pédagogique

L’application est pensée pour :

- les étudiant·e·s en solfège / FM / harmonie (conservatoires, HEM, écoles de musique),
- les profs souhaitant un outil rapide et ludique en cours,
- les musicien·ne·s qui veulent renforcer leur oreille harmonique sur les accords de 7ᵉ et leurs renversements.