# Traitement : Renting vs Buying - Follow The Math! (DRP7tRXts0Q)

## Départ
Début de la vidéo : aucun segments.json existant. Speech manuel en anglais, 194 lignes, 0,16 s à 827,52 s (environ 13,8 min).

## Tranches
- Tranche 1 : lignes 1 à 194 (0,16 à 827,52 s, environ 13,8 min), 23 segments. Le speech tient en une seule tranche (moins de 30 min). Remarques : 2 segments ont temps_estime à true.

## Décisions
- Titres courts en anglais (langue du speech), résumés factuels de 2 à 3 phrases, 5 à 10 mots-clés.
- Textes recopiés par script depuis speech.json, mot pour mot (espaces d'origine conservées). Les fautes d'origine sont conservées, par exemple « mortgagrs » (ligne 23) et « Prince Index » (ligne 160).
- Une seule coupure au milieu d'une ligne : ligne 193, après « can it last? », au mot près, avec temps estimé proportionnellement au nombre de mots. Elle sépare la question de clôture (segment 22) de l'invitation vers la vidéo suivante (segment 23).
- Transitions courtes rattachées à l'idée voisine : ligne 82 ouvre l'effet de verrouillage des taux, lignes 107 et 108 restent avec le coût des intérêts.

## Bilan
- Méthode : lecture du speech en deux paquets de 100 lignes, découpage par idées, génération de segments.json par script (positions de coupure en ligne et mot), vérification par script (JSON valide, id continus, temps croissants et sans trou, textes bout à bout identiques aux lignes 1 à 194, avancement cohérent).
- Nombre de segments : 23. Plus court : 4,6 s (id 22). Plus long : 68,5 s (id 11).
- Temps estimés (temps_estime = true) : segments 22 et 23.
- Passages douteux : chiffres et noms (taux de 6,71 %, 34 puis 14 millions de déclarants, valeurs de patrimoine médian) repris tels quels du speech, sans vérification externe ; les temps des lignes sont ceux des sous-titres YouTube.
- Point d'arrêt : ligne 194 sur 194, complet = true. Prochaine étape : aucune.
