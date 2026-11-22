# Traitement : eNzaPa9f0Ks

Départ : début de la vidéo (aucun segments.json existant).

## Tranches
- Tranche 1 (unique) : lignes 1 à 197 sur 197, 0,32 s à 833,03 s (environ 13,9 minutes), 28 segments. Le speech est plus court que 30 minutes, donc une seule tranche. Aucune coupure au milieu d'une ligne : temps_estime est false partout.

## Méthode
- Lecture du speech par blocs de 100 lignes, puis découpage par idées en plages de lignes entières (sujet qui change = coupure). Les transitions courtes sont rattachées à l'idée voisine.
- Titre, résumé (2 à 3 phrases) et 5 à 7 mots-clés en anglais, langue du speech.
- segments.json généré par script : textes mot pour mot (lignes jointes par un espace), debut d'un segment = fin du précédent.
- Vérification par script : JSON valide, id continus, temps sans trou, mots-clés 5 à 10, textes bout à bout identiques aux lignes 1 à 197.

## Bilan
- 28 segments ; plus court 5,3 s (id 27, conclusion), plus long 59,2 s.
- Passages douteux : aucun temps estimé ; les temps viennent de sous-titres manuels. Le segment 17 réunit deux points proches (buybacks et statut de monnaie de réserve) car le second est une conclusion de deux lignes.
- Point d'arrêt : complet (ligne 197). Rien à reprendre.
