# Journal de traitement : wcZ7q219JS8

Départ : début de la vidéo (aucun segments.json existant). Speech : 501 lignes, 2010,03 s (≈ 33,5 min), langue « en », source manuelle. La vidéo est un compte à rebours de 50 faits : les marqueurs « 50. », « 49. »… sont des lignes à part dans le speech.

## Tranches
- Tranche 1 : lignes 1 à 445 (0,16 s à 1789,76 s, ≈ 29,8 min), 47 segments (id 1 à 47). Fin de tranche choisie à la fin du fait 7 (Pilecki sous le régime communiste), avant la transition « Meanwhile, the legal reckoning… » qui ouvre le fait 6. Aucun temps estimé. Vérification : OK.

## Méthode et décisions de style (à suivre pour la tranche suivante)
- Lecture du speech par blocs d'environ 75 lignes, puis découpage par idées : en général un segment par fait numéroté. Les faits qui mélangent deux points sont scindés (faits 46 et 45).
- Le marqueur numérique (« 43. ») appartient au segment qu'il ouvre, avec le titre « Fact N: … ». Les phrases de transition qui précèdent un marqueur (ex. « But of all the symbols at Auschwitz… ») sont rattachées au fait suivant, qu'elles introduisent.
- Titres en anglais, courts, sous la forme « Fact N: sujet » (les segments sans numéro ont un titre descriptif). Résumés de 2 à 3 phrases avec noms, dates et chiffres du speech ; 8 mots-clés par segment.
- Le champ « texte » est extrait par script à partir de speech.json (points de coupe = numéro de ligne + nombre de mots), jamais retapé : il est donc mot pour mot.
- Taille des idées : 14 à 69 s ; le segment d'introduction (lignes 1-3) fait environ 14 s.
- Outils : /home/claude/build_tr.py (ajoute une tranche à segments.json), verify_gen.py (vérification).

## Remarques
- Speech : sous-titres manuels, quelques fautes gardées telles quelles (« Auschwirtz », « beaurocracy », « Högestrom », « surgical sewed », « they just could accept », « In , Romani »).
- Sujet : histoire de la Shoah, contenu documentaire et factuel. Les résumés suivent ce que dit la vidéo, sans vérification des faits.
- Point d'arrêt : ligne 445 sur 501, « complet » = false. Prochaine étape : reprendre à la ligne 446 (« Meanwhile, the legal reckoning for what happened at Auschwitz kept grinding forward… », début du fait 6), id 48.
