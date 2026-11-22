# Traitement : fDzCHPWkou4

Vidéo : « World War 3 Protocol. Why Global Nuclear Annihilation Is Inevitable. » Speech en anglais, sous-titres automatiques, 5891 lignes, 11 483,66 s (environ 191 min). Environ 7 tranches de 30 min.

## Journal des tranches
- Départ : début de la vidéo (segments.json absent).
- Tranche 1 : lignes 1 à 985 sur 5891, 0 à 1999,39 s (33,3 min), 36 segments (id 1 à 36). Fin d'idée choisie à la ligne 985 (« ...and it is still not enough. »), d'où une tranche un peu longue.
- Tranche 2 : lignes 986 à 1865 sur 5891, 1999,39 à 3712,97 s (28,6 min), 36 segments (id 37 à 72). Contenu : fin du scénario chinois et hiver nucléaire, puis la partie « ce que Hollywood se trompe sur l'apocalypse nucléaire » (mythes : frigo en plomb, Dead Hand, fallout, mutants, EMP, Mad Max), puis les effets d'une explosion de 100 kt sur le corps humain par distance (ground zero, 1000 ft, 0,5 mile, 1 mile, 5 miles, effets à long terme). Fin d'idée à la ligne 1865 (« ...far beyond normal aging. »). Prochaine étape : reprendre à la ligne 1866 (« Silo doors groan open », début du scénario « Zero hour » de guerre nucléaire mondiale).

## Décisions prises
- Segmentation par idées : une idée = un point (étape du scénario, incident historique, système d'armes, étape du scénario chinois). Les passages de transition de quelques secondes sont rattachés à l'idée voisine.
- Style des titres : court, en anglais, nominal, avec le sujet principal (noms propres, systèmes, lieux). Résumés de 2 à 3 phrases factuelles avec chiffres et noms. 8 mots-clés par segment.
- Taille des idées : en général 25 à 120 s ; la plupart entre 40 et 80 s.
- Le texte de chaque segment est produit par script à partir de speech.json (découpage par mots), donc mot pour mot. Les marqueurs de sous-titres « [music] » et « >> » sont conservés tels quels dans les textes.
- Temps : les lignes des sous-titres automatiques se chevauchent. Une coupure au début d'une ligne prend le debut de cette ligne ; une coupure au milieu d'une ligne est estimée au prorata des mots entre le debut de la ligne et le debut de la suivante. Presque tous les segments ont donc temps_estime = true (au moins une borne tombe au milieu d'une ligne). Entre deux tranches, la borne est la fin de la dernière ligne traitée.
- Outils : /home/claude/build2.py (ajout d'une tranche à segments.json à partir d'une liste de débuts d'idées) et verif2.py (vérification de l'étape 5). Un début d'idée est repéré par une phrase et un numéro de ligne approximatif.

## Remarques sur le speech (tranche 1)
- Le narrateur alterne un scénario minute par minute (compte à rebours du président américain) et des digressions historiques (Carter, Reagan, 1995, 1979, Dead Hand), puis un scénario de guerre nucléaire autour de Taïwan avec la Chine (limité, puis total).
- Transcription automatique : quelques fautes possibles (« Longpo », « Yalong Po », « Cheget »), conservées telles quelles.
