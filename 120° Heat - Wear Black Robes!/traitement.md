# Traitement : H7buemdxULY

Départ : début de la vidéo (aucun segments.json existant).

## Tranches
- Tranche 1 (unique) : lignes 1 à 200 sur 200, 0,08 s à 856,72 s (environ 14,3 minutes), 27 segments. Le speech est plus court que 30 minutes, donc une seule tranche. Aucune coupure au milieu d'une ligne : temps_estime est false partout.

## Méthode
- Lecture du speech en deux blocs (lignes 1 à 110, puis 111 à 200), puis découpage par idées en plages de lignes entières (changement de sujet = coupure). Les transitions courtes sont rattachées à l'idée voisine.
- Titre, résumé (2 à 3 phrases) et 6 à 7 mots-clés en anglais, langue du speech.
- segments.json généré par script : textes mot pour mot (lignes jointes par un espace), debut d'un segment = fin du précédent.
- Vérification par script : JSON valide, id continus, temps sans trou, mots-clés 5 à 10, textes bout à bout identiques aux lignes 1 à 200.

## Bilan
- 27 segments ; plus court 9,9 s (id 27, appel à l'action final), plus long 59,3 s (id 24, résultats de l'expérience).
- Passages douteux : aucun temps estimé ; les temps viennent de sous-titres manuels.
- Point d'arrêt : complet (ligne 200). Rien à reprendre.
