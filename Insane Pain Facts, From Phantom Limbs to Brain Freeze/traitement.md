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

## Point d'arrêt
Dernière ligne traitée : 2909. Prochaine étape : tranche 4, à partir de la ligne 2910 (fin de la ponction lombaire déjà couverte ; reprise sur « body, though. Number seven, gallbladder removal ... » ligne 2910 : « pain of having organs ripped out of your »), id 144.
