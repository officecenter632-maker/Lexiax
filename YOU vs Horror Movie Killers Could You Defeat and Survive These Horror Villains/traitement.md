# Traitement : YOU vs Horror Movie Killers || Could You Defeat and Survive These Horror Villains (dg6bbyhFjhc)

Speech : 3354 lignes, 6980,17 s (~116 min), langue en, sous-titres automatiques (texte approximatif, traduit/dégradé, quelques mots ukrainiens parasites).

## Décisions
- Format de la vidéo : série « You vs. », un monstre/tueur par partie (scénario d'ouverture, origine, pouvoirs, comment le vaincre). Une idée = un volet de ce plan (ex. origine, armure, point faible, une arme, un piège).
- Les coupures tombent TOUJOURS en fin de ligne du speech (les lignes de sous-titres sont courtes, ~2 s). Une idée qui commence au milieu d'une ligne est rattachée au segment où la ligne contient l'essentiel ; donc temps_estime = false partout et les textes se recollent exactement.
- Titres, résumés et mots-clés en anglais (langue du speech). Les noms de films sont corrigés dans les titres/résumés quand le speech est déformé (ex. « Sorrow Configuration » = Lament Configuration) ; le champ texte reste mot pour mot.

## Journal
- Départ : début de la vidéo (aucun segments.json existant).
- Tranche 1 : lignes 1 à 898 (sur 3354), 0 à 1834,89 s (~30,6 min), 39 segments (id 1 à 39). Xenomorph (Alien), Babadook, Leatherface, début de Pinhead (jusqu'à la tolérance à la douleur). Vérification OK.

- Tranche 2 : lignes 899 à 1731 (sur 3354), jusqu'à 3599,18 s (couvre 1834,89 à 3599,18 s, ~29,4 min), 36 segments (id 40 à 75). Fin de Pinhead, Michael Myers, Pennywise, début d'Annabelle (jusqu'à l'attaque physique). Vérification OK.

- Tranche 3 : lignes 1732 à 2615 (sur 3354), de 3599,18 à 5447,00 s (~30,8 min), 36 segments (id 76 à 111). Fin d'Annabelle (AA-12, XL18), Slenderman, Chucky, Valak, début de Samara (jusqu'à sa mort dans le puits). Vérification OK.

- Tranche 4 (dernière) : lignes 2616 à 3354 (sur 3354), de 5447,00 à 6980,17 s (~25,6 min), 31 segments (id 112 à 142). Fin de Samara (The Ring), Ghostface (Scream), Jigsaw (Saw), conclusion. Vérification OK, complet = true.

## Bilan final
- Méthode : lecture du speech par blocs de ~300 lignes ; plages de lignes choisies à la main pour chaque idée (titre, résumé, mots-clés) ; un script assemble `texte` en recollant les lignes mot pour mot et calcule debut/fin (debut = fin du segment précédent) ; script de vérification avant chaque push (JSON valide, id, 5 à 10 mots-clés, temps croissants sans trou, avancement, textes bout à bout = lignes 1 à N du speech).
- Nombre de segments : 142 pour 3354 lignes (6980,17 s). Plus court : 10,4 s (segment 142, outro). Plus long : 91,2 s (segment 140, solution du piège de la balance).
- Temps estimés : aucun (temps_estime = false partout), car toutes les coupures sont faites en fin de ligne. Conséquence : quelques segments commencent ou finissent par quelques mots qui appartiennent à l'idée voisine (amorces de transition type « So how are you going to »).
- Passages douteux du speech (sous-titres automatiques, texte conservé tel quel) : mots ukrainiens parasites (ex. lignes 231, 1167, 1214, 1451, 2196, 2219, 2226, 2657) ; noms déformés (« Balak » pour Valak, « Designer/Constructor » pour Jigsaw, « Pilka » pour Saw, « Sorrow Configuration » pour Lament Configuration, « Sante/Thorne » pour Thorn, « face grab » pour facehugger, « lump » pour chestburster, « Enda/Kulanna », « Hamahar Slimmer »). Les titres, résumés et mots-clés utilisent les noms corrects des films.
- Contenu sensible dans le speech : humour noir sur les tortures du film Saw (segment 140) et mention de violences dans l'origine de Samara et d'Enda ; résumés factuels et neutres.
- Problèmes rencontrés : aucun.

## Point d'arrêt
- Dernière ligne traitée : 3354 / 3354. complet = true. Rien à reprendre.
