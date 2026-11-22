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

## Point d'arrêt
Dernière ligne traitée : 1831. Prochaine étape : reprendre à la ligne 1832 (« universe is like a massive city where black holes are the only immortal residents ») avec l'id 80. Style des titres : français, courts, descriptifs ; résumés et mots-clés en anglais ; un segment fait en moyenne 40 à 80 s (11 s à 111 s).
