# Traitement : 8FgyNgIgVjw

Départ : début de la vidéo (aucun segments.json existant).

## Tranches
- Tranche 1 (unique) : lignes 1 à 215 sur 215, 0 s à 996,32 s (environ 16,6 minutes), 22 segments. Le speech est plus court que 30 minutes, donc une seule tranche. Aucune coupure au milieu d'une ligne : temps_estime est false partout.

## Méthode
- Lecture du speech en deux blocs (lignes 1 à 105, puis 106 à 215), puis découpage par idées en plages de lignes entières (changement de sujet = coupure). Les transitions courtes sont rattachées à l'idée voisine.
- Titre, résumé (2 à 3 phrases) et 5 à 7 mots-clés en anglais, langue du speech.
- segments.json généré par script : textes mot pour mot (lignes jointes par un espace), debut d'un segment = fin du précédent.
- Vérification par script : JSON valide, id continus, temps sans trou, mots-clés 5 à 10, textes bout à bout identiques aux lignes 1 à 215.

## Bilan
- 22 segments ; plus court 8,8 s (id 21, conclusion), plus long 74,9 s (id 15, année 30, adaptation sans satellites).
- Les repères « Year N » du narrateur tombent souvent en fin de ligne (par exemple « Year 2. » à la fin de la ligne 40). Comme les coupures sont faites aux fins de ligne, ce repère reste dans le texte du segment précédent, alors que son titre et son résumé décrivent l'année qui suit : c'est volontaire, pour ne pas estimer de temps.
- Passages douteux : aucun temps estimé ; les temps viennent de sous-titres manuels. Faute de transcription dans le speech : « colossians » (ligne 46, pour collisions) et « TPredicting » (ligne 84) sont gardés tels quels.
- Point d'arrêt : complet (ligne 215). Rien à reprendre.
