# Journal de segmentation : 0oV87yfN59g

Départ : début de la vidéo (aucun segments.json existant). Speech : 6858 lignes, 13 080,84 s (≈ 218 min), sous-titres automatiques en anglais, avec des balises « [music] » conservées telles quelles dans les textes.

## Décisions
- Vidéo en compte à rebours de scénarios de fin du monde (« Number eight » à « Number one »). Une idée = un point précis d'un scénario (exemple, citation d'expert, étape du raisonnement) ; durée visée 20 à 110 s.
- Toutes les coupures tombent en fin de ligne : temps_estime = false. Le debut d'un segment est la fin du précédent (les lignes des sous-titres automatiques ont de petits trous entre elles).
- Titres : en anglais, « Number N: ... » pour le premier segment d'un scénario numéroté, sinon titre descriptif court. Résumés de 2 à 3 phrases, 5 à 10 mots-clés.
- Les phrases de transition entre scénarios sont rattachées au scénario qui se termine (si elles l'annoncent) ou à celui qui commence.
- Les segments sont construits par script à partir de listes de bornes de lignes ; le texte est copié mot pour mot du speech.

## Tranches
- Tranche 1 : lignes 1 à 966 (sur 6858), minutes couvertes 0 à 30,3 (1820,01 s), 30 segments (id 1 à 30). Scénarios 8 (astéroïde) à début du 1 (nanotechnologie). Remarque : transcription automatique, quelques erreurs (« 1346 to 153 » pour 1353, « Chery Nick Bostrom ») conservées.
- Tranche 2 : lignes 967 à 1907 (sur 6858), minutes couvertes 30,3 à 61,3 (3677,63 s), 31 segments (id 31 à 61). La vidéo devient une compilation : fin du scénario nanotechnologie, deuxième classement « most likely ways » (astéroïde, trous noirs, volcans, climat, nucléaire, IA, extraterrestres, simulation), puis le Livre de l'Apocalypse (segments 44 à 58), puis la crise des missiles de Cuba (à partir du segment 59). Remarque : plusieurs coupures tombent au milieu d'une phrase car les lignes des sous-titres automatiques coupent en plein milieu (ex. segments 33/34, 36/37, 50/51), sans temps estimé.

## Point d'arrêt
- Dernière ligne traitée : 1907 (« …and in politics, »). Prochaine étape : reprendre à la ligne 1908 (« matter most. Soviet premier Nikita Krushchev… », Khrouchtchev et les missiles à Cuba), id suivant : 62.
