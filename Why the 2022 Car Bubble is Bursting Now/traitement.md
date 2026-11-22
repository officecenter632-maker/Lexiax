# Segmentation : « Why the 2022 Car Bubble is Bursting Now » (SSVG6rJM8Cw)

Départ : début de la vidéo (aucun segments.json existant).
Speech : 227 lignes, de 0,16 s à 957,31 s (environ 16 min), langue en, source manuelle. Une seule tranche, car le speech dure moins de 30 minutes.

## Journal des tranches

| Tranche | Lignes traitées | Minutes couvertes | Segments (id) | Remarques |
|---|---|---|---|---|
| 1 | 1 à 227 (tout) | 0 à 15,96 min (957,31 s) | 25 (id 1 à 25) | Tranche unique et dernière. Toutes les coupures tombent sur des fins de ligne : aucun temps estimé. |

## Décisions prises et pourquoi

- Une idée = un point précis qui se comprend seul : une étape du raisonnement ou une scène d'un des trois personnages (Molly, Tom, Herman).
- Les histoires des trois personnages sont découpées en deux temps (choix du prêt, puis issue), car ce sont deux idées distinctes qui reviennent plus loin dans le speech.
- Les transitions de quelques secondes sont rattachées au segment qui les introduit, par exemple la ligne 147 « But not everyone is so lucky » ouvre le segment sur prime et subprime, et les lignes 115 à 118 (« Molly, Tom, and Herman couldn't be more different ») restent avec l'histoire de Herman.
- Titres, résumés et mots-clés en anglais (langue du speech). Les textes des segments sont repris de speech.json par script, mot pour mot, lignes jointes par une espace.
- Le segment 25 (outro, 11,8 s) est volontairement court : c'est le renvoi vers la vidéo sur Ford.

## État final

- Méthode : lecture du speech par morceaux de 60 lignes, définition des idées par plages de lignes, assemblage de segments.json par script (temps pris sur les lignes, textes copiés du speech), puis vérification par script.
- Nombre de segments : 25.
- Plus court : 11,8 s (id 25, outro Ford). Plus long : 87,6 s (id 17, issue de Tom avec Uber).
- Point d'arrêt : dernière ligne traitée = 227 sur 227, « complet » = true. Rien à reprendre.
- Vérification : JSON valide, nb_segments exact, id de 1 à 25 sans trou, 5 à 10 mots-clés par segment, temps croissants et sans trou, avancement cohérent, textes bout à bout identiques aux lignes 1 à 227 (aux espaces près). Résultat : OK.

## Passages douteux

- Ligne 227 (id 25) : le texte automatique contient « panic. e. Watch “REAL Reason Why FORD Is Failing” », avec un « e. » parasite conservé tel quel dans le texte.
- Ligne 79 (id 9) : mélange d'unités dans le texte source (« 14,000 miles (22,530 km) »), conservé tel quel.
- Les chiffres de 2026 (108 millions de prêts, 1,7 trillion de dollars, 23 % de prêts de 84 mois ou plus, 6 900 dollars de capitaux propres négatifs) sont repris du speech sans vérification externe.
- Temps : les temps de sous-titres sont approximatifs, mais ici toutes les coupures sont à des limites de ligne.

## Problèmes rencontrés

Aucun.
