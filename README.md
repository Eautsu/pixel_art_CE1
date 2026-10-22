# Générateur Pixel art CE1

Générez des fiches de calcul dont les réponses révèlent un dessin en pixel art : l'élève colorie la case de la couleur indiquée, et l'image apparaît quand tout est juste.

**Créer la fiche :**
- [Version GitHub Pages](https://eautsu.github.io/pixel_art_CE1/)
- [Version Forge des communs numériques éducatifs](https://florencebourgeoisbossaert.forge.apps.education.fr/pixel_art_CE1)

Outil autonome (un seul fichier HTML, sans installation ni connexion) qui produit des **fiches « pixel art mathématiques »** pour le cycle 2 : l'élève résout des calculs, chaque réponse lui indique une **colonne** d'une grille, la **lettre** donne la ligne, et il colorie la case correspondante. Une fois tous les calculs faits, le dessin apparaît.

Sortie : une fiche **Word ou PDF** (exercice + corrigé), 10×10 ou 15×15.

---

## 1. Le principe en une minute

| Page élève | Page de correction |
|---|---|
| Grille vide (lettres en lignes, numéros en colonnes) | Grille coloriée |
| Légende par couleur : `F) 16 − 9 = ___` | Même légende, avec les réponses |
| « Laisser les cases non mentionnées en blanc » | Titre du dessin, uniquement ici |

Pour colorier `F) 16 − 9 = ___` en rouge, l'élève calcule 7, repère la case **F7** et la colorie en rouge. Le dessin est donc l'auto-correction : si une réponse est fausse, la case est mal placée et le dessin est abîmé.

---

## 2. Intérêt pédagogique

### 2.1 Une même fiche travaille deux compétences

- **Calcul** : mémoriser des faits numériques, mobiliser des procédures, en lien direct avec le calcul mental.
- **Repérage** : se repérer dans un tableau à double entrée (ligne × colonne), compétence de repérage dans l'espace travaillée au CP-CE1 et qui prépare les repérages sur quadrillage et plan.

Par rapport à un coloriage magique classique (un code couleur lié à un résultat), la lecture d'une double entrée est ici **indispensable** : sans elle, impossible de placer la case. L'exercice mobilise donc une autre compétence du programme que le calcul seul.

### 2.2 La validation est intégrée à l'exercice

- Pas de réponse à copier : l'élève calcule *avant* de pouvoir colorier.
- Un résultat faux se voit : la case atterrit au mauvais endroit et le dessin devient incohérent. L'élève a un retour immédiat et peut revenir sur ses calculs.
- Le correcteur (l'élève, un pair ou l'enseignant) contrôle d'un coup d'œil, sans refaire chaque calcul.

### 2.3 La motivation vient de la découverte du dessin

Le but affiché n'est pas « finir la fiche » mais **découvrir le dessin**. Le dessin peut être choisi par l'enseignant (un animal, un objet lié au projet de classe) ou **validé par les élèves de l'année**. L'effet de surprise et l'envie de vérifier portent l'effort de calcul.

### 2.4 Autonomie et organisation de la classe

- Fiche autonome : consigne unique, légende lisible, correction jointe.
- Compatible avec une **pochette d'autonomie** et un contrôle quotidien par l'enseignant : la tâche tient sur une semaine, par petites séquences.
- Le corrigé peut être donné aux élèves en autocorrection, ce qui libère l'enseignant pour un groupe de besoin.

### 2.5 Une progression sur la période, pas une activité isolée

Le dispositif s'inscrit dans une programmation de sessions (exemple utilisé en classe) :

| Session | Notion | Format |
|---|---|---|
| S1 | Comptine numérique | pas de fiche |
| S2 | +1 / −1 | résultat manquant |
| S3 | +2 / −2 | résultat manquant |
| S4 | Doubles et moitiés | résultat manquant |
| S5 | Table de +5 | terme manquant |
| S6 | Compléments à 10 | terme manquant |
| S7 | Bilan : ±1 / ±2, trois formats mélangés | résultat, 1er ou 2e terme manquant |

- **Période 1 : grille 10×10**, période de rodage : dessins et calculs simples, pour installer la compétence « tableau à double entrée ».
- **Période 2 : grille 15×15**, dessins plus élaborés une fois la lecture de la grille acquise.

### 2.6 Variété des formats de calcul

Le résultat, le 1er terme ou le 2e terme peut être l'inconnue (`7 + 2 = ___`, `___ + 5 = 9`, `6 + ___ = 10`). 
On travaille ainsi le sens de l'égalité et des opérations réciproques, au-delà du « calcul qui donne un résultat ».

---

## 3. Lien avec le programme 2025 du cycle 2

Les programmes de cycle 2 en vigueur à la rentrée 2025 sont publiés dans l'annexe du BO n° 41 du 31 octobre 2024. Le dispositif s'y rattache aux entrées suivantes (rattachement au niveau des domaines, pas de citation d'attendus mot à mot) :

| Domaine du programme | Ce que la fiche travaille |
|---|---|
| **Nombres et calculs** : mémoriser des faits numériques ; élaborer des stratégies et maîtriser des procédures | ±1, ±2, doubles et moitiés, compléments à 10, tables, calcul mental ; formats à terme manquant |
| **Nombres et calculs** : numération (dizaines au CP, **centaines au CE1**) | Familles « chiffre des dizaines / des unités / des centaines » |
| **Espace et géométrie** : repérage dans l'espace (CP-CE1) | Lecture et utilisation d'une double entrée lettre × numéro |
| **Organisation et gestion des données** : lire un tableau | Utiliser un tableau pour y placer des informations |
| **Raisonner, communiquer** | Verbaliser sa méthode de calcul, vérifier la cohérence d'un résultat par le dessin |

Le programme insiste sur la **verbalisation des procédures avec les mots de l'élève** : la fiche s'y prête en fin de séance (« comment as-tu trouvé 16 − 9 ? »).

*À vérifier par l'enseignant : la correspondance exacte avec les repères de progression de son niveau (CE1 ou CE2).*

---

## 4. Ce que le générateur apporte à l'enseignant

- **Une fiche en quelques minutes** à partir d'un dessin dessiné dans la page, avec les calculs choisis.
- **Les calculs sont garantis justes** : le programme vérifie chaque calcul et que la réponse correspond bien à la colonne de la case, avant de livrer la fiche.
- **Message clair en cas d'impossibilité mathématique** : par exemple, les doubles sont toujours pairs (les colonnes impaires restent vides), un chiffre ne dépasse jamais 9, ou une couleur a plus de cases dans une colonne qu'il n'existe de calculs distincts. Le message donne la cause et les pistes pour y remédier (ajouter les moitiés, un autre format, etc.).
- **Variété** : les lettres sont mélangées au hasard dans chaque couleur (le dessin est moins prévisible) et deux calculs identiques ne se suivent pas.
- **Lisibilité** : un rappel « (couleur, suite) » en haut de colonne quand une couleur continue ; mise en page automatique en 2 pages ou en pages séparées.
- **Export Word ou PDF**, avec nom, code de session et bandeau Prénom/Date.

---

## 5. Mode d'emploi rapide

1. **Dessiner** la grille (10×10 ou 15×15), ou importer un dessin issu du vérificateur.
2. **Choisir les calculs** : un modèle de départ (S2 à S7, numération) puis ajuster notions, formats, plafond des nombres.
3. **Lire la faisabilité** : le tableau par colonne indique ce qui est possible ; corriger si une alerte rouge apparaît.
4. **Choisir le format** (Word ou PDF) et **générer**.

## Que faire si le générateur affiche des messages rouges ?

Deux causes fréquentes :

- **Impossibilité mathématique** : par exemple, des doubles seuls ne peuvent pas remplir les colonnes impaires, et un chiffre ne dépasse jamais 9.
- **Pas assez de calculs différents** pour composer le dessin.

Dans la plupart des cas, il suffit de :

- accepter quelques répétitions de calculs ;
- combiner plusieurs notions (par exemple doubles et moitiés) ;
- combiner plusieurs formes de calcul (`7 + 2 = ?`, `? + 5 = 9` , `6 + ? = 10`).

Le bouton **« Proposer une solution »** applique ces réglages automatiquement et indique ce qu'il a ajouté. Le bouton **« Régler moi-même »** donne accès à tous les choix.

---

## 6. Conditions de réussite et limites (à garder en tête)

- **L'élève doit bien calculer pour trouver sa colonne.** Si la fiche est trop facile à deviner ou si la correction est visible, le calcul peut être contourné : donner le corrigé après la tâche.
- **Le dessin doit rester un moteur, pas un piège** : au rodage, privilégier des dessins simples et lisibles.
- **Le contrôle humain compte** : un contrôle régulier (par exemple quotidien) évite qu'un élève s'enferme dans une erreur répétée.
- **Les répétitions de calculs** sont parfois inévitables (peu de calculs possibles pour certaines colonnes) : l'option est à valider explicitement.
- Les familles de calcul se limitent aujourd'hui aux additions, soustractions, compléments, tables de multiplication, doubles/moitiés et chiffres ; pas de division.

---

## 7. Fichiers

- `Générateur Pixel art CE1.html` : l'outil (ouvrir dans un navigateur).
- `verificateur_pixel_art.html` : saisie et validation d'un dessin à part (export compatible).
- `gabarit_pixel_art.md` : règles de présentation des fiches.

## Sources

- [Programmes de mathématiques cycle 2, présentation (académie d'Orléans-Tours)](https://pedagogie.ac-orleans-tours.fr/documents/pdf/presentation_programmes_maths_c2_pdf.pdf) (renvoie à l'annexe du BO n° 41 du 31/10/24)
