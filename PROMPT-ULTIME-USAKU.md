# PROMPT ULTIME — Site e-commerce U SAKU

> **Mode d'emploi** : Copiez-collez ce prompt tel quel dans Claude, ChatGPT ou tout autre IA.
> Remplacez les éléments entre [CROCHETS] par vos infos personnelles.
> Vous pouvez aussi l'utiliser section par section pour construire le site progressivement.

---

## LE PROMPT

```
Tu es un designer web expert en e-commerce de luxe artisanal et en développement frontend (HTML, CSS, JavaScript, React). Tu vas créer un site web complet pour ma marque.

═══════════════════════════════════════════
1. IDENTITÉ DE LA MARQUE
═══════════════════════════════════════════

• Nom : U SAKU (signifie "le sac" en langue corse)
• Activité : Création et vente de sacs au crochet fait main
• Localisation : Corse, France
• Créatrice : [TON PRÉNOM] — artisane passionnée, chaque pièce est crochetée à la main avec amour en Corse
• Philosophie : Pièces uniques, personnalisables sur demande, artisanat authentique corse
• Gamme de prix : 80€ à 150€
• Catalogue : 10+ modèles de sacs au crochet
• Clientèle cible double :
  - Femmes 30-55 ans CSP+ cherchant un accessoire unique et artisanal
  - Touristes et amoureux de la Corse voulant ramener une pièce authentique de l'île
• Instagram : @usaku_17

═══════════════════════════════════════════
2. DIRECTION ARTISTIQUE — LUXE + TERROIR CORSE
═══════════════════════════════════════════

Le site doit fusionner deux univers :
— Le LUXE ÉPURÉ : typographies élégantes, espaces généreux, animations fluides, mise en page éditoriale haut de gamme
— Le TERROIR CORSE : couleurs de la terre, du maquis et de la mer, textures naturelles, esprit méditerranéen chaleureux

### Palette de couleurs (OBLIGATOIRE — respecter cette harmonie)

| Nom             | Hex       | Usage                              |
|-----------------|-----------|-------------------------------------|
| Maquis          | #4A6741   | Couleur principale, headers, accents|
| Maquis profond  | #2D3E28   | Fonds sombres, footer, sections     |
| Immortelle (or) | #C8A84E   | Accents luxe, boutons CTA, prix     |
| Immortelle clair| #E8D9A0   | Hover, highlights subtils           |
| Terre de Corse  | #8B6F47   | Textes secondaires, bordures        |
| Terre claire    | #C4A882   | Fonds alternatifs, cartes produits  |
| Mer tyrrhénienne| #3B6B8A   | Accents secondaires, liens          |
| Sable           | #F5EDE0   | Fonds de sections                   |
| Crème           | #FAF7F2   | Fond principal du site              |
| Encre           | #1C1A17   | Texte principal                     |
| Granit          | #7A7267   | Texte secondaire, légendes          |

### Typographies

- Titres : Cormorant Garamond (serif élégant, esprit éditorial luxe)
- Corps : DM Sans (sans-serif moderne, lisibilité parfaite)
- Accent/logo : Lettres espacées, majuscules fines pour le nom U SAKU

### Ambiance visuelle

- Photos produits sur fonds naturels : pierres corses, bois flotté, maquis, draps de lin
- Intégrer des photos de paysages corses en arrière-plan ou en sections (calanques, maquis, villages perchés, mer turquoise)
- Textures subtiles rappelant le crochet : trames, motifs entrelacés en SVG très légers
- Effet "galerie d'art" pour la présentation des sacs

═══════════════════════════════════════════
3. STRUCTURE DU SITE — SECTIONS OBLIGATOIRES
═══════════════════════════════════════════

### SECTION 1 — NAVIGATION (sticky, minimaliste)
- Logo "U SAKU" en haut à gauche (typographie Cormorant, lettres espacées, le U légèrement accentué en couleur Immortelle)
- Liens : Collection · Notre histoire · Personnalisation · Contact
- Icône panier en haut à droite avec compteur
- La nav devient semi-transparente au scroll avec un effet blur

### SECTION 2 — HERO SLIDER (section phare du site)
C'est la section la plus importante. Elle doit fonctionner comme un carrousel Instagram premium :

- SLIDER PLEIN ÉCRAN avec défilement horizontal fluide
- Chaque slide = 1 sac avec :
  • À gauche : grande photo du sac (60% de la largeur)
  • À droite : nom du sac, description poétique courte, prix, bouton "Découvrir"
- TRANSITIONS entre slides :
  • Animation slide (glissement horizontal) avec easing cubic-bezier doux
  • Durée : 0.8s à 1s
  • La couleur d'accent de chaque slide CHANGE pour correspondre au sac affiché (ex: slide 1 = tons maquis vert, slide 2 = tons mer bleu, slide 3 = tons terre ocre, slide 4 = tons immortelle doré)
  • La transition de couleur doit être progressive et harmonieuse, pas brutale
- Navigation : flèches discrètes + barre de progression/dots en bas
- Auto-play optionnel (pause au hover)
- Minimum 4 slides pour les 4 sacs phares

Exemple de slides :
1. "Fiore di Machja" — Sac crochet inspiré des fleurs du maquis (tons verts)
2. "Onda Turchina" — Sac crochet vagues méditerranéennes (tons bleus)
3. "Petra di Bavella" — Sac crochet motifs géométriques montagne (tons terre)
4. "Stella d'Oru" — Sac crochet fil doré, pièce signature (tons or)
[Remplace ces noms par tes vrais noms de modèles]

### SECTION 3 — COLLECTION / BOUTIQUE
- Grille de produits (3 colonnes desktop, 2 mobile, 1 très petit écran)
- Chaque carte produit :
  • Photo du sac avec effet hover (léger zoom + overlay avec bouton "Voir")
  • Nom du modèle (Cormorant Garamond)
  • Prix en couleur Immortelle
  • Petit badge si personnalisable ("Sur mesure" ou "Pièce unique")
- Filtres discrets en haut : Tous · Cabas · Bandoulière · Pochettes · Sur mesure
- Minimum 10 emplacements produits
- Animation d'apparition au scroll (fade-in staggeré)

### SECTION 4 — NOTRE HISTOIRE (storytelling émotionnel)
Layout éditorial en deux colonnes :
- Côté gauche : grande photo (la créatrice en train de crocheter, ou paysage corse)
- Côté droit : texte narratif

Le texte doit raconter :
- L'amour pour la Corse et ses traditions
- La passion du crochet fait main
- Le lien entre chaque sac et l'île (matières, couleurs inspirées du maquis, de la mer, des montagnes)
- Le fait que chaque pièce est unique, crochetée avec amour
- La possibilité de personnalisation

Inclure une citation mise en avant dans un encadré élégant :
"Chaque point de crochet porte en lui un peu de l'âme de la Corse."
— [TON PRÉNOM], créatrice de U SAKU

### SECTION 5 — LA CORSE, NOTRE INSPIRATION (section immersive)
Bande horizontale avec 3 cartes immersives côte à côte :
1. LE MAQUIS — fond vert maquis, texte : "Les couleurs et les parfums du maquis corse — immortelle, myrte, ciste — infusent chaque création"
2. LA MER — fond bleu profond, texte : "Le bleu de la Méditerranée et les calanques sculptées par le temps inspirent nos formes et nos textures"
3. LA MONTAGNE — fond terre/ocre, texte : "Le granit de Bavella, les châtaigniers centenaires et les villages perchés nous enseignent la force et l'authenticité"

Chaque carte a un petit motif SVG décoratif en filigrane (vagues, feuilles, pierres stylisées).

### SECTION 6 — PERSONNALISATION (argument de vente clé)
Section avec un fond sable/beige :
- Titre : "Votre sac, votre histoire"
- Sous-titre : "Chaque sac U SAKU peut être personnalisé selon vos envies : couleurs, taille, détails. Contactez-moi pour créer la pièce qui vous ressemble."
- Bouton CTA : "Demander une création sur mesure" (couleur Immortelle)
- 3 icônes/étapes simples :
  1. "Choisissez" — couleurs et modèle
  2. "Je crochète" — fabrication à la main en Corse
  3. "Recevez" — votre pièce unique livrée chez vous

### SECTION 7 — NEWSLETTER + FOOTER
Newsletter :
- Fond Maquis profond (#2D3E28)
- "Recevez les nouvelles de l'atelier" + champ email + bouton doré

Footer :
- Logo U SAKU
- Colonnes : Collection · À propos · Contact · Suivez-nous
- Lien Instagram @usaku_17
- Mention "Fait main en Corse avec ❤️"
- "© 2026 U SAKU — Tous droits réservés"

═══════════════════════════════════════════
4. COMPORTEMENT & ANIMATIONS
═══════════════════════════════════════════

- Toutes les sections apparaissent avec un fade-in au scroll (Intersection Observer)
- Le slider hero est le point focal : transitions fluides, changement de couleur progressif entre slides
- Hover sur les cartes produits : zoom photo 105% + léger overlay
- Boutons : transition de fond au hover (transparent → rempli)
- Navigation sticky avec changement de style au scroll (fond transparent → fond crème avec ombre légère)
- Curseur personnalisé optionnel (petit cercle fin)
- Le site doit être 100% responsive (mobile-first)
- Performance : lazy loading des images, animations CSS plutôt que JS quand possible

═══════════════════════════════════════════
5. TONS & COPYWRITING
═══════════════════════════════════════════

Le ton de tous les textes doit être :
- Poétique mais pas prétentieux
- Chaleureux et personnel (on sent la créatrice derrière)
- Mélange de français et de petites touches de langue corse pour les noms de produits
- Évocateur des sens : textures, parfums du maquis, lumière méditerranéenne
- Luxueux sans être inaccessible ("luxe artisanal", pas "luxe parisien")

Exemples de formulations :
- "Née du maquis, crochetée à la main" (tagline)
- "Chaque sac raconte un bout de Corse"
- "L'art du crochet, l'âme de l'île"

═══════════════════════════════════════════
6. CONTRAINTES TECHNIQUES
═══════════════════════════════════════════

- Code en HTML/CSS/JS pur OU en React (JSX) selon ta préférence
- Utiliser Google Fonts : Cormorant Garamond + DM Sans
- Les images produits seront remplacées par mes propres photos → utiliser des placeholders élégants (rectangles avec le nom du sac et un motif crochet SVG)
- Le slider doit fonctionner au touch/swipe sur mobile
- Prévoir des emplacements clairs pour mes photos avec des dimensions recommandées :
  • Photos produits : 800x1000px (portrait 4:5)
  • Photos hero slider : 1200x800px (paysage)
  • Photo "Notre histoire" : 600x800px
- Ajouter des commentaires dans le code pour que je puisse facilement remplacer les placeholders par mes vraies photos

═══════════════════════════════════════════
7. CE QUE JE NE VEUX PAS
═══════════════════════════════════════════

- Pas de design générique type "template Shopify basique"
- Pas de couleurs criardes ou néon
- Pas de polices génériques (Inter, Arial, Roboto)
- Pas de stock photos de sacs qui ne sont pas les miens
- Pas de pop-up agressif
- Pas de texte en anglais (tout en français, noms des sacs en corse)
- Pas d'animation excessive qui ralentit le site
- Pas de fond blanc pur (#FFFFFF) — utiliser crème (#FAF7F2) ou sable (#F5EDE0)

═══════════════════════════════════════════
8. LIVRABLES ATTENDUS
═══════════════════════════════════════════

Crée le site complet avec :
1. Le HTML/CSS/JS (ou React) fonctionnel
2. Le slider hero avec 4 slides et transitions de couleur
3. Toutes les sections décrites ci-dessus
4. Design responsive (mobile + desktop)
5. Placeholders numérotés pour mes photos avec commentaires explicatifs
6. Le code commenté pour faciliter les modifications

Commence par le slider hero (c'est le plus important), puis construis le reste du site autour.
```

