# Journal de traitement : dnmdZOEGXe8

Départ : début de la vidéo (aucun segments.json existant). Speech : 173 lignes, 814,08 s (≈ 13,6 min), langue « en », source manuelle.

## Tranches
- Tranche 1 : lignes 1 à 173 (0,16 s à 814,08 s, ≈ 13,6 min), 20 segments. La vidéo dure moins de 30 minutes : une seule tranche, qui est aussi la dernière. Remarques : 6 segments ont un temps estimé (voir plus bas).

## Méthode
- Lecture du speech par blocs de 60 lignes, puis découpage par idées (un point développé par segment, coupe au changement de sujet).
- Titres, résumés et mots-clés écrits en anglais (langue du speech).
- Le champ « texte » est extrait par script à partir de speech.json (points de coupe = numéro de ligne + nombre de mots), jamais retapé : il est donc mot pour mot.
- Quand une coupure tombe au milieu d'une ligne, le temps est estimé proportionnellement au nombre de mots (temps_estime = true sur les deux segments voisins).
- Vérification par script : JSON valide, nb_segments exact, id 1 à 20 sans trou, 5 à 10 mots-clés par segment, temps croissants et sans trou, avancement cohérent, textes bout à bout identiques aux lignes 1 à 173 (aux espaces près). Résultat : OK.

## Décisions
- Les transitions courtes sont rattachées à l'idée voisine (ex. « But the story certainly didn't end with Darya's death. » ouvre le segment 8).
- L'appel final vers une autre vidéo (lignes 172-173) est isolé dans son propre segment (20) pour ne pas polluer l'idée de conclusion (19).
- Titre de la vidéo : « Russia Closing 5 Hospital Due to PLAGUE OUTBREAK ».

## Bilan
- Segments : 20. Plus court : 9,92 s (segment 20). Plus long : 75,92 s (segment 4).
- Temps estimés (coupure au milieu d'une ligne) : segments 2-3 (ligne 17, frontière à 82,41 s), 13-14 (ligne 131, 612,8 s), 17-18 (ligne 163, 762,44 s).
- Speech douteux : texte de sous-titres avec quelques fautes de transcription gardées telles quelles (« righting the subtle drafts », « hundreds of people were forced into isolated », « thrive to thrive », « The virus acts like… » à propos d'une bactérie, ligne 33). Le contenu est un récit sensationnaliste présenté comme factuel ; il est segmenté tel quel, sans vérification des faits.
- Le titre parle de 5 hôpitaux, mais le speech ne mentionne explicitement que la fermeture de l'hôpital de Shelekhov.
- Problèmes rencontrés : aucun.
- Point d'arrêt : ligne 173 sur 173, « complet » = true. Prochaine étape : aucune.
