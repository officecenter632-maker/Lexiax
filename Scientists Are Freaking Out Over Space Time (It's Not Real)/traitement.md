# Traitement : Scientists Are Freaking Out Over Space Time (It's Not Real) (c8dlJJuqcOQ)

Départ : début de la vidéo (aucun segments.json existant). speech.json : 5233 lignes, 10427.77 s (environ 2 h 54), anglais, sous-titres automatiques.

## Constat sur le contenu
- La vidéo est en réalité un enchaînement de plusieurs épisodes de The Infographics Show. Le premier (0 s à environ 970 s) est celui du titre : test de Bell cosmique, superdéterminisme, principe holographique. Il est suivi d'une liste « 50 incroyables faits sur l'espace » (de 972 s à environ 1654 s), puis d'un épisode sur ce qui arrive au corps dans l'espace (à partir de 1654 s). Les épisodes suivants seront notés ici.
- Les faits numérotés (50 à 1) sont regroupés par sujet (2 à 4 faits voisins par segment, un fait seul quand il est isolé).

## Méthode
- Lecture du speech par tranches de lignes, coupure par idées, puis construction avec un script qui prend les textes directement dans speech.json (jamais retapés) : les textes bout à bout redonnent exactement les lignes traitées.
- Les lignes de sous-titres se chevauchent d'environ 2 s : la ligne i est prononcée entre son debut et le debut de la ligne i+1. Une coupure en début de ligne prend donc le debut de cette ligne.
- Une coupure peut tomber au milieu d'une ligne (début de phrase) : le temps est alors estimé proportionnellement au nombre de mots de la ligne, et temps_estime vaut true pour les deux segments qui touchent cette coupure.
- Aux limites de tranche, le segment finit à la fin de la dernière ligne traitée (fin_traitee_s), et le premier segment de la tranche suivante commence à cet instant.
- Titres en français, résumés et mots-clés en anglais (langue du speech) ; les titres sont courts et descriptifs.
- Résumés de 2 à 3 phrases ; mots-clés : 5 à 10 par segment.

## Tranches
- Tranche 1 : lignes 1 à 840, 0 s à 1827.03 s (environ 30,5 min), 46 segments (#1 à #46). Vérification OK. Épisode du titre (#1 à #21), 50 faits sur l'espace (#22 à #42), début de l'épisode sur le corps dans l'espace (#43 à #46). Le dernier segment de la tranche se termine par « If you are ejected » (fin de ligne 840 : début de phrase qui appartient au segment suivant, à garder en tête).

- Tranche 2 : lignes 841 à 1831, 1827.03 s à 3653.61 s (environ 30,4 min), 33 segments (#47 à #79). Vérification OK. Contenu : fin de l'épisode sur le corps dans l'espace (#47 à #49), épisode sur les mystères que la science n'explique pas (#50 à #67 : origine de la vie, pieuvres galloises, moisissures visqueuses, champignon Texas/Japon, encéphalite léthargique, énergie et matière noires, gravité, temps, antimatière, sonoluminescence, Anticythère, manuscrit de Voynich), début de l'épisode sur la mort d'un trou noir et de l'univers (#68 à #79). Le dernier segment finit par « The » (début de phrase de la ligne 1831).

- Tranche 3 : lignes 1832 à 2738, 3653.61 s à 5479.47 s (environ 30,4 min), 30 segments (#80 à #109). Vérification OK. Contenu : fin de l'épisode sur la mort de l'univers par les trous noirs (#80 à #87), épisode sur la théorie de la simulation et Melvin Vopson (#88 à #105 : entropie, Minecraft, Descartes, Bostrom, double fente, mathématiques de la nature, limites du système), début d'un épisode sur l'explosion de l'amas MS0735.6+7421 (#106 à #109). Le dernier segment se termine par l'accroche « That's so 2005. » (la suite annonce une explosion encore plus grosse).

## Point d'arrêt
Dernière ligne traitée : 2738. Prochaine étape : reprendre à la ligne 2739 (« [music] Don't worry, we can do way better than a black hole that sucks in 300 suns ») avec l'id 110. Style des titres : français, courts, descriptifs ; résumés et mots-clés en anglais ; un segment fait en moyenne 40 à 80 s (11 s à 111 s).

## Reprise à la ligne 2739 (nouvel agent)
Départ : segments.json existant, complet=false, 2738 lignes traitées, 109 segments. Vérifié OK (ids, temps, textes bout à bout) avant reprise. Style conservé : titres en français, résumés et mots-clés en anglais, 5 à 10 mots-clés. Coupures possibles en milieu de ligne (temps estimé au prorata des mots, temps_estime=true).

- Tranche 4 : lignes 2739 à 3741, 5479.47 s à 7432.01 s (environ 32,5 min), 41 segments (#110 à #150). Vérification OK. Contenu : fin de l'épisode sur l'explosion de l'amas (détection X et radio, Ophiuchus, taille, Big Bang) (#110 à #118), épisode sur les bulles de rien et l'espace-temps (#119 à #130), épisode sur 'Oumuamua et l'hypothèse d'un vaisseau (#131 à #140), épisode sur K2-18b et la recherche de vie, dont l'histoire de Mars (#141 à #150). Le dernier segment finit à la fin de la ligne 3741 (« life on Mars. »).

## Point d'arrêt
Dernière ligne traitée : 3741. Prochaine étape : reprendre à la ligne 3742 (liste d'exoplanètes potentiellement habitables : HD 20794d, Gliese 12b, Kepler-62f, Kepler-442b, TRAPPIST-1) avec l'id 151.

- Tranche 5 : lignes 3742 à 4674, 7432.01 s à 9323.31 s (environ 31,5 min), 39 segments (#151 à #189). Vérification OK. Contenu : fin de l'épisode K2-18b (exoplanètes candidates, spectroscopie, critiques, futurs télescopes) (#151 à #158), épisode sur le signal Wow et le Big Ear de John Kraus (#159 à #176 : SETI, raie de l'hydrogène 1420 MHz, hypothèses comètes d'Antonio Paris et magnétars), début d'un épisode sur les trous noirs (#177 à #189 : définition, histoire, Cygnus X-1, année-lumière, formation, trous de ver, idées reçues, classification). Remarques : 31 segments sur 39 ont un temps estimé (coupures en milieu de ligne). Lignes 4411 à 4412 : le texte automatique est tronqué (« science behind black / need to discuss »), gardé tel quel. Le dernier segment finit à la fin de la ligne 4674 (« Stellar mass black holes. »), qui annonce le segment suivant.

## Point d'arrêt
Dernière ligne traitée : 4674. Prochaine étape : reprendre à la ligne 4675 (« Not all stars that go supernova end up as black holes ») avec l'id 190 : trous noirs stellaires, puis les autres catégories.
