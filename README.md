# Réglementation des courtiers en assurance et en crédit en France

Nom technique : `courtier-assurance-credit-france`

Corpus réglementaire français pour les intermédiaires en assurance (IAS) et en
opérations de banque et services de paiement (IOBSP) immatriculés à l'ORIAS,
au format skill exploitable par un agent (Claude Code, Cowork, Cursor, Codex).

**Périmètre.** Courtiers, agents généraux et mandataires relevant des statuts
IAS et IOBSP. Ne couvre pas les autres professions dites de courtage : agents
immobiliers relevant de la loi Hoguet, courtiers en travaux, en énergie ou en
marchandises. Le crédit immobilier, lui, est au cœur du périmètre : c'est une
opération de banque, donc une activité IOBSP.

Chaque fiche répond à une question réellement posée par un professionnel, et
rattache la réponse au texte officiel qui la fonde.

## Ce que couvre le corpus

| Fiche | Question | État |
|---|---|---|
| `commun/quelle-obligation-me-concerne.md` | Quelle obligation me concerne selon mon immatriculation ? | ✅ |
| `iobsp/formation-continue-7h.md` | Combien d'heures pour un IOBSP ? | ✅ |
| `ias/formation-continue-15h.md` | Combien d'heures DDA pour un IAS ? | ✅ |
| `commun/formation-a-distance.md` | Peut-on valider ses heures à distance ? | ✅ |
| `commun/formations-eligibles.md` | Quelles formations comptent ? | ✅ |
| `iobsp/categories-iobsp.md` | COBSP, MOBSP, MIOBSP, MOBSPL | ✅ |
| `ias/categories-ias.md` | COA, AGA, MIA, MA | ✅ |
| `iobsp/capacite-professionnelle.md` | Niveaux I, II, III | ✅ |
| `ias/mandataire-mia.md` | Un MIA est-il soumis aux 15 h ? | ✅ |
| `iobsp/obligation-sans-credit-immobilier.md` | IOBSP sans crédit immo : quelle durée ? | ✅ |
| `commun/double-statut-ias-iobsp.md` | Double statut : cumul des obligations ? | ✅ |
| `iobsp/reforme-20-novembre-2026.md` | Ce qui change au 20/11/2026 | ✅ |
| `commun/qui-peut-dispenser.md` | Qui peut dispenser ? Qualiopi requis ? | ✅ |
| `commun/justificatifs-et-controle.md` | Quels justificatifs, qui contrôle ? | ✅ |
| `commun/modifier-categories-orias.md` | Ajouter/supprimer une catégorie ORIAS | ✅ |
| `commun/reclamations-mediation-client.md` | Réclamations et médiateur | ✅ |
| `commun/remunerations-honoraires-commissions.md` | Que dire au client sur la rémunération ? | ✅ |
| `commun/lcb-ft-obligations-courtier.md` | Qui est assujetti à la LCB-FT ? | ✅ |
| `commun/responsabilite-du-mandant.md` | Qui répond des actes d'un MIA/MIOBSP ? | ✅ |
| `ias/qui-doit-suivre-15h.md` | Dirigeants, commerciaux, back-office : qui doit les 15 h ? | ✅ |
| `ias/iata-exemption.md` | Un IATA est-il dispensé des 15 h ? | ✅ |
| `ias/indicateur-affaires.md` | Un indicateur d'affaires doit-il s'immatriculer ? | ✅ |
| `ias/gestion-sinistres-fonctions-support.md` | Sinistres et back-office : dans ou hors des 15 h ? | ✅ |
| `iobsp/programme-formation-continue.md` | Quel programme pour la formation continue IOBSP ? | ✅ |
| `iobsp/salaries-concernes-formation-continue.md` | Quels salariés d'un IOBSP sont concernés ? | ✅ |
| `commun/qcm-evaluation-obligatoire.md` | Un QCM final est-il obligatoire ? | ✅ |
| `commun/formation-audio-conforme.md` | Une formation audio peut-elle compter ? | ✅ |
| `commun/formation-initiale-vs-formation-continue.md` | L'initiale remplace-t-elle la continue ? | ✅ |
| `commun/obligation-individuelle-non-mutualisable.md` | Les heures se mutualisent-elles ? | ✅ |
| `commun/immatriculation-initiale-orias.md` | Comment s'immatriculer à l'ORIAS ? | ✅ |
| `commun/renouvellement-annuel-orias.md` | Quand et comment renouveler l'ORIAS ? | ✅ |
| `commun/association-professionnelle-agreee.md` | Qui doit adhérer à une association agréée ? | ✅ |
| `commun/rc-pro-garantie-financiere.md` | RC pro et garantie financière : qui, combien ? | ✅ |
| `commun/honorabilite-professionnelle.md` | Qui est soumis à l'honorabilité ? | ✅ |

Toutes les fiches sont rédigées après vérification directe de leurs articles
sur Légifrance et ont fait l'objet d'une relecture croisée entre agents.
Statut : brouillons jusqu'à validation du mainteneur ; aucune fiche n'est
publiée sans validation. Règle de process retenue : une fiche nouvelle entre
dans le corpus avec un ✅ « rédigée et vérifiée », mais seule la validation du
mainteneur autorise sa publication.

