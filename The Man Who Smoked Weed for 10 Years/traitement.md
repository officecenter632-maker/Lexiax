# Journal de segmentation : _KCvoOhUqHA

Vidéo : « The Man Who Smoked Weed for 10 Years »
Speech : 224 lignes, 0 à 1013,08 s (≈ 16,9 min), langue en, source manuelle.

## Départ
Départ du début de la vidéo (aucun segments.json existant).

## Tranches
- Tranche 1 : lignes 1 à 224 (0 à 1013,08 s, ≈ 16,9 min, moins de 30 min donc une seule tranche), 23 segments, aucun temps estimé.

## Méthode
- Lecture du speech par morceaux (lignes 1-80, 81-155, 156-224), jamais en entier d'un coup.
- Segmentation par idées, coupures uniquement en fin de ligne (temps_estime = false partout). La vidéo suit un fil chronologique (année par année de la vie d'Alex) : je coupe à chaque nouvel effet (tolérance, CUD, mémoire, dopamine, sommeil, grey matter, QI, poumons, cœur) puis à chaque point de la phase de récupération.
- Les transitions courtes sont rattachées au segment qui les suit (ex. ligne 94 « And he didn't even know it. Things get worse in his fourth and fifth year… ») ou qui les précède (ex. ligne 132 « the term high functioning stoner is a lie »).
- Segments définis par plages de lignes ; le champ texte est reconstruit par script en joignant les lignes du speech mot pour mot. debut = fin du segment précédent.
- Titres, résumés (2 à 3 phrases) et 7 à 9 mots-clés écrits en anglais, langue du speech.
- Vérification par script : JSON valide, nb_segments, id continus, champs non vides, 5 à 10 mots-clés, temps croissants sans trou, avancement cohérent, textes bout à bout = lignes 1 à 224 du speech (aux espaces près) : OK.

## Bilan
- 23 segments ; plus court : 17,84 s (segment 22, récupération cardiaque) ; plus long : 78,28 s (segment 19, récupération cognitive et âge de début).
- Passages à temps estimé : aucun.

## Passages douteux / remarques
- Ligne 142 : « marijuana mostly gets a free pass. But by the sixth and seventh years… » contient une transition vers la partie suivante ; la ligne entière est restée dans le segment 14 (mythe de l'innocuité) car on ne coupe pas en milieu de ligne.
- Lignes 197/198 : une phrase est répartie sur deux lignes (« …CB1 receptors can return to / normal levels… ») ; la coupure entre les segments 19 et 20 tombe donc au milieu d'une phrase, en fin de ligne.
- Les chiffres cités (IQ, 25 % / 42 %, 36 %, âge 41 vs 65, etc.) sont ceux du speech, non vérifiés.

## Point d'arrêt
Traitement complet : lignes 1 à 224 faites, « complet »: true. Rien à reprendre.
