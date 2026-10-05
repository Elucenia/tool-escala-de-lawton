<!-- ELUCENIA technical documentation · escala-de-lawton · fr · no clinical/professional/rights approval -->

# Échelle de Lawton-Brody (AIVQ)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escala-de-lawton)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Téléphone

`tel`

- `a` — Utilise le téléphone de sa propre initiative (cherche et compose les numéros)
- `b` — Compose quelques numéros connus
- `c` — Répond, mais ne compose pas de numéro
- `d` — N’utilise pas le téléphone

### Courses

`compras`

- `a` — Fait tous ses achats sans aide
- `b` — Ne fait seul que de petits achats
- `c` — A besoin d’être accompagné pour tout achat
- `d` — Incapable de faire des achats

### Préparation des repas

`comida`

- `a` — Planifie, prépare et sert des repas adéquats sans aide
- `b` — Prépare les repas si les ingrédients lui sont fournis
- `c` — Réchauffe et sert des repas préparés, mais sans alimentation adéquate
- `d` — A besoin que d’autres préparent et servent les repas

### Tâches ménagères

`casa`

- `a` — S’occupe du domicile seul ou avec une aide occasionnelle pour les tâches lourdes
- `b` — Effectue des tâches légères (vaisselle, faire le lit)
- `c` — Effectue des tâches légères, mais ne maintient pas une propreté adéquate
- `d` — A besoin d’aide pour toutes les tâches
- `e` — Ne réalise aucune tâche ménagère

### Lessive

`roupa`

- `a` — Lave tous ses vêtements personnels
- `b` — Lave de petites pièces de linge
- `c` — Tout le linge est lavé par d’autres

### Transport

`transp`

- `a` — Utilise les transports en commun ou conduit sans aide
- `b` — Prend seul un taxi ou un VTC, mais n’utilise pas les transports en commun
- `c` — Utilise les transports en commun avec un accompagnant
- `d` — Ne se déplace qu’en taxi ou en voiture avec l’aide d’une autre personne
- `e` — Ne sort pas de chez soi

### Médicaments

`remedio`

- `a` — Prend seul ses médicaments à la dose et à l’heure correctes
- `b` — Prend ses médicaments si quelqu’un prépare les doses à l’avance
- `c` — Incapable de prendre seul ses médicaments

### Finances

`dinheiro`

- `a` — Gère seul ses finances
- `b` — Effectue les achats quotidiens, mais a besoin d’aide pour les opérations bancaires et les achats importants
- `c` — Incapable de gérer l’argent

## Édition de la méthode

Lawton–Brody 1969 : adaptation locale 8 domaines 0–1, total 0–8 pour les deux sexes ; pas la version initiale selon le sexe

## Formule documentée

Chaque activité vaut 1 (indépendant) ou 0 (dépendant) selon le niveau :

Téléphone : 1 aux trois premiers.

Courses et repas : 1 au premier seulement.

Ménage : 1 sauf « ne participe pas ».

Linge : 1 aux deux premiers.

Transport : 1 aux trois premiers.

Médicaments : 1 au premier seulement.

Finances : 1 aux deux premiers.

Total 0 (dépendant) à 8 (indépendant).

## Limites et population

Cette version de Lawton évalue huit activités instrumentales et utilise un total de 0 à 8 pour tous les genres, conformément aux recommandations HIGN de 2019 ; elle n’applique pas l’ancienne cotation masculine sur cinq items. Les recommandations consultées ne préconisent pas l’instrument pour les personnes âgées vivant en institution. Les réponses de la personne ou d’un informateur décrivent la fonction perçue et ne démontrent pas l’exécution réelle de chaque tâche ; elles peuvent surestimer ou sous-estimer les capacités et ne pas détecter de petits changements. Consignez l’identité du répondant et le contexte de l’évaluation.

## Références

- [Lawton MP, Brody EM. Assessment of older people: self-maintaining and instrumental activities of daily living. Gerontologist, 1969.](https://doi.org/10.1093/geront/9.3_Part_1.179)

- [HIGN,TryThis23,revised2019](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_23.pdf)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
