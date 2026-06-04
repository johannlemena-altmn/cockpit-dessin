# Capter l'énergie d'une salle de sport (chaleur et mouvement) pour financer la transition : état de l'art, réalité physique, modèle ESS et verdict

Document de travail, juin 2026. Destiné à Johann Lemena.
Registre : exploration honnête, chiffrée, sans complaisance. L'objet est de séparer ce qui tient debout de ce qui relève du mirage.

---

## 0. Ce que dit l'intuition de départ, et comment on va la trancher

Ton point de départ mélange deux phénomènes physiques distincts qu'il faut séparer dès le début, sinon tout le raisonnement devient flou :

1. **L'énergie mécanique** : une personne qui pédale, court ou rame fait tourner un axe. Cette énergie peut être convertie en électricité avec un bon rendement. C'est de l'électricité « propre » au sens où elle ne brûle rien.
2. **La chaleur** : un corps, surtout à l'effort, dégage beaucoup de chaleur. Mais la chaleur basse température est une forme d'énergie « dégradée » : on la transforme très mal en électricité, et très bien en… chaleur. C'est une nuance qui change tout.

Ton intuition « ça doit déjà exister » est juste : les deux pistes existent, sont documentées, et certaines tournent en vrai. Ton intuition « on pourrait revendre cette énergie pour financer des projets collectifs » est, elle, à corriger fortement sur la partie électrique, et à reformuler sur la partie chaleur et sur la valeur symbolique. On y vient.

---

## 1. État de l'art

### 1.1 Équipements de sport qui produisent de l'électricité

**SportsArt (gamme ECO-POWR).** Le fabricant de référence. Vélos, tapis, elliptiques, rameurs équipés d'un micro-onduleur qui renvoie l'électricité produite directement dans le circuit du bâtiment (220-240 V), où elle alimente d'autres machines et réduit la facture. Le constructeur annonce jusqu'à 74 % de conversion de l'énergie humaine en électricité utilisable, et des pics autour de 200 W par machine pour un utilisateur qui force. Un tapis « auto-alimenté » : le coureur fait avancer la bande, plus besoin de moteur, et le surplus repart au réseau du bâtiment.

**Energym (RE:GEN).** Vélo connecté qui stocke dans une batterie amovible « Ohm » de 90 Wh. Un cycliste moyen produit 180-200 W sur une séance. Le constructeur communique sur « une séance de 30 minutes recharge la batterie », soit de quoi recharger une dizaine de smartphones. C'est l'ordre de grandeur honnête : on parle de recharger des téléphones, pas d'alimenter un foyer.

**The Green Microgym (Portland).** La salle « pionnière », ouverte en 2008, qui a popularisé l'idée. Elle a d'abord bricolé ses machines, puis est devenue revendeuse SportsArt. Donnée clé, et très instructive : une séance moyenne y produit **37,5 Wh**, « de quoi alimenter un téléphone pendant une semaine ». Retiens ce chiffre, c'est le plus honnête de tout le dossier.

**Autres acteurs.** The Great Outdoor Gym Company (mobilier urbain de fitness produisant un peu d'électricité pour de l'éclairage ou des prises USB). De nombreuses opérations événementielles « cinéma à pédales », « concert alimenté par le public ». Ces dispositifs sont réels mais relèvent surtout de la pédagogie et de l'animation, pas de la production sérieuse.

### 1.2 Récupération de chaleur corporelle

**Gare centrale de Stockholm (Jernhusen / immeuble Kungsbrohuset).** Le cas le plus cité. Les 250 000 personnes qui transitent chaque jour dans la gare réchauffent l'air ; des échangeurs sur la ventilation transfèrent cette chaleur vers de l'eau chaude, pompée jusqu'à un immeuble de bureaux voisin. Résultat : **15 à 25 %** des besoins de chauffage de l'immeuble couverts, environ 20 % d'économie sur la facture. À retenir : la chaleur est réutilisée **directement en chaleur**, jamais convertie en électricité.

**Mall of America (États-Unis).** Centre commercial géant chauffé en grande partie par la chaleur des visiteurs, des éclairages et des magasins, au point de quasiment ne pas avoir de chauffage central conventionnel. Même logique : chaleur récupérée pour chauffer.

**Récupération de chaleur du métro.**
- *Paris* : RATP et Paris Habitat, immeuble du 4ᵉ arrondissement, pompe à chaleur sur l'air chaud de la ligne 11 ; **35 %** des besoins de chauffage de 20 logements. Études d'extension (Porte de Clichy, Mairie de Saint-Ouen) visant jusqu'à 100 % des besoins d'une station.
- *Londres* (réseau Bunhill) : une pompe à chaleur de 1 MW sur un puits de ventilation de la Northern Line, air à 18-28 °C remonté à ~70 °C, qui chauffe plus de 500 logements.

