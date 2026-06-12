---
description: >-
  Comprenez ce que l'assistant peut faire et les limites inhérentes à son
  fonctionnement basé sur le langage.
icon: brain
---

# Capacités et limites

L'assistant fonctionne comme un système intelligent basé sur le traitement du langage naturel. Il excelle dans l'analyse, l'explication et la génération de texte, mais fonctionne dans des contraintes fondamentales.

## Ce que l'assistant comprend

L'assistant traite l'information **textuelle** :

* Il lit et comprend le code
* Il explique des concepts techniques
* Il génère du texte, du code, ou de la documentation
* Il répond à des questions basées sur les données disponibles



## Ce que l'assistant peut faire

L'assistant a à sa disposition plusieurs outil.

Il peut analyser les documents que vous avez téléverser de 3 manières différentes :&#x20;

* **Résumer** la totalité en suivant les instructions que vous fournissez (en 2 paragraphes, en espagnol...)
* **Utiliser la totalité du document** pour vous répondre (si le document fait environ moins de 5 pages de texte)
* Sélectionner les **quelques paragraphes** les **plus pertinents** pour s'en inspirer à la génération de votre réponse.

{% content-ref url="../guides/documents.md" %}
[documents.md](../guides/documents.md)
{% endcontent-ref %}

Il peut également déclencher une ou plusieurs recherches internet si les paramètres le permettent et que le modèle en rédige la demande. Nous déclenchons alors une recherche web, et le modèle se base sur les résultats de celle-ci pour générer votre réponse.

{% content-ref url="../guides-pratiques/recherche-web.md" %}
[recherche-web.md](../guides-pratiques/recherche-web.md)
{% endcontent-ref %}



## Ce que l'assistant ne peut pas faire

L'assistant **ne peut pas** :

* **Exécuter du code directement** : Il ne peut pas lancer de programmes, de scripts, ou d'outils sur votre machine. Lorsqu'il propose du code, c'est à vous de l'exécuter dans votre environnement.
* **Accéder à des ressources externes** : Sans configuration explicite, il ne peut pas se connecter à des bases de données, des API externes, ou des services en ligne en dehors de son contexte autorisé.
* **Modifier ou générer des fichiers** : Pour l'instant, l'Assistant ne fait que générer le texte que vous pouvez ensuite insérer dans des fichiers.&#x20;
* **Effectuer des actions physiques** : Il ne peut pas interagir avec le matériel, les périphériques, ou effectuer des opérations système.

## Limites techniques actuelles

{% hint style="warning" %}
**Capacité documentaire** : Il y a actuellement une limite de **10 documents de 10 Mo chacun par projet**. Cette limite est due au dimensionnement actuel du service et sera amenée à évoluer positivement très rapidement.
{% endhint %}

## Pourquoi ces limites ?

Ces restrictions existent par **conception de sécurité**, ainsi que d'avancée sur la feuille de route (voir section ci-dessous) :

* **Isolation** : L'assistant fonctionne dans un environnement contrôlé qui l'empêche d'affecter directement votre système.
* **Transparence** : Vous gardez toujours le contrôle sur ce qui est exécuté ou modifié.
* **Prévisibilité** : Le comportement de l'assistant reste dans le domaine de la manipulation de texte et d'information, pas dans celui de l'exécution arbitraire.

Quand l'assistant vous propose une solution impliquant du code, il vous guide **étape par étape** et c'est à vous de décider de l'exécuter dans votre environnement local.



## Évolution à venir

À terme, l'assistant pourra **exécuter du code dans un environnement sécurisé et isolé** pour réaliser des analyses statistiques, générer des documents, ou effectuer des traitements de données. Ces fonctionnalités seront activées progressivement selon des protocoles de sécurité stricts.

Consultez la [feuille de route](feuille-de-route.md) pour connaître les dates prévisionnelles de ces évolutions.

{% content-ref url="feuille-de-route.md" %}
[feuille-de-route.md](feuille-de-route.md)
{% endcontent-ref %}
