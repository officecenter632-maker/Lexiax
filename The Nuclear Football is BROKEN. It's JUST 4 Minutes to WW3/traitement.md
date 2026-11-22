# Journal de segmentation : The Nuclear Football is BROKEN. It's JUST 4 Minutes to WW3 (ojxd4XN0m2o)

Départ : début de la vidéo (aucun segments.json existant). Speech : 215 lignes, 829,28 s (environ 13,8 min), sous-titres manuels en anglais.

## Tranches
- Tranche 1 : lignes 1 à 215 (0 à 829,28 s, environ 13,8 min), 16 segments (id 1 à 16). Le speech entier tient en une seule tranche (moins de 30 minutes). Dernière tranche : complet = true.

## Méthode suivie
- Lecture du speech par blocs de lignes, puis découpage par idées (une affirmation, un exemple ou une étape du raisonnement par segment).
- Les lignes de compte à rebours (« T-06:00 », « T-05:30 »...) sont des marqueurs très courts : chacune est rattachée au début du segment qui la suit, et le compte à rebours figure dans les mots-clés.
- Toutes les coupures tombent à des fins de ligne du speech ; aucun temps estimé (temps_estime = false partout).
- debut d'un segment = fin du précédent ; le premier commence à 0,0, le dernier finit à 829,28.
- Le champ texte est généré par script en concaténant les lignes du speech, mot pour mot, sans correction.
- Titres, résumés et mots-clés en anglais (langue du speech).

## Bilan
- Nombre de segments : 16.
- Plus court : 9,44 s (segment 16, conclusion et renvoi vers la vidéo sur l'Armageddon nucléaire). Plus long : 101,84 s (segment 8, fausse alerte russe de 1995).
- Temps estimés : aucun.
- Passages douteux : aucun passage du speech n'est clairement erroné ; les marqueurs T-xx:xx (lignes 7, 25, 43, 64, 87, 124, 155, 166, 171, 184, 200, 208) ont des durées très courtes et sont conservés tels quels.
- Problèmes rencontrés : aucun.
- Vérification (script) : JSON valide, ids 1 à 16, 5 à 10 mots-clés par segment, temps sans trou, avancement cohérent, textes bout à bout identiques aux lignes 1 à 215 : OK.

## Point d'arrêt
Dernière ligne traitée : 215 sur 215. Travail terminé, rien à reprendre.
