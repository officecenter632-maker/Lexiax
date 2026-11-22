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
- Tranche 3 : lignes 1908 à 2863 (sur 6858), minutes couvertes 61,3 à 92,2 (5531,25 s), 29 segments (id 62 à 90). Contenu : crise des missiles de Cuba en détail (62 à 72), Peste noire et autres pestes (73 à 75), seconde version de la crise de Cuba (76 à 79), prédictions ratées : calendrier maya 2012, Y2K, rapture 2021 (80 à 83), armes de fin du monde : bioweapons (anthrax, fièvre Q, Marburg) et bombes atomique/H/Tsar Bomba (84 à 90). Remarque : la vidéo est une compilation de plusieurs vidéos ; des sujets déjà vus (crise de Cuba, Peste noire) reviennent, traités comme des idées distinctes.
- Tranche 4 : lignes 2864 à 3792 (sur 6858), minutes couvertes 92,2 à 122,4 (7345,37 s), 31 segments (id 91 à 121). Contenu : fin des armes de fin du monde (Davy Crockett, bombes sales, Novichok, sarin, assassinat, tiges de Dieu, lasers, MK Ultra, animaux armés, segments 91 à 99), vidéo Nostradamus (100 à 114), puis début d'une nouvelle vidéo « 12 most insane ways the world could end » (115 à 121 : introduction, n° 12 IA, n° 11 nanorobots, n° 10 géo-ingénierie solaire). Remarque : le segment 121 se termine par la transition « as shown by number nine » vers le n° 9.

## Point d'arrêt
- Dernière ligne traitée : 3792 (« …as shown by number nine »). Prochaine étape : reprendre à la ligne 3793 (« on our list. Number nine, catastrophic climate change… »), id suivant : 122.

## Reprise à la ligne 3793 (agent suivant)
- Travail précédent vérifié avec le script de l'étape 5 : OK (121 segments, lignes 1 à 3792). Même méthode : coupures en fin de ligne (temps_estime false), début d'un segment = fin du précédent, titres anglais « Number N: ... » pour l'ouverture d'un scénario, textes copiés mot pour mot.
- Tranche 5 : lignes 3793 à 4784 (sur 6858), minutes couvertes 122,4 à 154,1 (9248,19 s), 40 segments (id 122 à 161). Contenu : fin du classement « 12 most insane ways » (Number nine climat à Number one astéroïde, segments 122 à 134), puis nouvelle vidéo « best places to survive the end of the world » (Nouvelle-Zélande, Australie, Islande, Altiplano, Lesotho, Tristan da Cunha, Antarctique, villes refuges, bunkers, segments 135 à 150), puis scénario fictif de Troisième Guerre mondiale avec refuge à Tristan da Cunha (segments 151 à 161, en cours). Les coupures sont posées sur les lignes qui portent le titre « Number N », donc une phrase de transition peut commencer un segment.
- Remarque : sous-titres automatiques, balises « [music] » conservées.

## Point d'arrêt (mis à jour)
- Dernière ligne traitée : 4784 (« democratically elected every few years. »). Prochaine étape : reprendre à la ligne 4785 (« The best part about the island, though, is its remoteness. »), id suivant : 162. Le scénario Tristan da Cunha continue après la ligne 4784.

## Reprise à la ligne 4785 (agent suivant)
- Travail précédent vérifié avec le script de l'étape 5 : OK (161 segments, lignes 1 à 4784). Même méthode : coupures en fin de ligne (temps_estime false), textes générés mot pour mot à partir des lignes de speech.json, titres anglais, résumés en français.
- Tranche 6 : lignes 4785 à 5832 (sur 6858), minutes couvertes 154,1 à 185,3 (11120,31 s), 47 segments (id 162 à 208). Contenu : fin du scénario Tristan da Cunha (162 à 167), scénario fictif de la famille texane et de son bunker de luxe (168 à 182), scénario fictif d'apocalypse zombie en immeuble de bureaux puis fuite vers l'Alaska (183 à 205), nouvelle partie « could the zombie apocalypse actually happen » : folklore haïtien et neurotoxine (206 à 208, en cours).
- Remarques : sous-titres automatiques, balises « [music] » conservées. Le segment 205 se termine sur « ... but definitely not a zombie. A horde of feral creatures tears » : le début du thème suivant est dans la ligne de coupure, les temps n'ont pas été estimés.

## Point d'arrêt (mis à jour)
- Dernière ligne traitée : 5832 (« leaving them in a zombie-like trance. »). Prochaine étape : reprendre à la ligne 5833 (« Could this create a zombie plague? In a word, no. »), id suivant : 209.
