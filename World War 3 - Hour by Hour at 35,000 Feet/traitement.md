# Traitement : World War 3 - Hour by Hour at 35,000 Feet (qERTeNo8kNI)

Départ : début de la vidéo (aucun segments.json existant).

## Journal par tranche
- Tranche 1 : lignes 1 à 323 (sur 323), 0,16 s à 1387,20 s (environ 23,1 min), 36 segments. Le speech entier tient dans une seule tranche (moins de 30 minutes).

## Méthode suivie
- Speech lu par morceaux (lignes 1-66, 67-132, 133-198, 199-262, 263-323), sous-titres manuels en anglais. Le speech est un récit dramatisé (fiction) heure par heure ; les résumés décrivent les événements racontés, sans y ajouter de commentaire.
- Segmentation par idées : une scène ou une étape du récit (ou un point explicatif : EMP, goggles PLZT, règle 7/10, protection factor) par segment. Les en-têtes horaires (« T+14 Minutes ») sont rattachés à la scène qui suit, sauf quand ils terminent une ligne dont le début appartient à la scène précédente.
- Toutes les coupures tombent en fin de ligne du speech : aucun temps estimé (temps_estime false partout).
- Le texte de chaque segment est l'assemblage mot pour mot des lignes correspondantes (script), sans correction.
- Titres, résumés (2 à 3 phrases) et mots-clés (8 par segment) en anglais, langue du speech.
- Vérification par script : JSON valide, id 1 à 36 sans trou, temps croissants et sans trou, avancement cohérent, textes bout à bout identiques aux lignes 1 à 323.

## Bilan
- Segments : 36. Plus court : 10,40 s (segment 36, outro). Plus long : 70,80 s (segment 11, EMP et Starfish Prime).
- Passages à temps estimés : aucun.
- Décisions : les scènes de blessés des lignes 209-231 sont découpées en trois segments (rangée 17, rangée 22, bilan et reprise d'action de Tony) pour garder une idée par segment. Les en-têtes horaires en fin de ligne (ligne 152 « 3:34 P.M. », ligne 275 « 3:00 A.M. ») restent à la fin du segment dont la ligne est issue, pour ne pas couper une ligne.
- Passages douteux : sous-titres manuels avec des coquilles d'origine conservées telles quelles (« ThenTony » ligne 209, « IHe stands up » ligne 231, « coming back. » ligne 62, « their back on the ground » ligne 2). Les données du récit (distances, durées, chiffres) sont reprises du speech et non vérifiées.
- Problèmes rencontrés : aucun. Un dossier voisin (« World War 3 Protocol… ») appartient à une autre vidéo et n'a pas été ouvert.
- État : complet, lignes_traitees = nb_lignes_total = 323.
