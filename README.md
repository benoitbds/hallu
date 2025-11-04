# 🌀 Expérience Psychédélique Transcendantale

Une animation HTML/CSS/JavaScript immersive et hypnotique qui crée un voyage visuel à travers des motifs fractals, de la géométrie sacrée et des effets bioluminescents.

## 🎬 NOUVEAU : Version Cinématographique

**psychedelic-cinematic.html** - Rendu professionnel avec WebGL et shaders avancés

Une refonte complète utilisant des techniques de rendu cinématographique de niveau professionnel :
- **WebGL Raymarching** avec distance fields pour fractales 3D
- **Pipeline post-processing multicouche** (bloom HDR, chromatic aberration, vignette)
- **ACES Filmic Tonemapping** pour rendu cinématographique
- **Effets volumétriques** avec accumulation de lumière
- **4 scènes procédurales** : Tunnel fractal, Kaleidoscope, Morphing, Mandelbulb
- **Qualité GPU** avec shaders GLSL optimisés

## ✨ Caractéristiques

### Visuels
- **Motifs fractals organiques** évoluant continuellement
- **Palette bioluminescente** : cyan néon, violet profond, rose magenta, vert émeraude, bleu cobalt, orange incandescent
- **Profondeur 3D** avec système de particules multi-couches
- **Effets de glow et bloom** pour un rendu cinématographique
- **Géométrie sacrée** : Fleur de Vie, Spirale de Fibonacci, Mandalas évolutifs
- **Tunnel dimensionnel** créant une impression de voyage infini

### Animations
- Mouvements fluides et hypnotiques à 60fps
- Rotations et zooms progressifs pour une transe visuelle
- Pulsations synchronisées évoquant une respiration cosmique
- Transitions douces entre états visuels

### Interactivité
- **Mouvement de la souris** : influence les particules et la profondeur
- **Clic** : génère des ondes de choc lumineuses
- **Sons et mantras** : fréquence OM (136.1 Hz) et sons sacrés (528 Hz)

### Contrôles
- **Vitesse** : ajustez la vitesse de l'animation (0.1x à 3x)
- **Intensité** : contrôlez l'intensité des effets lumineux
- **Particules** : modifiez le nombre de particules (100 à 1000)
- **Son** : activez/désactivez l'audio
- **Mantra OM** : lancez le mantra primordial avec fréquence 136.1 Hz

## 🚀 Utilisation

### Version Cinématographique (Recommandée)

1. **Ouvrez le fichier** `psychedelic-cinematic.html` dans un navigateur moderne avec WebGL (Chrome, Firefox, Edge, Safari)

2. **Sélectionnez une scène** :
   - **Tunnel** : Voyage infini à travers un tunnel fractal
   - **Kaleidoscope** : Géométrie miroir hypnotique
   - **Morphing** : Formes qui se transforment organiquement
   - **Fractal** : Mandelbulb 3D avec raymarching

3. **Ajustez les effets** :
   - **Bloom** : Contrôlez l'intensité du glow HDR
   - **Aberration** : Effet de prisme chromatique
   - **Vitesse** : Modifiez la vitesse temporelle (0.1x - 3x)
   - **Intensité** : Amplifiez l'énergie lumineuse

4. **Interagissez** :
   - Déplacez la souris pour contrôler la caméra
   - Cliquez pour générer des impulsions quantiques

### Version Classique

1. **Ouvrez le fichier** `psychedelic-experience.html` dans un navigateur moderne (Chrome, Firefox, Edge, Safari)

2. **Activez le son** (optionnel) :
   - Cliquez sur "Activer Son"
   - Ensuite, cliquez sur "Mantra OM" pour démarrer l'expérience sonore

3. **Interagissez** :
   - Déplacez la souris pour influencer le flux énergétique
   - Cliquez n'importe où pour créer des ondes cosmiques
   - Ajustez les contrôles selon votre préférence

4. **Mode plein écran** (recommandé) :
   - Appuyez sur F11 pour le plein écran
   - Pour une expérience optimale, réduisez les distractions

## 🎨 Technologies

