# 🩺 DOCTEUR JULIEN

> Jeu éducatif réalisé par **Julien Animateur** pour l'ALSH.

---

## 🎮 Présentation

**Docteur Julien** est un jeu de réflexion inspiré du célèbre *Dr. Mario* (Nintendo).  
Les enfants incarnent un médecin qui doit soigner des petits monstres malades appelés **Gromis** en lançant des pilules colorées dans un flacon géant.

Le jeu se joue **en équipe** sur un même ordinateur — pas de compétition, juste de la coopération et du fun !  
Idéal pour des groupes de 2 à 3 enfants par poste, de **6 à 12 ans**.

---

## 🦠 Concept

Des **virus** de couleur (rouge 🔴, bleu 🔵, jaune 🟡) sont coincés dans un flacon.  
Le docteur lance des **pilules à deux couleurs** du haut du flacon.

Pour **tuer un virus**, il faut aligner **4 cases de la même couleur** à la suite — horizontalement ou verticalement — en combinant pilules et virus.

Quand un virus est éliminé, un **son de victoire** retentit 🔊  
Quand tous les virus sont soignés, le niveau est terminé ! 🎉

---

## 🕹️ Contrôles

| Touche | Action |
|--------|--------|
| ⬅️ ➡️ Flèches gauche/droite | Déplacer la pilule |
| ⬇️ Flèche bas | Faire tomber la pilule plus vite |
| ⬆️ Flèche haut ou `Z` | Faire pivoter la pilule |
| `R` | Recommencer le niveau (sans perdre sa progression) |

---

## 📋 Règles du jeu

1. **Les pilules tombent** du haut du flacon, une à la fois.
2. **Déplacez et tournez** la pilule avant qu'elle ne touche le fond ou d'autres pièces.
3. **Alignez 4 cases** de même couleur (pilule + virus) pour les éliminer.
4. **Les pilules orphelines** (dont l'autre moitié a été éliminée) tombent par gravité et peuvent créer des **combos en chaîne** !
5. Si la pile de pilules **atteint le haut** du flacon, c'est **Game Over**.
6. Soignez **tous les virus** pour passer au niveau suivant.
7. La touche `R` permet de **recommencer le niveau en cours** si la situation est bloquée — le score et le niveau sont conservés.

### 💡 Astuce combo
Quand une pilule tombe et crée une réaction en chaîne (plusieurs séries éliminées d'affilée), un **multiplicateur de score** s'active :
- 2 groupes simultanés → **×2**
- 3 groupes ou plus → **×4**

---

## 🏆 Les 40 niveaux

Le jeu compte **40 niveaux** de difficulté progressive.  
Sur le panneau droit, une **grille de 40 cases** montre l'avancement de l'équipe :  
- ✓ jaune = niveau terminé  
- 🟢 vert clignotant = niveau en cours  
- ⚫ gris = niveau à venir  

### Progression de la difficulté

| Niveau | Virus | Vitesse de chute | Virus Super ★ |
|--------|-------|-----------------|---------------|
| 1 | 4 | Très lente (800ms) | Aucun |
| 5 | 16 | Lente (660ms) | Aucun |
| 10 | 26 | Modérée (633ms) | 0% |
| 15 | 30 | Soutenue (550ms) | 18% |
| 20 | 37 | Rapide (467ms) | 37% |
| 30 | 41 | Très rapide (300ms) | 55% |
| 40 | 48 | Extrême (150ms) | 60% |

### Les Virus Super ★
À partir du **niveau 8**, apparaissent des **virus Super** (marqués d'une étoile ★).  
Ils sont plus résistants : il faut aligner **5 cases** au lieu de 4 pour les éliminer !

### Bonus de vitesse
Si un niveau est terminé en **moins de 60 secondes**, l'équipe gagne **+1000 points bonus** !

---

## 🎵 Musiques et sons

| Moment | Son |
|--------|-----|
| Pendant le jeu | 🎵 *Fever* — Dr. Mario (NES) |
| Virus éliminé | ⭐ Son de victoire |
| Game Over | 🎶 Musique Game Over — Dr. Mario (NES) |

---

## 📊 Scores

- **+100 points** par virus éliminé  
- **×2 ou ×4** si plusieurs groupes éliminés simultanément (combo)  
- **+1000 points** si le niveau est terminé en moins d'1 minute  
- Les scores sont sauvegardés localement sur chaque ordinateur  

---

## 👥 Mode équipe

Le jeu est conçu pour être joué **sans compétition**.  
Chaque ordinateur accueille une équipe unique qui entre ses prénoms au démarrage.  
Il n'y a **pas de classement entre les ordinateurs** — chaque groupe vit sa propre aventure !

Terminer les **40 niveaux** débloque un écran champion spécial 🌟

---

## 🖥️ Déploiement

Le jeu est hébergé sur **Vercel** et accessible depuis n'importe quel navigateur web.  
Aucune installation requise — il suffit d'ouvrir le lien sur les 16 ordinateurs.

---

*Jeu réalisé par Julien Animateur · ALSH 2026*
