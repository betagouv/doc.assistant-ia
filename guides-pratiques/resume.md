---
description: >-
  Résumé intelligent de documents, de pages web et de conversations avec l'outil
  de résumé intégré.
icon: file-lines
---

# Résumé automatique

Votre assistant peut **résumer automatiquement** des documents, des pages web et même des conversations pour vous fournir les points clés de manière concise et efficace.

{% hint style="success" %}
**Gagnez du temps** : Obtenez l'essentiel de longs documents ou articles en quelques secondes.
{% endhint %}

## Comment utiliser le résumé

Glissez-déposez un document ou uploadez-le, puis demandez un résumé :

```
Vous : "Voici un rapport de 50 pages. Peux-tu me le résumer ?"
[Glissez-déposez le document]
Assistant : "Voici le résumé du rapport..."
```

### Personnalisation du résumé

Vous pouvez spécifier le format et la longueur :

```
Vous : "Résume ce document en 5 bullet points maximum"
Vous : "Fais un résumé détaillé avec des sections claires"
Vous : "Donne-moi juste les 3 points principaux"
```

### Extraction d'informations spécifiques

Demandez à l'assistant d'extraire des informations précises :

```
Vous : "Dans ce document, extrais toutes les dates importantes"
Vous : "Résume seulement la section sur la sécurité"
Vous : "Quels sont les 5 points d'action mentionnés ?"
```

### Résumé de documents

Avec l'outil **Summarize** :

* ✅ Traitement de PDFs, Word, Markdown, etc.
* ✅ Identification automatique des sections importantes
* ✅ Conservation de la structure (titres, sous-titres)
* ✅ Extraction des données clés (dates, noms, chiffres)

## Bonnes pratiques

### Pour de meilleurs résumés

1. **Soyez spécifique** sur ce que vous voulez résumer
2. **Précisez le format** souhaité (bullet points, paragraphe, etc.)
3. **Indiquez la longueur** si vous avez des préférences
4. **Demandez des points spécifiques** à inclure ou exclure
5. **Vérifiez les sources** citées dans le résumé

### Exemples de requêtes efficaces

| ❌ Moins bon            | ✅ Meilleur                                                 | Pourquoi      |
| ---------------------- | ---------------------------------------------------------- | ------------- |
| "Résume"               | "Résume ce document en 5 points clés"                      | Plus précis   |
| "Donne le résumé"      | "Fais un résumé structuré avec introduction et conclusion" | Plus détaillé |
| "Dis-moi ce qu'il y a" | "Quels sont les arguments principaux et les preuves ?"     | Plus ciblé    |

## Paramètres avancés

Le résumé est déclenché par l'Assistant en précisant les contraintes que vous avez émises. Vous pouvez donc, directement depuis le message où vous demandez un résumé, donner des instructions spécifiques pour le résumé.

### Niveau de détail

Contrôlez la granularité du résumé :

```
Vous : "Résume ce document avec un niveau de détail élevé"
Vous : "Donne-moi un aperçu très général"
```

### Focus thématique

Demandez un résumé axé sur un thème spécifique :

```
Vous : "Résume ce rapport en te concentrant sur les aspects financiers"
Vous : "Quels sont les points techniques mentionnés dans ce document ?"
```

### Langue du résumé

Demandez un résumé dans une langue spécifique :

```
Vous : "Résume ce document en anglais"
Vous : "Fais un résumé en français de cet article"
```

## Limites et conseils

### Ce que le résumé peut faire

✅ Comprendre le contenu principal\
✅ Identifier les points clés \
✅ Extraire des informations structurées \
✅ Synthétiser des informations multiples \
✅ Détecter les thèmes principaux

### Ce que le résumé ne peut pas faire

❌ Comprendre le contexte non écrit \
❌ Interpréter des informations ambiguës \
❌ Garantir l'exactitude à 100% \
❌ Remplacer une lecture complète pour les décisions critiques \
❌ Comprendre les nuances subjectives

### Conseils pour une utilisation optimale

1. **Pour les documents importants** : Lisez toujours le document complet après le résumé
2. **Pour les décisions critiques** : Vérifiez les informations dans la source originale
3. **Pour les informations sensibles** : Confirmez avec un expert humain
4. **Pour les documents techniques** : Demandez un résumé plus détaillé
5. **Pour les comparaisons** : Résumez plusieurs documents pour une vue d'ensemble

## Résolution des problèmes

<details>

<summary>Le résumé est trop court/vague</summary>

* Demandez un résumé plus détaillé
* Précisez le nombre de points souhaités
* Demandez un résumé structuré
* Essayez un autre modèle (Mistral Large donne des résumés plus complets)

</details>

<details>

<summary>Le résumé manque d'informations importantes</summary>

* Demandez spécifiquement les informations manquantes
* Vérifiez que le document a été correctement uploadé
* Essayez de résumer des sections spécifiques du document
* Demandez un résumé avec un focus particulier

</details>

<details>

<summary>Le résumé contient des informations incorrectes</summary>

* Vérifiez l'exactitude avec la source originale
* Donnez un retour négatif (👎) avec une explication
* Demandez à l'assistant de vérifier une information spécifique
* Signalez le problème à votre administrateur

</details>

<details>

<summary>Le résumé est trop long</summary>

* Demandez un résumé plus court
* Précisez un nombre maximum de points
* Demandez uniquement les points principaux
* Utilisez des bullet points pour plus de concision

</details>

## Ressources similaires

{% content-ref url="../guides/documents.md" %}
[documents.md](../guides/documents.md)
{% endcontent-ref %}

{% content-ref url="recherche-web.md" %}
[recherche-web.md](recherche-web.md)
{% endcontent-ref %}
