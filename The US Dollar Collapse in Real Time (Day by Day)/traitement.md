# Traitement : baO2fIL4coI

Départ : début de la vidéo (aucun segments.json existant).
Speech : 328 lignes, 1271,0 s (~21,2 min), sous-titres manuels, langue en. Une seule tranche (< 30 min).

## Tranche 1 : lignes 1 à 328 (terminé)
- Minutes couvertes : 0 à 21,2 (0,16 s à 1271,0 s).
- Segments : 41 (id 1 à 41).
- Remarques : toutes les coupures tombent à des fins de ligne, donc aucun temps estimé (temps_estime = false partout). Les temps d'une ligne à l'autre sont repris tels quels (le debut d'un segment = la fin du précédent). Trou dans les sous-titres entre la ligne 48 (fin 178,08) et la ligne 49 (début 184,88) : il est absorbé à l'intérieur du segment 7.

## Décisions
- Le récit est organisé en « jours » (Day 1, Day 2...) : chaque marqueur « Day N » est rattaché à l'idée qui le suit ; une journée riche est scindée en plusieurs idées (ex. Day 4 en 3 segments, Day 21 en 2).
- Style des titres : phrase courte en anglais (langue du speech), préfixe « Day N: » quand l'idée ouvre une nouvelle journée.
- Idées de 13 à 49 s ; textes repris mot pour mot de speech.json (rien corrigé).

## Bilan
- Méthode : lecture du speech par blocs de ~80 lignes, découpage par idées, génération de segments.json par script à partir des bornes de lignes et des métadonnées, puis vérification automatique.
- Nombre de segments : 41. Plus court : 13,3 s (segment 34) ; plus long : 49,2 s.
- Vérification : OK (JSON valide, id continus, 5 à 10 mots-clés, temps croissants sans trou, avancement cohérent, textes bout à bout = lignes 1 à 328).
- Passages douteux : aucun temps estimé ; le speech est un récit fictif (scénario), les chiffres cités sont ceux du speech et n'ont pas été vérifiés.
- Point d'arrêt : complet (ligne 328 sur 328). Rien à reprendre.
