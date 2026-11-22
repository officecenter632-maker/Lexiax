# Journal de traitement : wcZ7q219JS8

Départ : début de la vidéo (aucun segments.json existant). Speech : 501 lignes, 2010,03 s (≈ 33,5 min), langue « en », source manuelle. La vidéo est un compte à rebours de 50 faits : les marqueurs « 50. », « 49. »… sont des lignes à part dans le speech.

## Tranches
- Tranche 1 : lignes 1 à 445 (0,16 s à 1789,76 s, ≈ 29,8 min), 47 segments (id 1 à 47). Fin de tranche choisie à la fin du fait 7 (Pilecki sous le régime communiste), avant la transition « Meanwhile, the legal reckoning… » qui ouvre le fait 6. Aucun temps estimé. Vérification : OK. Poussée : commit beb6059.
- Tranche 2 : lignes 446 à 501 (1789,76 s à 2010,03 s, ≈ 3,7 min), 7 segments (id 48 à 54), dernière tranche. Faits 6 à 1 et conclusion avec la promotion de la vidéo « How Nazi Gas Chambers Actually Worked ». Aucun temps estimé. Vérification : OK.

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
- Le dernier segment (54) isole la phrase de conclusion et la promotion finale (lignes 499-501) du fait 1.

## Bilan final
- Segments : 54 (47 + 7). Plus court : 14,19 s (segment 54, conclusion et promotion). Plus long : 69,04 s (segment 25, évasion de Vrba et Wetzler).
- Temps estimés : aucun, toutes les coupures tombent en début de ligne.
- Speech douteux : voir la liste de fautes de sous-titres ci-dessus, gardées telles quelles. Aucune vérification des faits historiques.
- Problèmes rencontrés : aucun.
- Point d'arrêt : ligne 501 sur 501, « complet » = true. Prochaine étape : aucune.
