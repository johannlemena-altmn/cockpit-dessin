# Développer un projet de rénovation sur papier : process complet, montages et méthode de cas d'étude

Document de travail pour Johann Lemena. Objectif : reproduire « sur papier » le process d'un responsable développement / montage d'opération, du sourcing au dépôt de permis, en l'orientant vers la rénovation bas carbone et en remplaçant le schéma achat-négociation par des montages gagnant-gagnant. Le tout relu au prisme « architecte d'expérience » : capter un récit avant de démontrer.

Une remarque d'honnêteté pour cadrer la suite. Personne ne devient développeur immobilier en lisant un document. Ce qui suit te donne la carte, pas le terrain. Trois choses te manqueront comme autodidacte, et il vaut mieux les nommer tout de suite : l'accès réel au foncier (les bonnes affaires ne sont pas sur les plateformes publiques, elles circulent dans des réseaux), la lecture fine d'un bilan d'opération (qui s'apprend en le faisant rater une fois), et l'autorité technique pour trancher une faisabilité (un architecte ou un bureau d'études le fait en trente minutes, toi en trois jours). Le cas d'étude sert justement à compenser : sur papier, tu peux simuler ces trois compétences sans capital ni mandat.

---

## Partie A. La chaîne complète du process de développement

Sept étapes. Pour chacune : ce qui se passe, qui fait quoi, le livrable produit, et les outils gratuits exploitables par un autodidacte. Je signale les pièges réels à chaque fois.

### Étape 1. Sourcing (repérer le gisement)

Tu cherches un bien ou un terrain qui a un potentiel non exploité : un bâtiment sous-occupé, une friche, un immeuble vétuste dans un secteur où le marché tire, un local dont l'usage actuel ne correspond plus à ce que le quartier demande. Le développeur appelle ça « détecter une plus-value latente ».

Chez Nexity, Cyril faisait ça à deux niveaux : la veille systématique (cartographie, déclarations d'intention d'aliéner en mairie, contacts notaires) et le flair de terrain (rouler dans un secteur, repérer une dent creuse, un bâtiment muré). Tu ne reproduiras pas le premier sans réseau. Le second, tu peux.

- Qui fait quoi : le développeur source seul ou avec un apporteur d'affaires. En autodidacte, tu fais tout.
- Livrable : une fiche de repérage par bien candidat (adresse, parcelle cadastrale, propriétaire présumé, première intuition d'usage).
- Outils gratuits :
  - cadastre.gouv.fr : identifie la parcelle, sa surface, ses limites.
  - DVF (Demandes de Valeurs Foncières) sur app.dvf.etalab.gouv.fr : tu vois le prix réel des transactions passées dans la rue, pas les prix affichés. C'est l'outil le plus sous-estimé pour un débutant, il te donne le marché réel.
  - Géoportail (geoportail.gouv.fr) : photo aérienne historique, tu compares 2000 et aujourd'hui pour voir ce qui s'est dégradé ou libéré.
  - Cartofriches (cartofriches.cerema.fr) : inventaire national des friches recensées, parfait pour un premier cas d'étude.

Piège réel : trouver un bien candidat est facile, savoir s'il est réellement disponible et à quel prix le propriétaire lâcherait est le vrai mur. Garde ça pour l'étape 5.

### Étape 2. Analyse réglementaire (PLU / PLUi)

Tu vérifies ce que le droit des sols autorise sur la parcelle. C'est binaire et impitoyable : si le PLU interdit ton usage ou ta hauteur, ton idée meurt là, peu importe sa beauté.

Ce que tu lis dans le PLU : le zonage (U, AU, A, N), le règlement de la zone (usages autorisés, hauteur maximale, emprise au sol, retraits, stationnement, aspect des façades), les servitudes (monuments historiques, risques, alignements), et les orientations d'aménagement (OAP) qui fixent des intentions sur certains secteurs.

- Qui fait quoi : le développeur fait une première lecture, l'architecte et le juriste valident l'interprétation. En rénovation, ta marge se joue souvent dans les détails du règlement (peut-on surélever ? changer la destination ?).
- Livrable : une note de constructibilité (ce que la parcelle permet, ce qu'elle interdit, les points à confirmer en mairie).
- Outils gratuits :
  - Géoportail de l'urbanisme (geoportail-urbanisme.gouv.fr) : le PLU/PLUi de la commune, téléchargeable. C'est ta source numéro un.
  - Atlas des patrimoines (atlas.patrimoines.culture.fr) : périmètres des monuments historiques et abords (utile pour anticiper l'ABF, voir partie B).
  - Géorisques (georisques.gouv.fr) : risques naturels et technologiques sur la parcelle (inondation, retrait-gonflement des argiles, pollution des sols).

Piège réel : le PLU se lit sur deux documents distincts, le plan de zonage et le règlement écrit, et il faut croiser les deux. Beaucoup d'autodidactes lisent le plan, voient « zone U » et croient que tout est permis. Le règlement écrit est là où sont les vraies contraintes.

### Étape 3. Faisabilité technique

Tu vérifies que le bâtiment ou le terrain peut physiquement accueillir ton idée. En rénovation, c'est l'étape qui révèle les bonnes et les mauvaises surprises : structure, état, présence d'amiante, capacité à recevoir de nouveaux usages.

- Qui fait quoi : l'architecte produit une esquisse (un croquis volumétrique qui teste l'idée), le bureau d'études structure dit si ça tient, les diagnostiqueurs interviennent plus tard. Le développeur cadre la commande et arbitre.
- Livrable : une esquisse + une note de faisabilité technique (ce qu'on garde, ce qu'on démolit, les points durs).
- Outils gratuits :
  - Géoportail (vue 3D, mesures de surfaces et de hauteurs approximatives).
  - Street View et les vues immersives pour observer les façades, l'état apparent, l'environnement immédiat.
  - Les archives de permis de construire en mairie (consultables gratuitement) pour retrouver les plans d'origine d'un bâtiment ancien.

Piège réel : en faisabilité de rénovation, ce qui coûte n'est pas ce qu'on voit. L'amiante, le désamiantage, la mise aux normes structure et accessibilité plombent les bilans. Un autodidacte sous-estime toujours ces postes. Sur papier, prévois une ligne « aléas et imprévus » d'au moins 10 à 15 % du coût travaux.

### Étape 4. Faisabilité économique et bilan de l'opération

Tu chiffres si l'opération s'équilibre. Le bilan promoteur, dans sa forme la plus simple :

Recettes (ce que tu vends ou loues) moins charges (foncier + travaux + études et honoraires + frais financiers + frais commerciaux + marge) = équilibre. Si la marge est trop faible ou négative, l'opération ne se fait pas.

Postes principaux d'un bilan de rénovation :
- Le foncier (ou la valeur d'apport du bâti existant si montage sans achat, voir partie C).
- Les travaux (le gros poste, très variable en rénovation, de 800 à 2500 euros/m² selon l'ampleur).
- Les honoraires (architecte, BET, géomètre, bureau de contrôle, coordinateur sécurité) : compter 12 à 18 % du coût travaux.
- Les frais financiers (intérêts du crédit de portage).
- Les frais commerciaux et la marge de l'opérateur.

- Qui fait quoi : le développeur monte le bilan, le pôle études le fiabilise, la direction valide le seuil de marge.
- Livrable : un bilan prévisionnel d'opération (tableau recettes/dépenses, marge, point mort).
- Outils gratuits :
  - DVF (encore) pour caler les recettes sur des prix réels.
  - Les bases notariales et observatoires locaux des loyers pour le marché locatif.
  - INSEE (insee.fr, données par commune et IRIS) pour la démographie, le revenu médian, la tension du marché : ça justifie tes hypothèses de recettes.
  - Un tableur. Un bilan d'opération est un tableur, rien de plus. Construis-le à la main une fois, tu comprendras tout.

Piège réel : le bilan est l'endroit où un autodidacte se ment le plus facilement. On gonfle les recettes, on minore les travaux, et l'opération « passe ». Discipline : recettes prudentes (fourchette basse de DVF), travaux généreux (fourchette haute + aléas). Si ça passe quand même, l'opération est solide.

### Étape 5. Maîtrise foncière (sécuriser le bien)

Tu obtiens le droit de disposer du bien. C'est l'étape qui, chez Nexity, débouchait sur l'offre de rachat puis la négociation longue que tu veux éviter. La partie C entière est consacrée aux alternatives. Retiens ici le principe : tant que tu n'as pas de promesse signée (ou un bail, ou un mandat), tu n'as rien, et tout le travail amont est à risque.

- Qui fait quoi : le développeur négocie, le notaire et le juriste sécurisent l'acte. C'est là que se joue la relation humaine, donc c'est là que ton prisme « architecte d'expérience » a le plus de valeur (partie D, le propriétaire).
- Livrable : une promesse de vente, un compromis, ou un montage alternatif signé.

Piège réel : c'est le vrai goulot d'étranglement de tout le métier. Sourcer, analyser, chiffrer : un autodidacte peut le faire seul. Convaincre un propriétaire de céder ou d'associer son bien : ça demande un capital, un mandat, ou une relation de confiance que tu n'as pas encore. D'où l'intérêt du cas d'étude sur papier, qui simule cette étape sans la subir.

### Étape 6. Parties prenantes et validation interne

Tu fais valider le projet par tous ceux qui peuvent le bloquer ou le porter : juridique, technique, commercial, client/propriétaire, collectivité. C'est l'objet de la partie D. La validation interne (chez un promoteur, le « comité d'engagement ») est le moment où la direction dit oui ou non au regard du bilan et du risque.

- Livrable : un dossier de présentation projet (le futur cœur de ton pitch) + une décision d'engagement.

### Étape 7. Administratif et dépôt de l'autorisation

Tu déposes l'autorisation d'urbanisme. En rénovation, le choix entre déclaration préalable et permis de construire dépend de l'ampleur (partie B).

- Qui fait quoi : l'architecte monte et dépose le dossier (obligatoire au-delà de 150 m² de surface de plancher), la mairie instruit, l'ABF émet un avis si le bien est en secteur protégé.
- Livrable : le dossier de demande (DP ou PC) et, à terme, l'arrêté.
- Outils gratuits :
  - service-public.fr pour les formulaires Cerfa et la liste des pièces.
  - Le portail d'urbanisme dématérialisé de la commune pour le dépôt en ligne.

Piège réel : le délai. Une fois le permis déposé, comptez l'instruction (deux à six mois selon les cas), puis le délai de recours des tiers (deux mois après affichage), puis le retrait possible. Un projet « validé » n'est pas un projet « purgé ». Pour un cas d'étude, c'est un détail ; pour un vrai projet, c'est six mois à un an de plus.

---

## Partie B. Le volet rénovation

Rénover n'est pas construire en plus petit. C'est un métier différent, avec ses contraintes propres et, c'est là que ton positionnement prend sens, un potentiel bas carbone énorme que le neuf n'aura jamais.

### Les contraintes propres à l'existant

- L'existant impose sa loi. Tu composes avec une structure, des trames, des hauteurs sous plafond, une orientation que tu n'as pas choisies. C'est une contrainte et un cadeau : ça force la créativité (la démarche Kéré, partie finale).
- Diagnostics obligatoires avant travaux sur bâti ancien : amiante (avant 1997), plomb (avant 1949), état des installations électriques et gaz, performance énergétique (DPE). Le repérage amiante avant travaux est non négociable et conditionne le coût.
- Structure : un bureau d'études structure doit valider toute ouverture, surélévation, changement de charge. C'est non négociable et ça se chiffre.
- Accessibilité (PMR) et sécurité incendie : déclenchées dès qu'il y a changement de destination ou accueil de public (ERP). Postes lourds, souvent oubliés par les débutants.

### ABF : les abords de monuments

Si le bien est dans le périmètre d'un monument historique ou en site patrimonial remarquable (à vérifier sur l'Atlas des patrimoines, étape 2), l'Architecte des Bâtiments de France (ABF) émet un avis sur l'aspect extérieur. Cet avis peut être conforme (il s'impose) ou simple selon le cas. Concrètement : tes choix de façade, de menuiseries, de toiture, de couleurs ne sont plus libres. Anticipe-le très tôt, un refus ABF tardif fait tomber un projet.

### Quelle autorisation : déclaration préalable ou permis ?

Règle simple à retenir :
- Déclaration préalable (DP) : petits travaux, modification d'aspect extérieur, changement de destination sans travaux sur la structure, créations de surface limitées (jusqu'à 20 m², 40 m² en zone urbaine sous conditions).
- Permis de construire (PC) : créations de surface importantes, modifications de structure porteuse avec changement de destination, surélévations significatives. Le recours à un architecte est obligatoire au-delà de 150 m² de surface de plancher.

En rénovation lourde avec changement d'usage, c'est presque toujours un permis.

### Réglementation énergétique applicable

Le neuf relève de la RE2020. La rénovation relève d'un autre régime : la réglementation thermique « existant » et, surtout, la logique du DPE et des obligations de rénovation (interdiction progressive de location des passoires énergétiques). Pour un cas d'étude, ton angle gagnant est de viser une amélioration franche du DPE et de la documenter : c'est ce qui « parle » à la collectivité et au futur occupant.

### L'angle bas carbone, réemploi, bioclimatique (les trois références)

C'est le cœur de ta différenciation. Trois apports concrets, un par référence.

1. Sobriété matière et réemploi (« Matériaux, un catalogue critique », Choplin et Simay). Le livre dépolitise faussement nos choix de matériaux et les repolitise : le béton, l'acier, le plastique ne sont pas neutres, ils sont liés à des logiques d'extraction. À l'inverse, terre crue, bois, pierre, paille sont des choix de territoire. Pour ton projet : le geste le plus bas carbone est de garder ce qui existe (ne pas démolir, c'est du carbone évité). Ensuite, privilégier matériaux biosourcés et géosourcés, et intégrer le réemploi (réutiliser sur place ou via des plateformes les éléments déposés : structure, parquet, menuiseries, sanitaires). Le réemploi a un coût caché (dépose soignée, stockage, requalification) mais raconte une histoire que le neuf ne raconte pas.

2. Adaptation bioclimatique (« Habiter un climat », Clément Gaillard). La thèse : les techniques anciennes savaient travailler avec le soleil, le vent, l'eau, l'inertie, là où le bâtiment moderne s'en est coupé en comptant sur la technique et la climatisation. L'approche est offensive, pas défensive : bien orienter, ventiler naturellement, protéger du soleil d'été, capter celui d'hiver, jouer la masse thermique. Pour ton projet en rénovation : avant de chiffrer une pompe à chaleur, regarde ce que le bâtiment existant offre déjà (épaisseur des murs, orientation, ombrages) et amplifie-le. Moins de technique, plus de conception.

3. Le geste Kéré (la vidéo et le prix Pritzker 2022). Diébédo Francis Kéré, architecte burkinabè, construit avec les matériaux et les compétences locales, et fait participer les habitants dès le début. Sa méthode passive (doubles toitures, murs à inertie, ventilation transversale, tours à vent) répond au climat sans énergie. Ce qu'on en retient pour ta méthode d'apprentissage : observer plusieurs fois des projets réels, en comprendre les principes, puis les reproduire et innover. C'est exactement la posture de ton cas d'étude. Le détail qui compte : chez Kéré, la matière locale et la participation ne sont pas un supplément d'âme, elles sont le projet. Le récit et la technique ne font qu'un.

Synthèse des trois : garder l'existant (Choplin/Simay), le faire travailler avec son climat (Gaillard), en apprenant par l'observation de cas réels et en associant les gens (Kéré). C'est une ligne directrice cohérente, et c'est rare. Tiens-la.

---

## Partie C. Les montages gagnant-gagnant (alternatives à l'achat-négociation)

Le réflexe Nexity (offre de rachat, négociation adversariale) a une logique : maîtriser le foncier en pleine propriété pour capter toute la plus-value. Mais il bute sur deux choses, le prix du foncier et le rapport de force. Voici sept montages qui contournent ce schéma. Aucun n'est magique, chacun a son revers, je le signale.

1. Dissociation foncier / bâti via bail réel solidaire (BRS) et organisme foncier solidaire (OFS). Le propriétaire du sol (l'OFS) garde le foncier, l'occupant achète seulement le bâti, via un bail de longue durée. Le prix d'acquisition baisse de 20 à 40 % puisque le terrain sort de l'équation. Gagnant-gagnant : accession abordable pour l'occupant, foncier préservé dans la durée pour la collectivité. Revers : c'est encadré (plafonds de ressources, agrément OFS, conditions d'attribution durcies depuis 2025), donc ce n'est pas un outil libre, c'est un outil social.

2. Bail emphytéotique. Un propriétaire (souvent une collectivité, une institution religieuse, un bailleur) te confie un bien pour une longue durée (18 à 99 ans) contre un loyer modeste, à charge pour toi de le rénover et de l'exploiter. À la fin, le bien revient au propriétaire amélioré. Gagnant-gagnant : le propriétaire ne vend pas (il garde son patrimoine) mais le voit rénové sans débourser ; toi tu portes un projet sans acheter. Revers : tu ne possèdes jamais le foncier, ton modèle économique doit tenir sur la seule exploitation.

3. AMO pour un propriétaire existant. Plutôt que d'acheter, tu vends ton intelligence de montage. Un propriétaire (privé, copropriété, association, petite collectivité) a un bien à rénover mais pas les compétences pour piloter ; tu deviens son assistant à maîtrise d'ouvrage. Gagnant-gagnant : il garde son bien et sa plus-value, tu es rémunéré pour ton expertise sans capital. Revers : tu captures peu de valeur, et c'est un métier de service, pas de promotion. Mais c'est, très concrètement, le point d'entrée le plus réaliste pour toi à court terme.

4. Copromotion / co-développement. Tu t'associes au propriétaire foncier qui apporte son terrain en nature dans l'opération au lieu de le vendre. Il devient partenaire et touche une part du résultat. Gagnant-gagnant : il participe à la plus-value au lieu de la solder une fois pour toutes ; toi tu réduis le besoin de capital initial. Revers : il faut une structure juridique (souvent une société de projet) et une vraie confiance, donc du temps.

5. Réhabilitation de friches via le Fonds friches / Fonds vert. Les friches (industrielles, commerciales, ferroviaires) sont recensées sur Cartofriches et le recyclage est subventionné (études, dépollution, démolition, réhabilitation) dans la logique « zéro artificialisation nette ». Gagnant-gagnant : la collectivité résorbe une verrue, l'État cofinance, toi tu équilibres une opération autrement infaisable. Revers : maturité du dossier exigée (maîtrise foncière, programmation), pollution et aléas lourds, calendrier long.

6. Appels à projets type « Réinventer ». Des collectivités mettent en concours des sites publics : ce n'est pas le plus offrant qui gagne, c'est le meilleur projet (usage, qualité, ambition environnementale). C'est fait pour toi : ça récompense le récit et la conception, pas le chèque. Gagnant-gagnant : la ville obtient un projet ambitieux, le lauréat accède à un foncier rare à prix maîtrisé. Revers : concurrence d'équipes très structurées, dossier coûteux à produire, sans garantie.

7. Coopérative d'habitants / habitat participatif. Les futurs occupants se regroupent, portent collectivement le foncier et le projet, souvent avec un accompagnement professionnel. Gagnant-gagnant : maîtrise des coûts, projet sur-mesure, lien social ; toi tu interviens comme monteur/AMO. Revers : gouvernance lente, financement bancaire plus complexe.

Lecture transversale pour ton positionnement : les montages 3, 6 et 7 sont les plus alignés avec ton profil (peu de capital, forte valeur sur le récit et le montage). Les montages 1, 2, 5 demandent un partenaire institutionnel. Aucun ne demande d'écraser quelqu'un dans une négociation : c'est exactement ce que tu cherchais.

---

## Partie D. Cartographie des parties prenantes (le prisme « architecte d'expérience »)

Ton idée d'architecte d'expérience prend ici tout son sens. Chaque partie prenante a un langage, une peur, un désir. Tu ne convaincs pas en assénant le même argument à tous : tu captes d'abord ce qui « parle » à chacun (l'émotion, le récit), puis tu démontres (les chiffres, la preuve). Capter, puis révéler.

Pour chaque acteur : ce qui le motive, ce qui lui fait peur, le récit à capter en premier, la preuve à apporter ensuite.

### Le client / propriétaire

- Ce qui le motive : ne pas perdre, être respecté, voir son bien (souvent chargé d'histoire) prolongé plutôt que effacé.
- Ce qui lui fait peur : se faire avoir, perdre le contrôle, regretter.
- Récit à capter : « Votre bâtiment a une histoire, je ne viens pas l'effacer, je viens lui donner une suite. » C'est l'inverse exact de l'offre de rachat froide qui le réduit à un vendeur.
- Preuve à révéler ensuite : le montage qui le garde dans le jeu (copromotion, bail, AMO), le bilan qui montre que tout le monde y gagne.

### La collectivité (mairie, service urbanisme, élus)

- Ce qui la motive : un territoire qui s'améliore, des promesses tenues devant les électeurs, pas d'ennuis.
- Ce qui lui fait peur : le recours des riverains, la friche qui s'éternise, le projet hors-sol qui ne « parle » pas au quartier.
- Récit à capter : « Ce projet répond à un besoin du quartier que vous connaissez déjà. » Montre que tu as compris le territoire (données INSEE, usages observés).
- Preuve à révéler ensuite : la conformité au PLU, l'amélioration du DPE, la résorption d'une friche, l'absence d'artificialisation. Le langage ZAN leur parle directement.

### Le juridique / notaire

- Ce qui le motive : la sécurité de l'acte, l'absence de vice, la propreté du montage.
- Ce qui lui fait peur : le risque caché, le montage bancal qui explose dans deux ans.
- Récit à capter : « J'ai besoin que ce montage soit inattaquable, aidez-moi à le blinder. » Tu le mets en position d'expert protecteur, pas de simple exécutant.
- Preuve à révéler ensuite : un montage clair, des titres propres, des conditions suspensives bien posées.

### La technique / ingénierie (architecte, BET, bureau de contrôle)

- Ce qui la motive : le beau geste technique, le défi bien posé, la reconnaissance de leur métier.
- Ce qui lui fait peur : la commande floue, le client qui change d'avis, l'irréalisable déguisé en « simple ».
- Récit à capter : « Voici la contrainte, et je crois qu'elle cache une belle idée. Qu'en pensez-vous ? » Tu actives la fierté de métier (très exactement ce que Kéré fait avec les artisans locaux).
- Preuve à révéler ensuite : un programme clair, des hypothèses réalistes, le respect de leur expertise sur les points durs (structure, amiante).

### Le commercial / la direction (le comité d'engagement)

- Ce qui le motive : la marge, le risque maîtrisé, le différenciant qui fait vendre.
- Ce qui lui fait peur : l'opération qui ne sort pas, l'invendu, le dépassement.
- Récit à capter : « Ce projet a une histoire qui le vendra plus vite et plus cher que la moyenne. » Le récit est ici un actif commercial, pas une décoration.
- Preuve à révéler ensuite : le bilan prudent qui passe quand même, le point mort, la demande documentée (INSEE, DVF).

Principe d'ensemble : tu racontes un scénario, tu ne récites pas un argumentaire. La même opération se raconte cinq fois, en cinq récits différents, tous vrais. C'est ça, l'architecte d'expérience appliqué au montage.

---

## Partie E. Méthode pas-à-pas pour ton cas d'étude (sur papier)

### Comment repérer un bâtiment candidat près de chez toi

1. Choisis une commune que tu connais physiquement (tu dois pouvoir aller la voir). Le terrain compte, à la Kéré.
2. Ouvre Cartofriches et le Géoportail de l'urbanisme sur cette commune. Repère trois à cinq candidats : friche recensée, bâtiment muré, ancien équipement public désaffecté, immeuble vétuste en secteur tendu.
3. Pour chacun, fais une fiche express : parcelle (cadastre), zonage (PLU), prix du marché autour (DVF), risques (Géorisques), périmètre patrimonial (Atlas des patrimoines).
4. Choisis-en un. Critère : assez de contraintes pour être intéressant, pas assez pour être infaisable. Le bon cas d'étude n'est ni un terrain vierge ni une ruine classée.
5. Va le voir. Photographie. Observe l'orientation, le quartier, les flux, qui passe devant. C'est de l'observation Kéré, pas une formalité.

### Quoi collecter (la check-list de données)

- Cadastre : référence, surface parcelle.
- PLU : zonage + extrait du règlement de la zone + OAP éventuelle.
- DVF : trois à cinq transactions comparables récentes dans le secteur.
- INSEE : population, revenu médian, dynamique de la commune/IRIS.
- Géorisques : aléas.
- Atlas des patrimoines : ABF oui/non.
- Photos terrain + vues Géoportail (aérienne actuelle + historique).
- Si possible, plans d'origine (archives permis en mairie).

### Comment structurer la présentation finale (pitch promoteur)

Un pitch de développeur raconte une histoire en sept temps, dans cet ordre :
1. Le lieu et son récit (capter d'abord : pourquoi ce bâtiment mérite une suite).
2. Le constat (ce qui ne va plus, le besoin du territoire, données à l'appui).
3. L'idée (l'usage nouveau, en une phrase forte).
4. La faisabilité (réglementaire, technique, ce qu'on garde, ce qu'on transforme).
5. Le montage gagnant-gagnant (qui possède quoi, qui gagne quoi).
6. Le bilan (recettes prudentes, dépenses généreuses, la marge qui tient).
7. La preuve par les parties prenantes (un récit par acteur, partie D).

Garde l'émotion au début et à la fin, les chiffres au milieu. On capte, on démontre, on rouvre l'émotion.

### Squelette de cas d'étude pré-rempli (exemple plausible)

À décliner. L'exemple est crédible mais fictif, remplace chaque champ par ton vrai cas.

---

#### Cas d'étude : réhabilitation d'une ancienne école communale en tiers-lieu d'habitat et de travail

Lieu (fictif) : ancien groupe scolaire désaffecté, commune périurbaine de 6 000 habitants, secteur en regain démographique. Parcelle AB-214, 1 800 m² de terrain, bâti de 720 m² sur deux niveaux, vacant depuis 2018.

1. Le récit du lieu. Trois générations de la commune ont appris à lire ici. Le bâtiment est muré, mais tout le monde le connaît. Le démolir effacerait une mémoire ; le réhabiliter la prolonge. Carbone évité, mémoire gardée : un seul geste.

2. Le constat. La commune gagne des actifs qui télétravaillent et manquent de lieux pour le faire ; les jeunes ménages peinent à se loger (revenu médian INSEE à compléter, prix DVF du secteur à compléter). L'école vide se dégrade et coûte à la commune en gardiennage.

3. L'idée. Un tiers-lieu mixte : rez-de-chaussée en espace de coworking et services partagés, étage en quatre logements abordables. L'usage scolaire devient un usage de vie et de travail, sans changer l'âme du lieu.

4. La faisabilité. Zonage U (à confirmer au PLU), changement de destination (équipement vers mixte habitat/activité) soumis à permis de construire avec architecte. Diagnostics amiante et plomb à mener (bâti d'avant 1997). Structure conservée (murs porteurs en bon état apparent), planchers à renforcer. Bioclimatique : grande orientation sud des classes réemployée pour les logements (apport solaire d'hiver, casquettes pour l'été, principe Gaillard). Matériaux : conservation maximale, isolation biosourcée (paille/ouate), réemploi des menuiseries et parquets sur place (principe Choplin/Simay). DPE visé : passage de F/G à C.

5. Le montage. Pas d'achat. Bail emphytéotique de 40 ans entre la commune (propriétaire, qui garde son patrimoine) et une société de projet portée par toi + un partenaire investisseur. La commune ne débourse rien, récupère un bâtiment réhabilité et un lieu de vie ; tu portes l'exploitation. Alternative envisagée : candidature à un appel à projets « Réinventer » porté par l'intercommunalité.

6. Le bilan (à chiffrer, ordres de grandeur indicatifs). Coût travaux estimé 720 m² x 1 600 euros/m² = 1,15 M€ + honoraires 15 % + aléas 12 %. Recettes : loyers coworking + loyers logements abordables + éventuelle subvention Fonds vert sur le volet énergétique. Point mort à calculer ; viser un équilibre sur 40 ans cohérent avec le bail.

7. La preuve par parties prenantes.
   - Commune : tu résorbes une friche, tu crées du logement et de l'activité, sans vendre ni dépenser (récit : « votre école continue de servir »).
   - Habitants/occupants : un lieu chargé de sens, des loyers abordables (récit : « on travaille là où on a grandi »).
   - Architecte/BET : un défi de réemploi et de bioclimatique valorisant (récit : « la contrainte de l'existant cache une belle idée »).
   - Juridique : un bail emphytéotique propre, conditions suspensives sur diagnostics (récit : « blindons-le ensemble »).
   - Investisseur : un actif patrimonial, un récit qui sécurise la commercialisation (récit : « cette histoire se loue »).

---

## Pour démarrer concrètement cette semaine

1. Choisis ta commune et ouvre Cartofriches + Géoportail de l'urbanisme dessus (une heure).
2. Repère trois candidats, fais leurs fiches express (DVF, cadastre, zonage). Garde-en un.
3. Va le voir, photographie, observe à la Kéré.
4. Remplis le squelette de la partie E avec tes vraies données.
5. Monte le bilan dans un tableur, à la main, une fois.

Le reste (faisabilité fine, vrai montage, vrai permis) viendra quand tu auras un mandat réel. Pour l'instant, le cas d'étude est ton terrain d'entraînement, et c'est exactement comme ça que Kéré a appris : en regardant, puis en faisant.
