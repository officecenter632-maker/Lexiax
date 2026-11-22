# Journal de segmentation : Insane Pain Facts, From Phantom Limbs to Brain Freeze (zeVq8Pt2JCc)

Speech : 6947 lignes, 0.32 s à 13672.56 s (≈ 3 h 48), langue en, sous-titres automatiques (sans ponctuation fiable, balises [music] conservées dans les textes). Tranches d'environ 30 min : ≈ 8 tranches prévues.

## Décisions et style
- Départ : début de la vidéo (aucun segments.json existant).
- Structure de la vidéo : succession de listes numérotées (« Number N ») : liste de 20 faits (lignes 1 à 409), puis liste de 50 faits (à partir de la ligne 410), etc. Une idée = en général un fait numéroté ; deux faits très voisins sont fusionnés (ex. faits 35 et 34 sur le cerveau).
- Méthode : lecture par blocs de 170 à 240 lignes, bornes d'idées définies en numéros de ligne dans des fichiers texte (« a-b | titre | résumé | mots-clés »), texte reconstruit par script (lignes jointes par un espace), donc mot pour mot.
- Les coupures tombent toujours en fin de ligne : temps_estime = false. Quand une ligne contient à la fois la fin d'un fait et le « Number N » suivant, la ligne va au segment où se trouve la plus grande part de ses mots (le plus souvent le segment qui commence), donc un titre de numéro peut apparaître en fin du segment précédent.
- Titres, résumés (2 à 3 phrases) et mots-clés (5 à 10) en anglais. Idées de 7 à 60 s ; les faits très courts (« quick-fire facts ») sont regroupés.
- Texte du speech non corrigé (fautes de transcription automatique conservées : « analesia », « spopalatine ganglio neuralgia », « Surre Mi », « Fran Schmidt »...). Dans les résumés les noms sont rétablis.

## Tranches
- Tranche 1 : lignes 1 à 976 (0,32 à 1801,12 s, ≈ 30 min), 63 segments (id 1 à 63). Fin sur la douleur fantôme (fait 5 de la liste de 50 faits) avant « Number four, pain relief through the ages ». Remarques : aucune coupure estimée ; segments courts (7 à 15 s) pour les faits 48 à 46.

- Tranche 2 : lignes 977 à 1946 (1801,12 à 3653,68 s, ≈ 30,9 min), 43 segments (id 64 à 106). Contenu : fin de la liste de 50 faits (soulagement de la douleur, douleur plaisante, névralgie du trijumeau, cœur brisé), liste des blessures les plus douloureuses (LCA, ligament collatéral ulnaire, jambe, vertèbres, TBI, calculs rénaux), endroits les plus douloureux pour un coup de poing, puis liste « unbearable » (n° 20 à 16 : poisson-pierre, fourmi balle, goutte, Lego, hernie discale). Remarques : aucune coupure estimée ; les passages longs (≥ 120 s) sont scindés en deux idées.

- Tranche 3 : lignes 1947 à 2909 (3653,68 à 5459,76 s, ≈ 30,1 min), 37 segments (id 107 à 143). Contenu : fin de la liste « unbearable » (n° 15 à 1 : drépanocytose, neuropathie, ours grizzly, péritonite, mal de dents, fémur, épaule luxée, torsion testiculaire, exécutions, calculs, tétanos, brûlures, algie vasculaire, névralgie du trijumeau), puis début de la liste des 15 procédures médicales les plus douloureuses (n° 15 à 8 : liposuccion, gaz du sang artériel, implants dentaires, myomectomie, prothèse de hanche, hémorroïdectomie, greffe de peau, ponction lombaire). Remarques : aucune coupure estimée.

