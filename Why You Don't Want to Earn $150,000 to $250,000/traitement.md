# Traitement : Why You Don't Want to Earn $150,000 to $250,000 (tehBa2ZjG-I)

## Départ
Aucun segments.json au départ : début de la vidéo (ligne 1). Aucun autre agent n'avait travaillé sur ce dossier.

## Tranches
- Tranche 1 : lignes 1 à 191 (toute la vidéo, 0,0 s à 867,3 s soit environ 14,5 minutes, donc une seule tranche de moins de 30 minutes). 30 segments (id 1 à 30). Aucune coupure au milieu d'une ligne, donc temps_estime = false partout.

## Méthode suivie
- Lecture du speech par blocs d'environ 60 lignes, sans jamais l'afficher en entier.
- Segmentation par idées : coupe au changement de sujet, transitions courtes rattachées à l'idée voisine (par exemple la ligne 46 « And that's where the real squeeze begins » reste avec le passage sur les impôts et le 401(k)).
- Toutes les coupures tombent sur des fins de ligne du speech. Le debut d'un segment est la fin du précédent ; le premier commence à 0,0 s et le dernier finit à 867,3 s.
- Le texte de chaque segment est repris par script, mot pour mot, des lignes du speech (lignes jointes par un espace). Titre, résumé et mots-clés sont écrits à la main, en anglais (langue du speech).

## Bilan
- 30 segments. Le plus court : id 30 (10,4 s, conclusion et renvoi vers une autre vidéo). Le plus long : id 16 (50,0 s, ouvriers et cadres dans le même bateau).
- Temps estimés : aucun.
- Passages douteux du speech (conservés tels quels) :
  - Ligne 110 : la phrase « watch 80% of it dwindle away » n'a pas de point final.
  - Ligne 150 : « challenge.. » avec deux points.
  - Les chiffres (inflation 3,4 %, taux hypothécaires 6 %, etc.) viennent du speech et n'ont pas été vérifiés.
- Problèmes rencontrés : aucun.
- Vérification (script) : JSON valide, nb_segments exact, id 1 à 30 continus, 5 à 10 mots-clés partout, temps croissants sans trou, avancement cohérent, textes bout à bout identiques aux lignes 1 à 191 : OK.

## Point d'arrêt
Dernière ligne traitée : 191 sur 191. Traitement complet, rien à reprendre.