## Évaluations

`_meta/evals.md` contient quinze questions réelles, la réponse attendue et le
piège que commettent les réponses non sourcées. Elles permettent de mesurer
l'apport du skill et servent de test de non-régression après chaque mise à jour.

## Avertissement

Ce corpus est une aide à la compréhension de la réglementation. Il ne constitue
pas un conseil juridique et ne se substitue ni à un professionnel du droit, ni à
l'association professionnelle agréée par l'ACPR dont dépend l'intermédiaire, ni
à l'ACPR elle-même.

Les textes évoluent. Chaque fiche porte sa date de dernière vérification.

## Version canonique

Les fiches sont publiées et mises à jour sur **https://dcidda.fr/ressources/**,
qui est la source canonique. Ce dépôt en est le miroir machine-readable.

Chaque fiche porte son lien canonique, en tête dans son champ `canonical` et en
pied de page. **En cas d'écart entre ce dépôt et dcidda.fr, c'est dcidda.fr qui
fait foi** : le site porte la date de dernière vérification effective.

**Règle de publication : jamais le miroir avant la page canonique.** Un lien
« Version canonique » pointant vers une page inexistante détruit la crédibilité
qu'il est censé porter. Cette condition est remplie depuis le 11 septembre 2026,
date de mise en ligne des 34 fiches sur dcidda.fr — d'où la publication de ce
miroir.

Corollaire pour les contributions : une fiche ne doit jamais être ajoutée ici
sans que sa page canonique existe. Vérifier l'URL avant tout ajout.

## État de vérification

**1er septembre 2026.** Trois fiches rédigées et vérifiées, table des sources
close (les cinq entrées « non vérifié » de la v7 ont été levées, liens de veille
complétés).

**8 septembre 2026.** Les dix fiches restantes rédigées après vérification
directe sur Légifrance : R. 511-2, L. 511-1, L. 511-2, R. 512-13-1
(C. assurances), la section complète R. 519-1 à R. 519-18 (CMF, dont R. 519-4
et les articles de capacité professionnelle), et A. 512-1 à A. 512-8
(arrêtés). Constat au passage : R. 519-2 et R. 519-3 sont affichés « en
vigueur jusqu'au 20/11/2026 ».

**8–9 septembre 2026 (suite).** Relecture croisée avec l'audit ChatGPT :
correction d'une erreur (association obligatoire des courtiers IOBSP,
L. 519-11) et de quatre nuances ; puis cinq fiches « vie commerciale »
ajoutées (catégories ORIAS, réclamations/médiation, rémunération, LCB-FT,
responsabilité du mandant) après lecture de L. 546-1 à L. 546-4, L. 521-2 et
L. 521-3, R. 519-19 à R. 519-26, L. 519-6, L. 519-3-2, L. 519-3-4 et
L. 561-2 (rédaction du 05/08/2026, loi n° 2026-725). Enfin, les 15 fiches
contribuées par Codex (4 IAS, 2 IOBSP, 9 communes dont les 5 fiches
administratives ORIAS/RC/honorabilité) ont été fusionnées après relecture
croisée, avec deux retouches (analogie secrétariat/comptabilité qualifiée,
R. 511-3 ajouté pour la commission d'apport). Une dernière passe a supprimé
deux raccourcis non textuels sur la LCB-FT et la multi-inscription — le corpus
compte 33 fiches.

**Réserve de la v7 levée.** L'arrêté du 14 août 2026 (NOR ECOT2621748A, JORF
n° 0196 du 23 août 2026) avait été référencé sans être lu, Légifrance bloquant
la récupération automatisée. Son contenu a été lu intégralement le 1er septembre
2026. Ce qu'il confirme : les 7 heures demeurent applicables au crédit
immobilier (chapitre III), une durée suffisante adaptée vaut pour le crédit à la
consommation (chapitre II) ; les références sont recodifiées (D. 313-10-2 →
D. 314-23, D. 313-10-4 → D. 314-25) et l'annexe de programme est remplacée.
Entrée en vigueur au 20 novembre 2026, les contrats en cours restant régis par
le droit antérieur.

## Maintenance

La veille lit la colonne « Veille » de `sources/sources-officielles.md`, compare
la version en vigueur et ouvre une issue en cas d'écart. **L'agent détecte,
l'humain écrit** : aucun modèle ne réécrit un article de code dans ce dépôt. Les
corrections passent par pull request, jamais par commit direct.

Échéances suivies : **20 novembre 2026** (réforme crédit) et **10 juillet
2027** (nouvelle rédaction programmée de L. 561-2).

## Contribuer

Une erreur, un article périmé, une source plus précise : ouvrez une issue en
citant le texte. Les corrections sourcées sont intégrées en priorité.

---

*Maintenu par dcidda.fr — organisme de formation spécialisé dans la formation
continue des intermédiaires en assurance et en crédit. Déclaration d'activité
enregistrée sous le n° 76 82 01459 82 auprès du préfet de région Occitanie.
Cet enregistrement ne vaut pas agrément de l'État.*
