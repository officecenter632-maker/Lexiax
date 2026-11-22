# Traitement : DO_2lNje_bs

Vidéo : « Why Its Illegal To Cut Off Mattress Tags and Other Insane Laws »
Speech : 4213 lignes, 0,64 s à 8096,08 s (~135 min), langue en, source automatique (présence de « [music] » et de « >> » dans le texte, laissés tels quels).

## Journal

Départ : début de la vidéo (segments.json n'existait pas).

- Tranche 1 : lignes 1 à 912, 0 à 1719,44 s (~28,7 min), 39 segments (id 1 à 39). Vérification OK.
- Tranche 2 : lignes 913 à 1859, 1719,44 à 3646,08 s (~32 min), 48 segments (id 40 à 87). Vérification OK. Contenu : Chine impériale, Angleterre médiévale et Tudor, lois américaines (prohibition, flipper, danse), puis début d'une 2e vidéo-compilation : « 20 aliments interdits aux États-Unis » (un segment par numéro, 20 à 1) et « choses illégales en Russie » (n° 10 : produits importés).

Reprise à la ligne 1860 (un autre agent s'était arrêté après la tranche 2 ; son travail est vérifié OK et n'a pas été modifié).

- Tranche 3 : lignes 1860 à 2854, 3646,08 à 5484,96 s (~30,7 min), 50 segments (id 88 à 137). Vérification OK. Contenu : fin de la liste « choses illégales en Russie » (n° 9 blogs à n° 1 sous-vêtements en dentelle), « choses illégales du quotidien aux États-Unis » (chien sans licence, électronique jetée, Orem, Milwaukee, curfews, impôts, mots de passe Netflix, Bobby Unser, obstruction), puis « 20 choses légales aux États-Unis » (n° 20 singes à n° 4 conduire nu). Les coupures en milieu de ligne (titres de liste) sont marquées temps_estime = true.

Reprise à la ligne 2855 (un autre agent s'était arrêté après la tranche 3 ; son travail est vérifié OK et n'a pas été modifié ; mêmes conventions de titres, de résumés et de coupures).

- Tranche 4 : lignes 2855 à 3803, 5484,96 à 7279,48 s (~30 min), 57 segments (id 138 à 194). Vérification OK. Contenu : fin de « 20 choses légales aux États-Unis » (n° 3 détecteurs de radar à n° 1 étiquette de matelas), « 10 choses les plus illégales jamais inventées » (n° 10 gilets pare-balles à n° 1 armes biologiques, 2 segments quand le sujet a deux temps), « choses autrefois légales » (travail des enfants, prostitution, conduite en état d'ivresse, mercenaires, bataille de Khasham), puis début de « lois illégales en Corée du Nord » (voyage, films et musique, appels internationaux, vêtements, coupes de cheveux). Coupure de tranche à la fin de la ligne 3803 (fin de l'idée sur les coupes de cheveux, juste avant les piercings). Plus courts : segments de transition ou de suite courte (9 à 17 s) ; plus long : 75 s. Temps estimés (coupes en milieu de ligne) : presque tous les segments, comme avant.

- Tranche 5 (finale) : lignes 3804 à 4213, 7279,48 à 8096,08 s (~13,6 min), 30 segments (id 195 à 224). Vérification OK. Contenu : fin de « lois illégales en Corée du Nord » (piercings, interdiction de sourire pendant le deuil, internet et Kwangmyong, ordinateurs et téléphones, photographie, conduite et transports, coupures d'électricité, micro-ondes, religion, travail attribué à vie, semaine de 48 h, alcool, impossibilité de quitter le pays, Otto Warmbier, sarcasme et critique du régime, nom du pays). Un segment par sujet, 2 segments quand le sujet a deux temps.

## Décisions prises (pour qui reprend le travail)

- Une idée = un sujet précis : une loi bizarre (ex. Boulder, Reno, Akron), un cas judiciaire (Hattori, Johns Hopkins, Baltimore) ou une étape d'un raisonnement. Quand un cas est long, il est scindé en « les faits » et « le verdict / les suites ».
- Les titres de sujet (« Dirty tires. », « Don't share your password. ») tombent souvent au milieu d'une ligne : coupure faite au milieu de la ligne, temps estimé proportionnellement au nombre de mots, `temps_estime` = true pour les deux segments voisins. C'est pourquoi presque tous les segments sont marqués estimés.
- Titres en anglais, courts, de la forme « Lieu : sujet » ; résumé de 2 à 3 phrases factuelles en anglais (langue du speech) ; 5 à 10 mots-clés. Taille des idées : de quelques secondes à ~75 s, en général 30 à 60 s.
- Textes générés par script à partir de speech.json, mot pour mot ; la tranche se termine toujours en fin de ligne.
- Outils de travail (hors dépôt) : un script de génération lit des fichiers de définitions (fin de chaque segment = numéro de ligne, ou ligne + mot après lequel couper).

## Point d'arrêt

Tranche 3 terminée : lignes_traitees = 2854 (fin de « Number 4: driving naked », juste avant « And while driving, you might want to save yourself some money. Number three, using radar detectors »). Prochaine étape : reprise à la ligne 2855 (n° 3 : détecteurs de radar). La vidéo est une compilation de plusieurs sujets (lois absurdes, voyage dans le temps, aliments interdits aux USA, Russie) : un nouveau sujet commence souvent par un titre sans transition, à couper en milieu de ligne si besoin. Format des titres pour les listes numérotées : « Number N: sujet ».


Tranche 4 terminée : lignes_traitees = 3803 (fin de « North Korea: official haircut rules for women », juste avant « Oh, and while we're on the topic of prohibited personal styles, piercings are also banned »). Prochaine étape : reprise à la ligne 3804 (Corée du Nord : piercings, interdiction de sourire pendant le deuil, internet), id suivant 195. Reste 410 lignes, environ 13 minutes (7279 à 8096 s) : une seule tranche finale, puis passer « complet » à true et ajouter le bilan final (méthode, nombre de segments, plus court et plus long, passages douteux).

## Bilan final

- Terminé : lignes_traitees = 4213 sur 4213, complet = true, 224 segments (id 1 à 224), couvrant 0,64 à 8096,08 s (~135 min). Reprise faite à la ligne 2855 (tranches 4 et 5) ; les 137 premiers segments n'ont pas été modifiés.
- Méthode : lecture du speech par blocs d'environ 200 lignes, un segment par idée (un sujet précis, scindé en deux quand il a deux temps : faits puis suites), titres « Number N: sujet » pour les listes numérotées, résumés et mots-clés en anglais. Les textes sont générés par script à partir de speech.json (mot pour mot) ; les temps en milieu de ligne sont estimés proportionnellement au nombre de mots.
- Durées : plus court 6,6 s (id 10), 6,75 s (id 195) ; plus long 75,1 s (id 27), 75,0 s (id 47). Temps estimés : 202 segments sur 224.
- Passages douteux : le speech est un sous-titrage automatique avec des erreurs (ex. « practices or tax associated with any religion » à la ligne 4045, sans doute « texts » ; « abanned » ; « meet out » ; « Hell » prononcé tel quel), conservées telles quelles dans les textes ; les marqueurs « [music] » et « >> » sont conservés. Des lignes se chevauchent légèrement, d'où de petits écarts possibles entre les temps estimés et la parole réelle.
- Problèmes rencontrés : aucun. Dernière vérification (script) : JSON valide, nb_segments exact, id 1 à 224, champs et 5 à 10 mots-clés, temps croissants sans trou, avancement cohérent, textes bout à bout identiques aux lignes 1 à 4213 : OK.