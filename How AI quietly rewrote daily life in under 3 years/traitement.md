# Journal de segmentation : How AI quietly rewrote daily life in under 3 years (AVOt4CCwAB4)

Speech : 6328 lignes, 13291.68 s (~3 h 41), sous-titres automatiques en anglais.
Départ : début de la vidéo (aucun segments.json existant).

## Décisions de méthode (à respecter pour rester cohérent)
- Les segments sont définis par plages de lignes du speech ; le texte est assemblé par script, mot pour mot (lignes jointes par un espace). Aucune coupure au milieu d'une ligne, donc temps_estime = false partout.
- Les sous-titres sont en « rolling captions » : une ligne est dite à peu près entre son debut et le debut de la ligne suivante. Une coupure entre deux segments est donc placée au debut de la première ligne du segment suivant. Exception : le dernier segment d'une tranche finit à la fin de la dernière ligne traitée (= avancement.fin_traitee_s), et le segment suivant (tranche suivante) commence à cet instant.
- Comme on coupe à la ligne, quelques mots de transition peuvent passer d'un segment à l'autre (par ex. « The idea of a » en fin de segment 1) ; on a choisi la coupure la plus proche de la fin de phrase.
- Style des titres : anglais, court, nominal, format « sujet : précision » quand utile. Résumés : 2 à 3 phrases factuelles avec noms propres. Mots-clés : 6 à 8 termes en anglais.
- Taille des idées : en général 15 à 80 s (une idée = un point précis : un exemple, une affirmation, une étape).
- Structure de la vidéo : un premier récit (lignes 1-548) sur les effets de l'IA dans la vie quotidienne (art, arnaques, emplois, relations, santé mentale, environnement) ; puis une seconde histoire (à partir de la ligne 549) sur les études Anthropic (chantage de Kyle Johnson, instrumental convergence, supervision) ; à partir de la ligne 924 s'ouvre un classement « comment l'IA peut provoquer l'apocalypse » (Number 10, ...).

## Tranches
- Tranche 1 : lignes 1 à 923, 0 à 1845.04 s (~30,7 min), 43 segments (id 1 à 43). Passages d'idées cohérents ; durée min 16,9 s, max 77,5 s. Aucun passage douteux ; les « [music] » du speech sont conservés tels quels dans les textes. Prochaine étape : reprendre à la ligne 924 (« Number 10. A single cloud server goes dark... », début du classement des scénarios d'apocalypse), id 44.