Reprise à la ligne 2910 (travail d'un agent précédent vérifié : 143 segments, lignes 1 à 2909, OK ; non modifié).

- Tranche 4 : lignes 2910 à 3892 (5459,76 à 7319,44 s, ≈ 31 min), 42 segments (id 144 à 185). Contenu : fin de la liste des procédures médicales les plus douloureuses (n° 7 à 1 : ablation de la vésicule biliaire, accouchement, hystérectomie, proctocolectomie, chirurgie du talon, fusion vertébrale, biopsie de moelle osseuse), puis nouvelle liste sur les morts les plus douloureuses : brûlures (Jackie Suburido, Katherine Hayes), armes à feu (blessures par balle à divers endroits), coups de couteau, crise cardiaque et arrêt cardiaque, surdose d'opioïdes, cancer, fin de vie (phase pré-active et active), déshydratation (Chaz Powell), famine, AVC, BPCO, cirrhose, accidents de la route (traumatisme, hémorragie, choc, motard amputé). Remarques : aucune coupure estimée. Une ligne qui mêle la fin d'une idée et le début de la suivante va au segment qui garde la phrase la plus complète ou la majorité de ses mots. La ligne 2910 (« pain of having organs ripped out of your ») ouvre le segment 144 : elle est le reste de la phrase commencée à la ligne 2909 (fin du segment 143).

## Point d'arrêt
Dernière ligne traitée : 3892 (fin du segment 185, sur le récit du motard accidenté). Prochaine étape : tranche 5, à partir de la ligne 3893 (« amputated. Amputation can also be a consequence of a car crash... », suite sur le fémur et les fractures), id 186.

Reprise à la ligne 3893 (travail d'un agent précédent vérifié : 185 segments, lignes 1 à 3892, OK ; non modifié).

- Tranche 5 : lignes 3893 à 4818 (7319,44 à 9216,16 s, ≈ 31,6 min), 36 segments (id 186 à 221). Contenu : fin de la section sur les morts douloureuses (écrasement et fémur, noyade, expériences de mort imminente), puis une première liste « top 10 » des douleurs (ornithorynque, mal de dents et dents qui explosent, calculs rénaux, guêpe tarentule, cancer des os, céphalée rachidienne, torsion testiculaire, balle dans le genou et Irlande du Nord, algie vasculaire de la face, névralgie du trijumeau, proctalgie fugace), puis une seconde liste de maladies (n° 10 à 6 : syndrome de Stoneman, épidermolyse bulleuse, névralgie post-zostérienne, ostéosarcome, syndrome de l'homme raide). Remarques : aucune coupure estimée ; plusieurs coupures tombent au milieu d'une phrase ou sur un « Number N » car les lignes de sous-titres automatiques sont courtes ; la tranche s'arrête à la ligne 4818 (« agonizing spasms. Number five, ») et la suivante commence à « arachnoiditis. ».

## Point d'arrêt (mis à jour)
Dernière ligne traitée : 4818 (fin 9216,16 s). Prochaine étape : tranche 6, à partir de la ligne 4819 (« arachnoiditis. Think about the worst back pain you've ever had… »), id 222.

Reprise à la ligne 4819 (travail d'agents précédents vérifié : 221 segments, lignes 1 à 4818, OK ; non modifié).

- Tranche 6 : lignes 4819 à 5737 (9216,16 à 11154,32 s, ≈ 32,3 min), 27 segments (id 222 à 248). Contenu : fin du top 10 des conditions douloureuses (n° 5 à 1 : arachnoïdite, cancer du pancréas, SDRC, algie vasculaire, névralgie du trijumeau), puis épisode sur les morts les plus douloureuses de l'histoire (Balthasar Gérard, Treadwell et les grizzlis, Dózsa, lingchi, Yuan Chonghuan, les cinq châtiments chinois, Li Si, Ismaïl et Melik, Iron Mike, plomb fondu de Crassus et Henry Hall, Damiens, Tchernobyl, Martin d'Aragon). Aucune coupure estimée. Style : un segment par récit ou par item de liste ; titres « Number N: … » pour les listes. Les fragments de titres de liste coupés à cheval sur deux lignes (« Number one, trigeminal / neuralgia ») restent dans le segment de la ligne.

## Point d'arrêt (mis à jour)
Dernière ligne traitée : 5737 (fin 11154,32 s, fin du segment sur la mort de Martin d'Aragon). Prochaine étape : tranche 7, à partir de la ligne 5738 (« epic face plant you just took off your skateboard… », début du top 10 des blessures), id 249.

- Tranche 7 : lignes 5738 à 6624 (11154,32 à 13021,76 s, ≈ 31,1 min), 43 segments (id 249 à 291). Contenu : top 10 des blessures les plus douloureuses (n° 10 à 1 : écorchure de route, coccyx, clavicule, fracture du boxeur, entorse de cheville, côtes, tendon d'Achille, torsion testiculaire, brûlures du 3e degré, frelon géant asiatique), puis nouvelle liste de « 50 faits » sur les conditions les plus douloureuses (n° 50 à 18 : goutte, endométriose, fibromyalgie, neuropathie périphérique, pancréatite aiguë, appendicite, calculs rénaux). Un segment par item de liste. Aucune coupure estimée. Les fragments de titres (« Number 27. Sorry, boss. » etc.) à cheval sur deux lignes restent dans le segment de la ligne.

## Point d'arrêt (mis à jour)
Dernière ligne traitée : 6624 (fin 13021,76 s, fin du segment « Number 19: the four types of kidney stones »). Prochaine étape : tranche 8 (dernière), à partir de la ligne 6625 (« really true? Number 18, more painful than child birth… »), id 292, jusqu'à la ligne 6947.

- Tranche 8 (dernière) : lignes 6625 à 6947 (13021,76 à 13672,56 s, ≈ 10,8 min), 19 segments (id 292 à 310). Contenu : fin de la liste de « 50 faits » (n° 18 à 1 : calculs rénaux, névralgie du trijumeau, algie vasculaire, SDRC) et outro. Un segment par item de liste. Aucune coupure estimée.

## Point d'arrêt (final)
Dernière ligne traitée : 6947 sur 6947 (fin 13672,56 s). « complet » = true. Rien à reprendre.

## Bilan final (reprise des tranches 6 à 8, lignes 4819 à 6947)
- Méthode : lecture du speech par blocs de ~200 lignes (sans les temps), découpage par idées sur des limites de lignes, construction de segments.json par script en mode ajout (texte copié mot pour mot depuis speech.json, temps repris des lignes), vérification par script avant chaque push.
- Total du fichier : 310 segments (id 1 à 310). Plus court : 7,0 s. Plus long : 118,4 s. Aucun temps estimé.
- Passages douteux : transcription automatique (fautes conservées : « Yurard », « Domianne », « CPRS », « pee » pour pea, etc. ; les noms sont rétablis dans les résumés) ; les titres de liste coupés sur deux lignes (« Number 27. Sorry, boss. ») sont rattachés au segment de la ligne où ils tombent ; les marqueurs « [music] » sont laissés dans le texte.
- Remarque de contenu : la vidéo est un montage de plusieurs épisodes (listes de conditions douloureuses, morts les plus douloureuses, blessures, « 50 faits »), d'où des sujets qui reviennent (névralgie du trijumeau, algie vasculaire et SDRC apparaissent dans deux listes différentes).