---

## VARIANTES DU PROMPT

### Version courte (pour une demande rapide) :

```
Crée un site e-commerce pour "U SAKU", marque de sacs au crochet fait main en Corse.
Style : luxe artisanal + terroir corse.
Palette : vert maquis (#4A6741), or immortelle (#C8A84E), terre (#8B6F47), bleu mer (#3B6B8A), fond crème (#FAF7F2).
Typos : Cormorant Garamond (titres) + DM Sans (corps).
Sections : slider hero avec transition de couleur entre sacs, grille boutique 10+ produits, histoire de la créatrice, section culture corse, personnalisation sur mesure, newsletter, footer.
Le slider doit glisser horizontalement d'un sac à l'autre avec un changement progressif de couleur d'ambiance à chaque slide. Prix : 80-150€. Responsive, animations au scroll, tout en français avec noms corses.
```

### Prompt spécifique pour le SLIDER uniquement :

```
Crée un slider/carrousel hero plein écran pour un site de sacs au crochet fait main en Corse (marque : U SAKU).

Chaque slide affiche :
- À gauche (60%) : emplacement photo du sac
- À droite (40%) : nom du sac (en corse), description poétique, prix (80-150€), bouton "Découvrir"

4 slides minimum. L'élément clé : chaque slide a sa propre couleur d'ambiance qui correspond au sac. La transition entre slides est un glissement horizontal fluide (0.8s, cubic-bezier) avec un fondu de couleur progressif.

Couleurs par slide :
1. Vert maquis (#4A6741) — sac inspiré de la flore corse
2. Bleu mer (#3B6B8A) — sac inspiré de la Méditerranée
3. Ocre terre (#8B6F47) — sac inspiré des montagnes
4. Or immortelle (#C8A84E) — sac signature doré

Typos : Cormorant Garamond (titres) + DM Sans (corps). Fond crème (#FAF7F2). Navigation par flèches + dots. Responsive + swipe mobile.
```

---

## NOTES POUR PERSONNALISER LE PROMPT

Avant d'utiliser ce prompt, remplacez :

1. **[TON PRÉNOM]** → votre prénom de créatrice
2. **Les noms des 4 sacs du slider** → vos vrais noms de modèles
3. **Les descriptions** → adaptez avec les vraies descriptions de vos sacs
4. **Les prix exacts** → ajustez par modèle si nécessaire
5. **Ajoutez vos photos** → une fois le site généré, remplacez les placeholders

## CONSEILS D'UTILISATION

- Utilisez le prompt complet pour un site entier
- Utilisez la version courte pour itérer rapidement
- Utilisez le prompt slider seul pour perfectionner cette section d'abord
- Vous pouvez ensuite demander : "Maintenant ajoute la section boutique" etc.
- Si le résultat ne vous plaît pas : "Rends le slider plus lent et plus élégant" ou "Change les couleurs de la slide 2 vers un bleu plus profond"
