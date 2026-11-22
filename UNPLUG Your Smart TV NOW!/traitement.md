# Traitement : UNPLUG Your Smart TV NOW! (JhuL2Yr-tvs)

## Départ
Début de la vidéo : aucun segments.json existant. Speech manuel en anglais, 214 lignes, 0,24 s à 947,44 s (environ 15,8 min).

## Tranches
- Tranche 1 : lignes 1 à 214 (0 à 947,44 s, environ 15,8 min), 34 segments. Le speech tient en une seule tranche (moins de 30 min). Remarques : aucune coupure au milieu d'une ligne, donc temps_estime est false partout.

## Décisions
- Titres courts en anglais (langue du speech), résumés factuels de 2 à 3 phrases, 5 à 10 mots-clés.
- Textes recopiés par script depuis speech.json (lignes jointes par une espace), donc mot pour mot (fautes d'origine conservées, par exemple « IThe » ligne 35, « miniscule » ligne 194).
- Transitions courtes rattachées à l'idée voisine : lignes 41 à 44 avec Vizio, 67 avec Huntley, 128 avec le consentement, 152 à 154 avec le modèle économique.
- Lignes 170 à 172 (razor and blades) fusionnées avec les résultats financiers de Vizio.

## Bilan
- Méthode : lecture du speech par paquets de 60 lignes, découpage par idées aux fins de lignes, génération de segments.json par script, vérification par script (JSON valide, id continus, temps croissants et sans trou, textes bout à bout identiques aux lignes 1 à 214, avancement cohérent).
- Nombre de segments : 34. Plus court : 12,2 s (id 34). Plus long : 70,4 s (id 26).
- Temps estimés : aucun.
- Passages douteux : ligne 35 commence par « IThe » (faute du sous-titre) ; les temps des lignes sont ceux des sous-titres YouTube (approximatifs).
- Point d'arrêt : ligne 214 sur 214, complet = true. Prochaine étape : aucune.
