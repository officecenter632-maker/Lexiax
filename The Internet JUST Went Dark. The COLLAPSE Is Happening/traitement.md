# Traitement : The Internet JUST Went Dark. The COLLAPSE Is Happening (_huy9jU9UAA)

Départ : début de la vidéo (aucun segments.json existant). Speech : 554 lignes, 2161,76 s (≈36 min), donc 2 tranches.

## Décisions de méthode
- Le speech est un récit fictionnel jour par jour (Nate Kessler, Cleveland). Un segment = un épisode ou un point précis (une journée, ou une scène d'une journée si elle mélange plusieurs points). Titres de la forme « Day N: événement ».
- Les en-têtes « Day N » appartiennent au segment qu'ils ouvrent. Les journées très courtes ne sont fusionnées avec la suivante que si le sujet est le même (Day 41-47).
- Textes assemblés par script depuis speech.json, mot pour mot. Coupures uniquement en fin de ligne dans cette tranche.
- Titres, résumés et mots-clés en anglais (langue du speech).

## Tranches
- Tranche 1 : lignes 1 à 464 sur 554, 0,16 à 1824,08 s (≈30,4 min), 44 segments, aucun temps estimé. Coupure en fin de journée du récit (fin de Day 58, avant « Day 60 »).
  Point d'arrêt : ligne 464. Prochaine étape : reprendre à la ligne 465 (« Day 60 ») avec l'id 45.
- Tranche 2 : lignes 465 à 554 sur 554, 1824,08 à 2161,76 s (≈5,6 min), 10 segments (id 45 à 54), aucun temps estimé. Dernière tranche : complet = true.

## Bilan final
- 54 segments au total ; plus court 11,5 s (segment 54, promo de fin), plus long 80,4 s (segment 19, Day 9 : égouts, sauvetage de l'insuline, exutoires pluviaux).
- Aucune coupure en milieu de ligne : tous les `temps_estime` sont à false. Les temps des sous-titres restent approximatifs.
- Segments courts fusionnés : Day 41-47 (segment 40) et Days 80-83 (segment 50) regroupent deux petites journées liées.
- Vérification script : JSON valide, id 1 à 54, 5 à 10 mots-clés, temps croissants sans trou, textes bout à bout = lignes 1 à 554, lignes_traitees = nb_lignes_total : OK.
- Le début (segments 1 à 44) n'a pas été modifié par la tranche 2.
- Statut : complet = true. Prochaine étape : aucune.
