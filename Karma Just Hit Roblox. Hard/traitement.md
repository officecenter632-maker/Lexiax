# Journal de traitement : IpheDQ5v6oQ

Départ : début de la vidéo (aucun segments.json existant). Speech : 204 lignes, 894,13 s (≈ 14,9 min), langue « en », source manuelle.

## Tranches
- Tranche 1 : lignes 1 à 204 (0,16 s à 894,13 s, ≈ 14,9 min), 26 segments. La vidéo dure moins de 30 minutes : une seule tranche, qui est aussi la dernière. Remarques : aucun temps estimé.

## Méthode
- Lecture du speech par blocs d'environ 55 lignes, puis découpage par idées (un point développé par segment, coupe au changement de sujet).
- Titres, résumés et mots-clés écrits en anglais (langue du speech).
- Le champ « texte » est extrait par script à partir de speech.json (points de coupe = numéro de ligne + nombre de mots), jamais retapé : il est donc mot pour mot.
- Toutes les coupures tombent en début de ligne : temps_estime = false partout.
- Vérification par script : JSON valide, nb_segments exact, id 1 à 26 sans trou, 5 à 10 mots-clés par segment, temps croissants et sans trou, avancement cohérent, textes bout à bout identiques aux lignes 1 à 204 (aux espaces près). Résultat : OK.

## Décisions
- Les phrases de transition courtes sont rattachées à l'idée qu'elles introduisent (ex. « And that's why the empire is collapsing. » ouvre le segment 3, « Now Roblox is panicking. » ouvre le segment 23, « They didn't have a choice. » ouvre le segment 21).
- Les allégations (lawsuits, plainte FTC, exploitation) sont résumées comme des affirmations de la vidéo, avec les démentis de Roblox quand le speech les mentionne.
- L'appel final vers une autre vidéo (lignes 202-204) est isolé dans son propre segment (26).
- Titre de la vidéo : « Karma Just Hit Roblox. Hard. ».

## Bilan
- Segments : 26. Plus court : 15,01 s (segment 26, promotion). Plus long : 56,88 s (segment 15, deux piliers du modèle économique).
- Temps estimés : aucun.
- Speech douteux : sous-titres manuels, quelques fautes de ponctuation gardées telles quelles (« sitearen't », « running scared.These lawsuits as a legitimate », « The entire might be changing forever », « bypass the bands »). Les chiffres et événements de 2026 (cours de bourse, plaintes, provisions) sont ceux de la vidéo, non vérifiés ; le ton est à charge contre Roblox.
- Problèmes rencontrés : aucun. Le dossier s'appelle « Karma Just Hit Roblox. Hard » (sans le point final du titre).
- Point d'arrêt : ligne 204 sur 204, « complet » = true. Prochaine étape : aucune.
