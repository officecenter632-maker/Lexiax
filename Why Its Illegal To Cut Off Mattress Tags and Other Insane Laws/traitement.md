# Traitement : DO_2lNje_bs

Vidéo : « Why Its Illegal To Cut Off Mattress Tags and Other Insane Laws »
Speech : 4213 lignes, 0,64 s à 8096,08 s (~135 min), langue en, source automatique (présence de « [music] » et de « >> » dans le texte, laissés tels quels).

## Journal

Départ : début de la vidéo (segments.json n'existait pas).

- Tranche 1 : lignes 1 à 912, 0 à 1719,44 s (~28,7 min), 39 segments (id 1 à 39). Vérification OK.
- Tranche 2 : lignes 913 à 1859, 1719,44 à 3646,08 s (~32 min), 48 segments (id 40 à 87). Vérification OK. Contenu : Chine impériale, Angleterre médiévale et Tudor, lois américaines (prohibition, flipper, danse), puis début d'une 2e vidéo-compilation : « 20 aliments interdits aux États-Unis » (un segment par numéro, 20 à 1) et « choses illégales en Russie » (n° 10 : produits importés).

Reprise à la ligne 1860 (un autre agent s'était arrêté après la tranche 2 ; son travail est vérifié OK et n'a pas été modifié).

- Tranche 3 : lignes 1860 à 2854, 3646,08 à 5484,96 s (~30,7 min), 50 segments (id 88 à 137). Vérification OK. Contenu : fin de la liste « choses illégales en Russie » (n° 9 blogs à n° 1 sous-vêtements en dentelle), « choses illégales du quotidien aux États-Unis » (chien sans licence, électronique jetée, Orem, Milwaukee, curfews, impôts, mots de passe Netflix, Bobby Unser, obstruction), puis « 20 choses légales aux États-Unis » (n° 20 singes à n° 4 conduire nu). Les coupures en milieu de ligne (titres de liste) sont marquées temps_estime = true.

## Décisions prises (pour qui reprend le travail)

- Une idée = un sujet précis : une loi bizarre (ex. Boulder, Reno, Akron), un cas judiciaire (Hattori, Johns Hopkins, Baltimore) ou une étape d'un raisonnement. Quand un cas est long, il est scindé en « les faits » et « le verdict / les suites ».
- Les titres de sujet (« Dirty tires. », « Don't share your password. ») tombent souvent au milieu d'une ligne : coupure faite au milieu de la ligne, temps estimé proportionnellement au nombre de mots, `temps_estime` = true pour les deux segments voisins. C'est pourquoi presque tous les segments sont marqués estimés.
- Titres en anglais, courts, de la forme « Lieu : sujet » ; résumé de 2 à 3 phrases factuelles en anglais (langue du speech) ; 5 à 10 mots-clés. Taille des idées : de quelques secondes à ~75 s, en général 30 à 60 s.
- Textes générés par script à partir de speech.json, mot pour mot ; la tranche se termine toujours en fin de ligne.
- Outils de travail (hors dépôt) : un script de génération lit des fichiers de définitions (fin de chaque segment = numéro de ligne, ou ligne + mot après lequel couper).

## Point d'arrêt

Tranche 3 terminée : lignes_traitees = 2854 (fin de « Number 4: driving naked », juste avant « And while driving, you might want to save yourself some money. Number three, using radar detectors »). Prochaine étape : reprise à la ligne 2855 (n° 3 : détecteurs de radar). La vidéo est une compilation de plusieurs sujets (lois absurdes, voyage dans le temps, aliments interdits aux USA, Russie) : un nouveau sujet commence souvent par un titre sans transition, à couper en milieu de ligne si besoin. Format des titres pour les listes numérotées : « Number N: sujet ».
