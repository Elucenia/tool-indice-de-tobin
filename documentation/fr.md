<!-- ELUCENIA technical documentation · indice-de-tobin · fr · no clinical/professional/rights approval -->

# Indice de Tobin (respiration rapide et superficielle)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/indice-de-tobin)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Fréquence respiratoire spontanée

`fr`

respirations/min · intervalle: 1–80

### Volume courant spontané

`vt`

mL · intervalle: 50–1500

## Édition de la méthode

RSBI/Yang–Tobin 1991 : f/VT, VT en litres ; ne pas confondre avec mL

## Formule documentée

f/VT = fréquence respiratoire (resp/min) ÷ volume courant (litres).

## Limites et population

Le RSBI a été étudié comme prédicteur du résultat des tentatives de sevrage ventilatoire. Le résultat dépend des conditions et de la technique de mesure et ne confirme pas seul la capacité de protection des voies aériennes ou la sécurité de l’extubation. Un indice favorable n’équivaut pas à un succès garanti.

## Références

- [Yang KL, Tobin MJ. A prospective study of indexes predicting the outcome of trials of weaning from mechanical ventilation. N Engl J Med, 1991.](https://doi.org/10.1056/NEJM199105233242101)

- [Boles JM et al. Weaning from mechanical ventilation. Eur Respir J, 2007.](https://doi.org/10.1183/09031936.00010206)

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

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

En dessous de 105 : favorise le succès du sevrage


### 2

105 ou plus : prédit l’échec du sevrage


### 3

105 ou plus : prédit l’échec du sevrage