Le fil rouge de toute la section 1.2 : **la chaleur basse température ne sert qu'à faire de la chaleur**, via pompe à chaleur et réseau d'eau chaude. Personne, nulle part, ne convertit cette chaleur diffuse en électricité, parce que c'est physiquement absurde (section 2).

---

## 2. Réalité physique, sans complaisance

### 2.1 L'énergie mécanique : un humain est une très petite centrale

Puissance mécanique qu'un humain soutient sur la durée (pas un pic de quelques secondes) :

| Profil | Puissance soutenue ~1 h |
|---|---|
| Personne au repos sur un vélo, pédalage de loisir | 50 à 100 W |
| Pratiquant régulier, cours de biking intense | 150 à 250 W |
| Cycliste entraîné (FTP) | 200 à 300 W |
| Athlète élite (WorldTour) | 380 à 490 W |

Tableau 1 : puissance mécanique humaine soutenue (sources : Cyclists Hub, Rouvy, données FTP 2026).

Garde 150 W comme hypothèse réaliste et plutôt généreuse pour un participant motivé en cours collectif.

**Calcul d'une salle.** Prends une salle de biking bien remplie : **20 vélos**, occupés **6 heures par jour** en moyenne (c'est déjà optimiste, une salle ne tourne pas à plein toute la journée), participants à **150 W mécaniques**, rendement de conversion mécanique vers électricité utile autour de **70 %** (chiffre constructeur, déjà flatteur).

- Puissance électrique moyenne par vélo : 150 W × 0,70 ≈ **105 W**.
- Énergie par vélo et par jour : 105 W × 6 h ≈ **0,63 kWh**.
- Pour 20 vélos : ≈ **12,6 kWh par jour**, soit ~**4 600 kWh par an**.

**Comparaison qui fait mal.** Un foyer français moyen consomme de l'ordre de **4 700 kWh/an** d'électricité (hors chauffage électrique ; avec chauffage électrique, on dépasse souvent 10 000 kWh/an). Donc ta salle de 20 vélos tournant 6 h/jour, dans une hypothèse optimiste, produit environ l'électricité **d'un seul foyer**, chauffage non compris.

Et l'ordre de grandeur le plus parlant reste celui de The Green Microgym : **une séance = 37,5 Wh**. Pour produire **1 kWh** (le prix d'environ 0,20 € au tarif réglementé), il faut **27 séances** de sport complètes. Un participant qui sue pendant 45 minutes génère, en valeur électrique de marché, **moins d'un centime d'euro**.

### 2.2 La chaleur : abondante, mais quasi inconvertible en électricité

Un corps dégage **~100 W au repos**. À l'effort intense, la production de chaleur métabolique grimpe à **350-500 W**, et le corps peut évacuer jusqu'à **~700 W** par évaporation de la sueur. Une salle de 20 personnes à l'effort, c'est donc grossièrement **7 à 10 kW de chaleur** déversés dans la pièce. C'est énorme, et c'est exactement pourquoi une salle de sport bondée devient vite une étuve. Ton intuition « manchots sur la banquise » est physiquement correcte : la chaleur est bien là.

**Le piège.** Convertir cette chaleur en électricité se heurte au rendement de Carnot. À 37 °C de source (310 K) contre 0 °C d'ambiance (273 K), le rendement **théorique maximal** est de **12 %**. Dans la vraie vie, l'écart de température entre l'air d'une salle (disons 25-30 °C) et l'extérieur est bien plus faible, et les générateurs thermoélectriques réels tournent **sous 5 %**, souvent autour de 1-2 %. Conclusion brutale : sur 10 kW de chaleur, tu récupérerais peut-être 100 à 200 W d'électricité avec un matériel coûteux et fragile. C'est ridicule.

**Ce qui marche, en revanche.** Réutiliser la chaleur **en tant que chaleur**, avec un rendement de récupération qui peut dépasser 70-80 % :
- préchauffage de l'air neuf via la VMC double flux (récupérateur sur l'air extrait) ;
- préchauffage de l'eau chaude sanitaire (douches de la salle, gros poste) ;
- couplage à une pompe à chaleur pour rehausser la température, comme à Stockholm ou dans le métro.

C'est là qu'est la vraie énergie récupérable d'une salle de sport. Pas dans l'électricité, dans la chaleur réutilisée sur place.

