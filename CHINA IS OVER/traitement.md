# Journal de segmentation : CHINA IS OVER (Qi5iRWzsQdc)

Départ : début de la vidéo (aucun segments.json existant). Speech : 213 lignes, 1064,4 s (environ 17,7 min), sous-titres manuels en anglais.

## Tranches
- Tranche 1 : lignes 1 à 213 (0 à 1064,4 s, environ 17,7 min), 24 segments (id 1 à 24). Le speech entier tient en une seule tranche (moins de 30 minutes). Dernière tranche : complet = true.

## Méthode suivie
- Lecture du speech par blocs de lignes, puis découpage par idées (un point précis par segment : chiffres, exemple, étape du raisonnement).
- Toutes les coupures tombent à des fins de ligne du speech ; aucun temps estimé (temps_estime = false partout).
- debut d'un segment = fin du précédent ; le premier commence à 0,0, le dernier finit à 1064,4.
- Le champ texte est généré par script en concaténant les lignes du speech, mot pour mot, sans correction.
- Titres, résumés et mots-clés en anglais (langue du speech).

## Bilan
- Nombre de segments : 24.
- Plus court : 16,0 s (segment 24, conclusion et renvoi vers la vidéo sur le Japon). Plus long : 65,0 s (segment 13, coût du mariage et chute de l'immobilier).
- Temps estimés : aucun.
- Passages douteux : la ligne 17 contient une faute de sous-titre (« t 3.275 million ») et la ligne 138 se termine par « . . » ; ligne 94 « 1.54 cm » (vraisemblablement 1,54 m) ; conservés tels quels. Les lignes 165 et 175 coupent une phrase, regroupées avec la suite dans le segment concerné.
- Problèmes rencontrés : aucun.
- Vérification (script) : JSON valide, ids 1 à 24, 5 à 10 mots-clés par segment, temps sans trou, avancement cohérent, textes bout à bout identiques aux lignes 1 à 213 : OK.

## Point d'arrêt
Dernière ligne traitée : 213 sur 213. Travail terminé, rien à reprendre.
