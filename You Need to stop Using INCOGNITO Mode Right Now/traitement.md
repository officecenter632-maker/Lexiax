# Traitement : 5153vDFmwBs

Départ : début de la vidéo (aucun segments.json existant).

## Tranches
- Tranche 1 (unique) : lignes 1 à 186 sur 186, 0,16 s à 807,74 s (environ 13,5 minutes), 21 segments. Le speech est plus court que 30 minutes, donc une seule tranche. Aucune coupure au milieu d'une ligne : temps_estime est false partout.

## Méthode
- Lecture du speech en deux blocs (lignes 1 à 100, puis 101 à 186), puis découpage par idées en plages de lignes entières (changement de sujet = coupure). Les transitions courtes sont rattachées à l'idée voisine.
- Titre, résumé (2 à 3 phrases) et 6 à 7 mots-clés en anglais, langue du speech.
- segments.json généré par script : textes mot pour mot (lignes jointes par un espace), debut d'un segment = fin du précédent.
- Vérification par script : JSON valide, id continus, temps sans trou, mots-clés 5 à 10, textes bout à bout identiques aux lignes 1 à 186.

## Bilan
- 21 segments ; plus court 11,3 s (id 21, appel à l'action final), plus long 55,3 s (id 18, termes du règlement de décembre 2023).
- Passages douteux : aucun temps estimé ; les temps viennent de sous-titres manuels. Quelques fautes du sous-titre sont conservées mot pour mot (par exemple « after your because » à la ligne 97).
- Point d'arrêt : complet (ligne 186). Rien à reprendre.
