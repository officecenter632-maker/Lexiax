# Journal de traitement : sKfaPvntZuA

Départ : début de la vidéo (aucun segments.json existant). Speech : 213 lignes, 1017,0 s (≈ 17 min), langue « en », source manuelle.

## Tranches
- Tranche 1 : lignes 1 à 213 (0,16 s à 1017,0 s, ≈ 17 min), 24 segments. La vidéo dure moins de 30 minutes : une seule tranche, qui est aussi la dernière. Remarques : 4 segments ont un temps estimé (voir plus bas).

## Méthode
- Lecture du speech par blocs d'environ 55 lignes, puis découpage par idées (un point développé par segment, coupe au changement de sujet).
- Titres, résumés et mots-clés écrits en anglais (langue du speech).
- Le champ « texte » est extrait par script à partir de speech.json (points de coupe = numéro de ligne + nombre de mots), jamais retapé : il est donc mot pour mot.
- Quand une coupure tombe au milieu d'une ligne, le temps est estimé proportionnellement au nombre de mots (temps_estime = true sur les deux segments voisins).
- Vérification par script : JSON valide, nb_segments exact, id 1 à 24 sans trou, 5 à 10 mots-clés par segment, temps croissants et sans trou, avancement cohérent, textes bout à bout identiques aux lignes 1 à 213 (aux espaces près). Résultat : OK.

## Décisions
- Les phrases coupées entre deux lignes sont gardées dans la même idée : coupure au milieu de la ligne 72 (après « runaway train. », 335,08 s) et de la ligne 139 (après « treasuries. », 664,28 s).
- Les mentions de chiffres (tailles du carry trade, rendements, parts de réserves) sont gardées dans le résumé et les mots-clés pour faciliter la recherche.
- Titre de la vidéo : « Most Terrifying Financial Shift in the World Right Now ».

## Bilan
- Segments : 24. Plus court : 13,72 s (segment 24, conclusion et promotion). Plus long : 70,48 s (segment 5, levier et appels de marge).
- Temps estimés (coupure au milieu d'une ligne) : segments 7-8 (ligne 72, frontière à 335,08 s) et 15-16 (ligne 139, frontière à 664,28 s).
- Speech douteux : sous-titres manuels, pas d'erreur de transcription évidente. Quelques passages sont mal formulés dans la source et gardés tels quels (ex. ligne 53 « wiping out 505% of your investment »). Le contenu est un récit alarmiste présenté comme factuel (chiffres et événements de 2026 non vérifiés) ; il est segmenté tel quel, sans vérification des faits.
- Problèmes rencontrés : aucun.
- Point d'arrêt : ligne 213 sur 213, « complet » = true. Prochaine étape : aucune.
