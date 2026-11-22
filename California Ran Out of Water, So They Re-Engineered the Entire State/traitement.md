# Journal de segmentation : L-gAoGQrvp0

Vidéo : « California Ran Out of Water, So They Re-Engineered the Entire State »
Speech : 243 lignes, 0 à 1069,46 s (≈ 17,8 min), langue en, source manuelle.

## Départ
Départ du début de la vidéo (aucun segments.json existant).

## Tranches
- Tranche 1 : lignes 1 à 243 (0 à 1069,46 s, ≈ 17,8 min, soit moins de 30 min donc une seule tranche), 28 segments, aucun temps estimé.

## Méthode
- Lecture du speech par morceaux (lignes 1-85, 86-165, 166-243), jamais en entier d'un coup.
- Segmentation par idées avec des coupures uniquement en fin de ligne (donc temps_estime = false partout). Les phrases de transition (ex. « But slavery was just the beginning », « Which may be why… ») sont rattachées au segment suivant ou précédent selon leur sens.
- Segments définis par plages de lignes ; le champ texte est reconstruit par script en joignant les lignes du speech mot pour mot (rien de corrigé). debut = fin du segment précédent.
- Titres, résumés (2 à 3 phrases) et 5 à 9 mots-clés écrits en anglais, langue du speech.
- Vérification par script : JSON valide, nb_segments, id continus, champs non vides, 5 à 10 mots-clés, temps croissants sans trou, avancement cohérent, textes bout à bout = lignes 1 à 243 du speech (aux espaces près) : OK.

## Bilan
- 28 segments ; plus court : 12,88 s (segment 28, outro) ; plus long : 73,16 s (segment 26, exode démographique).
- Passages à temps estimé : aucun.

## Passages douteux / remarques
- Le titre de la vidéo parle d'eau (« Ran Out of Water »), mais le speech traite de l'histoire économique de la Californie (ruée vers l'or, exploitation, main-d'œuvre, Big Tech, exode) et jamais de l'eau. Le speech est repris tel quel, sans correction.
- Ligne 238 : « $300 trillion empire » alors que la ligne 1 dit « $3 trillion » (incohérence du speech d'origine, conservée).
- Ligne 78 : « tThe » (faute de frappe d'origine conservée).
- Ligne 51 : « That was the year California legalized indigenous slavery, passing the Foreign Miners' Tax » : confusion probable du speech (la loi de 1850 sur l'esclavage et la taxe sont deux textes), conservée telle quelle.

## Point d'arrêt
Traitement complet : lignes 1 à 243 faites, « complet »: true. Rien à reprendre.
