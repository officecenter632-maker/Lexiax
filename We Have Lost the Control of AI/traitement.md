# Journal de segmentation : Df0v8WoVscI (We Have Lost the Control of AI...)

## Départ
Début de la vidéo : segments.json n'existait pas. Speech : 177 lignes, 862,16 s (≈ 14,4 min), langue en, source manuelle.

## Tranches
- Tranche 1 : lignes 1 à 177, 0 à 862,16 s (14,4 min), 23 segments. Le speech entier dure moins de 30 minutes : une seule tranche, qui est aussi la dernière. Aucun temps estimé.

## Décisions prises
- Toutes les coupures tombent à une fin de ligne du speech : aucun temps estimé (temps_estime = false partout), donc pas de risque d'imprécision.
- Titres en anglais (langue du speech), courts, descriptifs. Résumés factuels de 2 à 3 phrases avec noms propres, chiffres et notions. 5 à 10 mots-clés par segment.
- Taille des idées : de 11 s à 77 s. Les transitions courtes sont rattachées à l'idée voisine ; l'anecdote du ticket de support (reward hacking) est séparée de sa définition et de la partie « tunnel vision / vitesse ».
- Le texte de chaque segment est la concaténation mot pour mot des lignes couvertes (séparées par un espace).

## Passages douteux
- Segments 18 et 19 : la phrase « No one knows what will happen if AI is / allowed to continue down its current path » est répartie sur deux lignes, entre la fin du segment 18 et le début du segment 19 (coupure à la fin de ligne pour éviter un temps estimé).
- Le speech contient des noms probablement issus de la transcription (David Robinson, Jacob Coxon) : conservés tels quels.
- Ligne 151 du speech : « programs regularly operate with oversight » (probablement « without ») : laissé mot pour mot.

## Bilan
- Segments : 23. Plus court : 11,3 s. Plus long : 76,9 s.
- Vérification (JSON valide, ids, champs, mots-clés, temps sans trou, avancement, textes = lignes 1 à 177) : OK.
- Statut : complet (lignes_traitees = nb_lignes_total = 177). Rien à reprendre.
