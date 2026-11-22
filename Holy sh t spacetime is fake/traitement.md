# Journal de segmentation : Holy sh*t spacetime is fake... (HTYIKPcPRRQ)

Départ : début de la vidéo (aucun segments.json existant). Speech : 204 lignes, 986,72 s (environ 16,4 min), sous-titres manuels en anglais.

## Tranches
- Tranche 1 : lignes 1 à 204 (0,24 à 986,72 s, environ 16,4 min), 20 segments (id 1 à 20). Le speech entier tient en une seule tranche (moins de 30 minutes). Dernière tranche : complet = true.

## Méthode suivie
- Lecture du speech par blocs de lignes, puis découpage par idées (une affirmation, un exemple ou une étape du raisonnement par segment).
- Toutes les coupures tombent à des fins de ligne du speech ; aucun temps estimé (temps_estime = false partout).
- debut d'un segment = fin du précédent ; le premier commence à 0,24 (début de la première ligne), le dernier finit à 986,72.
- Le champ texte est généré par script en concaténant les lignes du speech, mot pour mot, sans correction.
- Titres, résumés et mots-clés en anglais (langue du speech).
- Quand une phrase court sur deux lignes, la coupure est placée à la fin de la ligne la plus proche (ex. segments 5/6 et 18/19).

## Bilan
- Nombre de segments : 20.
- Plus court : 14,8 s (segment 20, conclusion et renvoi vers la vidéo sur la fin de l'univers). Plus long : 92,8 s (segment 13, superdéterminisme).
- Temps estimés : aucun.
- Passages douteux : ligne 87 (« physicists David from MIT, and UC San Diego », nom manquant) et ligne 3 (« 7.8 billion light years » mentionné avant l'expérience) ; lignes 40 et 138-141 contiennent des citations dont la ponctuation est irrégulière. Conservés tels quels.
- Problèmes rencontrés : aucun.
- Vérification (script) : JSON valide, ids 1 à 20, 5 à 10 mots-clés par segment, temps sans trou, avancement cohérent, textes bout à bout identiques aux lignes 1 à 204 : OK.

## Point d'arrêt
Dernière ligne traitée : 204 sur 204. Travail terminé, rien à reprendre.
