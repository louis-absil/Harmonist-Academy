# 🎹 Harmonist Academy

> **Version actuelle :** v3.8.2 (Stable)
> **Statut :** En développement actif

**Harmonist Academy** est une application web d'entraînement auditif (Ear Training), conçue pour aider les musiciens à reconnaître instantanément les accords, les renversements et les voicings complexes.

Loin des exercices académiques austères, l'application utilise des mécaniques de RPG (XP, Niveaux, Maîtrises, Badges) pour rendre l'apprentissage addictif et gratifiant.

---

## ✨ Fonctionnalités Principales

### 🎧 Entraînement Auditif Avancé
- **Moteur Audio Réaliste :** Utilise des samples de piano de haute qualité (Salamander Piano) avec réverbération à convolution.
- **Système de "Salles" (Sets) :**
  - **🏛️ L'Académie (Classique) :** Triades, 7ème, Renversements classiques (État fondamental, 1er, 2ème, 3ème).
  - **🎷 Le Club (Jazz) :** Accords enrichis (6/9, 13, Alt, Sus7b9) et Voicings réalistes (Close, Drop 2, Shell, Rootless).
- **Feedback Visuel :** Clavier virtuel et effets visuels réactifs.

### 🎮 Gamification & Progression
- **Système d'XP et Niveaux :** Progressez du niveau 1 au niveau 20.
- **Série (Streak) & Combos :** Plus vous enchaînez les bonnes réponses, plus l'interface s'anime et le score grimpe.
- **Système de Maîtrise (Prestige) :**
  - Une fois le niveau 20 atteint, validez votre Maîtrise pour réinitialiser votre niveau mais gagner une Étoile (Or ⭐, Platine 💠, Cosmique 🟣).
  - Débloque de nouvelles "Salles" (Contenu Jazz, etc.).
- **Badges & Trophées :** Plus de 25 succès à débloquer ("The Duke", "Métronome", "Sniper"...).
- **Coach Virtuel :** Analyse vos erreurs en temps réel et vous donne des conseils théoriques ciblés.

### 🕹️ Modes de Jeu
L'application propose une courbe de difficulté progressive :
1.  **🧘 Mode Zen :** Pas de temps, pas de vies. Idéal pour apprendre.
2.  **🎧 Mode Inverse :** On entend un son, on doit trouver son nom (Quiz). *(Débloqué Niv 3)*
3.  **⚡ Mode Chrono :** 60 secondes pour faire le meilleur score. *(Débloqué Niv 8)*
4.  **🏃 Mode Sprint :** 10 secondes par question. La moindre erreur est fatale. *(Débloqué Niv 12)*

---

## 🚀 Installation & Utilisation

Harmonist Academy est une **Single Page Application (SPA)** construite en HTML/CSS/JS pur (Vanilla). Aucune installation complexe n'est requise.

### Prérequis
- Un navigateur web moderne (Chrome, Firefox, Safari, Edge).
- Connexion internet requise au premier lancement pour charger les samples audio (puis fonctionne en cache).

### Lancer le projet
1.  Clonez ce dépôt :
    ```bash
    git clone https://github.com/votre-username/harmonist-academy.git
    ```
2.  Ouvrez le fichier `index.html` directement dans votre navigateur.
    *   *Recommandé :* Utilisez une extension comme "Live Server" sur VS Code pour éviter les blocages CORS liés aux modules audio.

---

## 🎼 Contenu Musical

### Salle 1 : L'Académie (Niveau Standard)
Focalisée sur la reconnaissance fonctionnelle.
- **Accords :** Maj7, min7, Dom7, m7b5 (Ø), Dim7, minMaj7.
- **Variations :** État Fondamental, 1er Renversement (65), 2ème Renversement (43), 3ème Renversement (2).

### Salle 2 : Le Club (Maîtrise I)
Focalisée sur la couleur et la texture Jazz.
- **Accords :** Maj6, min6, Dom9, Sus7b9, Maj9, min9, Dom13, Alt (7#9b13), Maj7#11.
- **Voicings (Textures) :**
  - **Serré (Close) :** Toutes les notes dans une octave.
  - **Ouvert (Drop 2) :** Voicing aéré typique du piano jazz.
  - **Shell (Bebop) :** Tonique + Tierce + 7ème (Essentiel).
  - **Rootless (Bill Evans) :** Sans fondamentale, axé sur les extensions.

---

## 🛠️ Stack Technique

- **Core :** Vanilla JavaScript (ES6+).
- **Audio :** Web Audio API (Context, Gain, Oscillator, Convolver).
- **Style :** CSS3 (Variables, Flexbox, Grid, Animations).
- **Data :** LocalStorage pour la persistance des données (sauvegarde automatique).

---

## 🔮 Roadmap

- [x] **v3.0 :** Refonte UI & Moteur Audio.
- [x] **v3.5 :** Ajout des Badges & Coach.
- [x] **v3.8 :** Système de Maîtrise, Mode Jazz & Voicings.
- [ ] **v4.0 (Maîtrise II) :** Le Laboratoire (Accords Atonaux, Quartal, Quintal, Clusters).
- [ ] **v4.5 (Maîtrise III) :** Le Cosmos (Modes de Messiaen, Gammes par tons, Microtonalité).

---

## 📝 Crédits

Développé par **Louis Absil**.
Samples de piano par **Salamander Grand Piano**.

---

*Fait avec ❤️ et beaucoup de café.*
