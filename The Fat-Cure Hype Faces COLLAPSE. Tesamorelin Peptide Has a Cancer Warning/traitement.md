# Journal de segmentation : L4Bobswuv8k

Départ : début de la vidéo (aucun segments.json existant).

## Tranches
- Tranche 1 : lignes 1 à 197 (sur 197), minutes couvertes 0,0 à 16,3 (980,8 s), 22 segments (id 1 à 22). Le speech entier dure moins de 30 minutes : une seule tranche. Dernière tranche : « complet » = true.

## Méthode suivie
- Lecture du speech par blocs de 50 lignes, puis définition manuelle des idées (un point par segment).
- Toutes les coupures tombent en fin de ligne du speech : aucun temps estimé (temps_estime = false partout). Les transitions de quelques lignes sont rattachées à l'idée voisine (ex. lignes 144-145 aux effets secondaires, ligne 63 à l'approbation FDA).
- Le champ texte est extrait par script, mot pour mot, des lignes du speech (jointes par un espace). Titres, résumés et mots-clés en anglais (langue du speech).
- Style des titres : courts, descriptifs, sans ponctuation finale. Idées de 16 à 79 secondes environ.

## Bilan
- Nombre de segments : 22.
- Plus court : 16,0 s (id 22, conclusion). Plus long : 78,8 s (id 13, effets cognitifs).
- Vérification par script : JSON valide, nb_segments exact, id 1 à 22 sans trou, 5 à 10 mots-clés, temps croissants et sans trou, avancement cohérent, textes bout à bout identiques aux lignes 1 à 197.
- Passages où les temps sont estimés : aucun.
- Passages douteux du speech : ligne 164 « odds ratio of roughly 3.3% » (un odds ratio n'est pas un pourcentage, formulation du speech conservée) ; ligne 100 « But will it work? » apparaît comme transition sans lien clair avec la suite (conservée dans le segment 11).
- Problèmes rencontrés : aucun.
- Point d'arrêt : ligne 197 (fin). Prochaine étape : aucune, travail terminé.