### 2.3 Verdict physique intermédiaire

- Électricité mécanique : réelle, propre, mais marginale en quantité. Une salle entière ≈ un foyer.
- Chaleur en électricité : mirage thermodynamique, à abandonner.
- Chaleur en chaleur : la vraie ressource, sous-exploitée, qui peut couvrir une part significative des besoins de chauffage et d'eau chaude du bâtiment.

---

## 3. Modèle ESS et économique

### 3.1 Le cadre français de la valorisation d'électricité, en clair

Trois voies existent pour ce que produit une installation :

**Autoconsommation individuelle.** Tu consommes sur place ce que tu produis. C'est le mode le plus pertinent ici : l'électricité des vélos alimente l'éclairage, les écrans, la ventilation de la salle, et réduit la facture. Pas de paperasse de revente. Économie directe au prix où tu achètes ton électricité (~0,20 €/kWh), donc bien plus que le prix de revente.

**Autoconsommation collective.** Cadre français spécifique, géré par Enedis : plusieurs producteurs et consommateurs reliés au même quartier (périmètre géographique encadré) partagent une production via le réseau public. C'est le montage qui colle à un projet ESS de quartier. Il impose une personne morale organisatrice (souvent une association ou une coopérative), une convention avec Enedis, et le paiement du TURPE (tarif d'usage du réseau, de l'ordre de 25-35 €/an pour les petites puissances). Pertinent surtout pour du solaire de quartier ; pour une salle de sport, la production est trop faible pour justifier seule ce montage, mais le cadre juridique de la coopérative reste le bon véhicule.

**Obligation d'achat / revente du surplus.** Tu peux vendre le surplus. Sauf que les tarifs 2026 sont parlants : **environ 0,04 €/kWh** pour le surplus d'une petite installation (≤ 9 kWc), **~0,054 €/kWh** entre 9 et 100 kWc. Et tu paies le TURPE et tu deviens « producteur » avec ses obligations.

### 3.2 Chiffrons le revenu électrique réel

Reprenons la salle de 20 vélos : ~4 600 kWh/an.

- **En revente au réseau** (0,04 €/kWh) : **~184 € par an**. Ce n'est pas une faute de frappe. Moins de 200 € par an pour 20 vélos qui tournent 6 h/jour.
- **En autoconsommation** (économie sur une électricité achetée ~0,20 €/kWh) : **~920 € par an**. Cinq fois mieux, et c'est l'option à retenir, mais ça reste l'ordre de grandeur d'un demi-mois de loyer commercial.

Face à cela, l'investissement : un vélo SportsArt ECO-POWR coûte plusieurs milliers d'euros pièce, soit un surcoût de plusieurs dizaines de milliers d'euros pour la salle par rapport à du matériel classique. Le **temps de retour par l'électricité seule se compte en décennies, voire jamais**. Conclusion : on ne finance aucun projet collectif avec la vente d'électrons. Le revenu électrique est une rounding error.

### 3.3 Où est la vraie valeur

La valeur de ce projet n'est pas dans les kWh. Elle est dans trois registres bien plus consistants :

**1. La chaleur réutilisée (valeur la plus tangible).** Récupérer la chaleur des corps et des douches via VMC double flux et pompe à chaleur peut couvrir une part réelle du chauffage et de l'eau chaude du bâtiment. C'est là que se trouvent les vraies économies physiques, sur un poste (chauffage + ECS) qui pèse bien plus lourd que l'électricité spécifique. À chiffrer sur un bâtiment réel, mais l'ordre de grandeur potentiel dépasse de loin les 920 €/an de l'électricité.

**2. La valeur symbolique, pédagogique et d'engagement.** Un compteur qui affiche en temps réel « vous avez produit X Wh, alimenté Y ampoules » transforme l'effort en geste citoyen visible. C'est un puissant levier d'adhésion, de fidélisation, de communication, de différenciation commerciale. Des salles le vendent déjà comme argument marketing. C'est réel, et ça a une valeur monétaire indirecte (adhésions, notoriété, presse).

**3. Le montage ESS qui capte cette valeur symbolique.** Plutôt que de financer des projets par la vente d'électricité (impossible), tu finances par le **modèle**, en faisant de la salle une vitrine :
- structure en **coopérative (SCIC)** ou **association**, gouvernance démocratique sur l'usage des fonds, ce qui colle à ton exigence « usages d'intérêt général choisis démocratiquement » ;
- recettes réelles : **adhésions / abonnements** d'une salle qui se distingue par son projet, **mécénat et sponsors** (collectivités, fondations, entreprises locales cherchant une vitrine bas-carbone), **subventions** (CEE, ADEME, programmes régionaux d'innovation sociale), **label** revendiqué ;
- une partie des excédents fléchée, par vote des sociétaires, vers des projets de transition du territoire.

