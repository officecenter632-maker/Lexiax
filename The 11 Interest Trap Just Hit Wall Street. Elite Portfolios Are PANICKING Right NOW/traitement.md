# Traitement : YVFA79OhlU0

Départ : début de la vidéo (aucun segments.json existant).

## Tranches
- Tranche 1 (unique) : lignes 1 à 213 sur 213, 0,16 s à 928,96 s (environ 15,5 minutes), 30 segments. Le speech est plus court que 30 minutes, donc une seule tranche. Aucune coupure au milieu d'une ligne : temps_estime est false partout.

## Méthode
- Lecture du speech en deux blocs (lignes 1 à 100, puis 101 à 213), puis découpage par idées en plages de lignes entières (changement de sujet = coupure). Les transitions courtes sont rattachées à l'idée voisine.
- Titre, résumé (2 à 3 phrases) et 6 à 7 mots-clés en anglais, langue du speech.
- segments.json généré par script : textes mot pour mot (lignes jointes par un espace), debut d'un segment = fin du précédent.
- Vérification par script : JSON valide, id continus, temps sans trou, mots-clés 5 à 10, textes bout à bout identiques aux lignes 1 à 213.

## Bilan
- 30 segments ; plus court 7,7 s (id 30, appel à l'action final), plus long environ 55 s.
- Passages douteux : aucun temps estimé ; les temps viennent de sous-titres manuels. Un trou de 0,96 s dans le speech entre les lignes 163 et 164 (713,36 à 714,32 s) tombe à l'intérieur du segment 22 : il n'y a donc pas de trou entre segments.
- Le titre de la vidéo contient « 11% » ; le dossier du dépôt s'appelle « 11 » sans le signe pourcentage.
- Point d'arrêt : complet (ligne 213). Rien à reprendre.
