# Contribuer au corpus

Ce dépôt est le miroir machine-readable de **https://dcidda.fr/ressources/**,
qui est la source canonique. Les règles ci-dessous ne sont pas des préférences
de style : chacune vient d'une erreur réellement commise sur ce corpus.

---

## 1. Toute affirmation porte l'article qui la fonde

Une règle énoncée sans son article est incomplète, même si elle est exacte.

Ordre de préférence des sources :

1. le texte lui-même sur Légifrance ;
2. une publication officielle : ORIAS, ACPR, Direction générale du Trésor ;
3. rien d'autre. Les sites d'organismes de formation — y compris celui du
   mainteneur — ne sont pas des sources de droit.

## 2. Lire le texte, pas une source secondaire

Ne jamais déduire le contenu d'un article de son intitulé, du titre d'une
annexe, ni de ce qu'en dit un autre document. Ouvrir l'article.

Cette règle vient d'une erreur : l'article R. 519-12 CMF a été présenté comme
ne visant que la formation initiale, sur la foi du titre d'une annexe. Son I
couvre expressément la formation continue et son IV fonde l'attestation. Vingt-six
fichiers ont été corrigés dans le mauvais sens avant que quelqu'un n'ouvre
l'article.

## 3. Identifier les arrêtés par leur NOR, jamais par leur seule date

**Quatre arrêtés sont datés du 9 juin 2016** et touchent l'intermédiation. Un
seul est abrogé.

| Objet | NOR | Identifiant | État au 11/09/2026 |
|---|---|---|---|
| application de l'article D. 313-10-2 C. consommation | FCPT1610795A | JORFTEXT000032675834 | en vigueur |
| registre unique | FCPT1613759A | JORFTEXT000032675862 | en vigueur |
| programmes de formation des IOBSP | FCPT1610790A | JORFTEXT000032675903 | **abrogé** depuis le 30/07/2022 |
| capacité professionnelle des IOBSP | FCPT1610793A | JORFTEXT000032675950 | en vigueur |

Écrire « l'arrêté du 9 juin 2016 » sans préciser lequel expose à deux erreurs
symétriques : citer un texte mort, ou croire abrogé un texte vivant. **Les deux
se sont produites.** Les identifiants `…834` et `…903` ne diffèrent que par
quelques chiffres — vérifier l'identifiant, pas la date.

## 4. Qualifier le registre de chaque affirmation

- **Obligation** — imposée par un texte, avec l'article.
- **Interprétation** — position de l'ACPR, d'une association agréée ou d'une
  doctrine. À présenter comme telle, jamais comme la loi.
- **Pratique de place** — usage répandu sans fondement textuel. Le signaler,
  c'est la principale source d'erreur du secteur.

## 5. Aucun seuil opérationnel dans le corpus

Le corpus énonce la règle telle que le texte l'écrit — par exemple « le contrôle
est réussi lorsque le nombre de bonnes réponses **excède 70 %** » (arrêté du
18 juillet 2022, art. 6). Il ne porte aucune traduction chiffrée détachée de son
barème.

Interdit : « le seuil est de 15/20 ». Le chiffre y remplace le texte, et devient
faux dès qu'on change le nombre de questions.

Autorisé et utile : « sur vingt questions, quatorze bonnes réponses font
exactement 70 % et sont donc insuffisantes ; il en faut quinze ». Le texte reste
la règle, le chiffre n'est qu'une vérification arithmétique.

Là où aucun texte n'impose de seuil — c'est le cas de la formation continue DDA,
le Code des assurances n'en fixant aucun — tout chiffre affiché est un choix
d'organisme et doit être nommé comme tel.

## 6. Les affirmations négatives sont bornées

« Aucun texte ne fixe de durée » ne peut jamais être définitif. Préciser le
périmètre — formation continue ou formation d'accès — et la date des sources
consultées. Une affirmation négative vaut jusqu'à preuve d'un texte contraire.

## 7. Lien canonique obligatoire

Chaque fiche porte son champ `canonical` en tête et le rappel en pied de page.

**Ne jamais ajouter une fiche ici sans que sa page canonique existe sur
dcidda.fr.** Vérifier l'URL avant tout ajout : un lien canonique vers une page
inexistante détruit la crédibilité qu'il est censé porter.

En cas d'écart entre ce dépôt et dcidda.fr, **c'est dcidda.fr qui fait foi**.

## 8. Format imposé d'une fiche

Frontmatter : `canonical`, `question`, `statut`, `derniere_verification`.

Sections, dans cet ordre : **Réponse courte**, **En pratique**, **Ce que ça ne
couvre pas**, **Base juridique**, **Sources officielles**, **Dernière
vérification**.

Une fiche répond à une question réellement posée, pas à un article.

## 9. Dater ce qui a été vérifié, et distinguer de ce qui ne l'a pas été

La section « Dernière vérification » dit **ce qui a été relu, quand, et ce qui
ne l'a pas été**. « Les autres articles sont repris de fiches vérifiées le
8 septembre 2026, sans relecture nouvelle » est une mention utile, pas un aveu
de faiblesse.

## 10. En cas de doute, ne pas trancher

Signaler l'ambiguïté plutôt que de la résoudre au jugé. Une qualification
inventée est plus coûteuse qu'une question posée : elle a l'apparence d'une
réponse et personne ne la revérifie.

---

## Signaler une erreur

Ouvrir une issue en indiquant la fiche, l'affirmation contestée, et l'article ou
la source qui la contredit. Une contestation sans source ne peut pas être
traitée.