Dans ce montage, l'énergie produite est le **prétexte mobilisateur**, pas la source de revenu. C'est honnête, et c'est solide.

---

## 4. Verdict d'expert et pistes

### 4.1 Ce qui est juste dans ton intuition

- La chaleur d'une salle bondée est bien réelle et massive : 7 à 10 kW pour 20 personnes à l'effort. Bien vu.
- L'énergie cinétique du sport est captable et convertible en électricité propre, la technologie existe et est mûre (SportsArt, Energym).
- Le cadre ESS, gouvernance démocratique, financement de projets collectifs, est pertinent et même la meilleure partie de l'idée.

### 4.2 Ce qu'il faut abandonner

- **Convertir la chaleur des corps en électricité** : mirage thermodynamique (Carnot ~12 % théorique, <5 % réel). À enterrer définitivement.
- **Financer des projets collectifs par la vente d'électricité** : faux. ~184 €/an de revente pour 20 vélos. L'électricité produite est trop faible et trop mal payée. À remplacer par l'autoconsommation (qui économise sans enrichir) et par les recettes du modèle ESS.
- **L'idée d'une salle qui « alimente une commune »** : un foyer, pas une commune. À recalibrer dans tout discours public, sous peine de perdre en crédibilité.

### 4.3 La version réaliste et utile de l'idée

Une salle de sport coopérative, à double récupération :
- **Mécanique** : machines productrices d'électricité en **autoconsommation**, dont la vraie fonction est pédagogique et d'engagement (compteur visible, gamification).
- **Thermique** : récupération sérieuse de la chaleur des corps et des douches, via VMC double flux et pompe à chaleur, pour le chauffage et l'eau chaude (c'est là que sont les vraies économies physiques).
- **Modèle** : structure ESS qui transforme la visibilité du projet en adhésions, mécénat, sponsors, subventions, et qui finance démocratiquement des projets de transition du territoire.

L'énergie est le récit fédérateur ; le financement vient du modèle, pas des électrons.

### 4.4 Trois à cinq prochaines étapes concrètes pour prototyper

1. **Quantifier sur une vraie salle.** Trouver une salle de biking partenaire, mesurer fréquentation réelle, heures d'occupation, et estimer la production électrique et la chaleur dégagée. Remplacer mes hypothèses par des vrais chiffres.
2. **Dimensionner la récupération de chaleur.** Faire chiffrer par un bureau d'études thermiques une récup sur la VMC et sur les eaux grises des douches, avec part des besoins de chauffage et d'ECS couverts, et temps de retour. C'est la brique la plus rentable, à instruire en priorité.
3. **Choisir le véhicule juridique.** Comparer association et SCIC, écrire une gouvernance où les sociétaires votent l'affectation des excédents. Caler le discours sur les bons ordres de grandeur.
4. **Construire le modèle de recettes.** Lister les guichets réels (CEE, c'est ton terrain professionnel, ADEME, fondations, collectivités, sponsors locaux) et bâtir un budget prévisionnel où l'électricité revendue pèse symboliquement et le reste fait le chiffre.
5. **Chercher une commune ou une collectivité pilote.** Présenter le projet comme une vitrine bas-carbone et un outil d'engagement citoyen, pas comme une source d'énergie pour la commune. C'est l'angle juste et vendeur.

---

### Sources principales
- SportsArt ECO-POWR : gosportsart.com, World Economic Forum (2018).
- Energym RE:GEN : energym.io, GearJunkie.
- The Green Microgym : thegreenmicrogym.com (37,5 Wh/séance).
- Stockholm Kungsbrohuset / Jernhusen : CleanTechnica, TIME, Amusing Planet.
- Récup chaleur métro : RATP (ligne 11), Le Moniteur, Techniques de l'Ingénieur (Bunhill, Londres).
- Puissance humaine et FTP : Cyclists Hub, Rouvy, données FTP 2026.
- Chaleur métabolique : HeatHydration, Deranged Physiology, ScienceDirect.
- Carnot et thermoélectrique basse température : IntechOpen, ScienceDirect, Stanford PH240.
- Cadre français : Enedis (autoconsommation collective), Hellio et Libow (tarifs OA 2026), photovoltaique.info, TURPE 7.