### Version Cinématographique (WebGL)
- **WebGL** avec shaders GLSL pour rendu GPU
- **Raymarching** pour géométrie procédurale 3D
- **Distance Fields** pour fractales et formes organiques
- **Pipeline post-processing** :
  - Extraction de zones lumineuses (threshold-based)
  - Gaussian blur séparable (horizontal + vertical)
  - HDR bloom avec multi-pass rendering
  - Chromatic aberration radiale
  - Vignette cinématographique
  - Film grain subtil
- **ACES Tonemapping** pour mappage tonal filmique
- **Volumetric lighting** avec accumulation de rayons
- **Framebuffers multiples** pour effets composés
- **Web Audio API** intégrée
- **60fps constant** grâce au GPU

### Version Classique (Canvas 2D)
- **Canvas 2D** pour les animations haute performance
- **Web Audio API** pour la génération de sons sacrés
- **Animations optimisées** à 60fps minimum
- **Responsive** : s'adapte à toutes les tailles d'écran

## 🧘 Ambiance

Cette expérience évoque :
- Un voyage intérieur méditatif
- La dissolution de l'ego
- L'union avec le cosmos
- Une esthétique organique et technologique
- Une dimension mystique et futuriste

## 🔧 Configuration technique

### Version Cinématographique - Détails des Shaders

**Scènes Raymarching** :
- **Tunnel Fractal** : Distance fields avec répétition spatiale et smooth min blending
- **Kaleidoscope** : Symétrie miroir à 6 axes avec rotation récursive
- **Morphing** : Interpolation fluide entre sphère, cube et tore
- **Mandelbulb** : Fractale 3D avec estimation de distance et power 8

**Effets de Lighting** :
- Calcul de normales par gradient
- Fresnel effect pour halos lumineux
- Ambient occlusion basée sur les itérations
- Éclairage volumétrique avec 20 samples par rayon

**Pipeline Post-Processing** :
1. Rendu scène principale (HDR framebuffer)
2. Extraction bloom (threshold 0.7)
3. Gaussian blur 2-pass (résolution divisée par 2)
4. Composite avec ACES tonemapping
5. Chromatic aberration radiale
6. Vignette + film grain
7. Gamma correction (2.2)

### Version Classique - Performance
- Optimisé pour 60fps
- Trail effect pour réduire la charge graphique
- Gestion dynamique du nombre de particules
- Context 2D avec `{ alpha: false }` pour meilleures performances

### Audio (Les deux versions)
- Fréquence OM : 136.1 Hz (fréquence du OM primordial)
- Fréquence de clic : 528 Hz (fréquence de transformation)
- Modulation LFO pour effet mystique
- Fade in/out progressif

## 🌟 Expérience recommandée

Pour une expérience optimale :
1. Utilisez un écran large en plein écran
2. Réduisez l'éclairage ambiant
3. Utilisez un casque audio pour l'immersion sonore
4. Commencez avec vitesse 1x et ajustez selon votre confort
5. Laissez-vous porter par les visuels sans résister

## 📝 Notes

### Prérequis Version Cinématographique
- Navigateur moderne avec **WebGL** activé
- Carte graphique compatible (GPU intégré suffisant)
- Chrome 56+, Firefox 51+, Safari 15+, Edge 79+
- Performances optimales sur desktop (mobile supporté mais peut chauffer)

### Prérequis Version Classique
- N'importe quel navigateur moderne
- Fonctionne sur mobile et desktop
- Plus léger en ressources

### Général
- L'expérience est entièrement côté client (aucune connexion requise)
- Fonctionne hors ligne après le premier chargement
- Le son nécessite une interaction utilisateur pour démarrer (politique des navigateurs)

## 🆚 Quelle version choisir ?

**Version Cinématographique** si vous voulez :
- Le meilleur rendu visuel possible
- Effets de post-processing professionnels
- Fractales 3D et géométrie procédurale
- Qualité de production cinématographique
- Utilisation desktop principalement

**Version Classique** si vous préférez :
- Compatibilité maximale
- Utilisation mobile fluide
- Approche plus légère
- Particules et géométrie sacrée 2D

## 🎭 Avertissement

Cette expérience contient des animations psychédéliques intenses. Elle n'est pas recommandée pour les personnes sensibles aux stimulations visuelles rapides ou souffrant d'épilepsie photosensible.

---

**✦ Bon voyage dans les dimensions intérieures ✦**
