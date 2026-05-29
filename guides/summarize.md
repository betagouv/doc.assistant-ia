---
description: >-
  Résumé intelligent de documents, de pages web et de conversations avec
  l'outil de résumé intégré.
icon: file-lines
---

# Résumé automatique

Votre assistant peut **résumer automatiquement** des documents, des pages web et même des conversations pour vous fournir les points clés de manière concise et efficace.

{% hint style="success" %}
**Gagnez du temps** : Obtenez l'essentiel de longs documents ou articles en quelques secondes.
{% endhint %}

## Comment utiliser le résumé

### Méthode 1 : Résumé de documents

Glissez-déposez un document ou uploadez-le, puis demandez un résumé :

```
Vous : "Voici un rapport de 50 pages. Peux-tu me le résumer ?"
[Glissez-déposez le document]
Assistant : "Voici le résumé du rapport..."
```

### Méthode 2 : Résumé de pages web

L'assistant peut résumer des pages web trouvés via la recherche :

```
Vous : "Recherche web sur les dernières avancées en IA et résume les résultats"
Assistant : "Voici un résumé des dernières avancées..."
```

Ou avec une URL spécifique :
```
Vous : "Résume l'article à cette URL : https://exemple.com/article-long"
Assistant : "Voici le résumé de l'article..."
```

### Méthode 3 : Résumé de conversations

Résumez une conversation en cours ou passée :

```
Vous : "Résume ce que nous avons discuté jusqu'à présent"
Assistant : "Voici les points principaux de notre conversation..."
```

## Fonctionnalités de résumé

### Types de résumés

| Type | Description | Cas d'usage |
|------|-------------|------------|
| **Résumé court** | 3-5 points clés | Aperçu rapide |
| **Résumé détaillé** | 10-15 points avec contexte | Analyse approfondie |
| **Résumé structuré** | Avec titres et sections | Documents formels |
| **Résumé en bullet points** | Liste de points | Présentations |
| **Résumé en paragraphe** | Texte continu | Rapports |

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

## Outils de résumé intégrés

### Résumé de documents

Avec l'outil **Summarize** :
- ✅ Traitement de PDFs, Word, Markdown, etc.
- ✅ Identification automatique des sections importantes
- ✅ Conservation de la structure (titres, sous-titres)
- ✅ Extraction des données clés (dates, noms, chiffres)

### Résumé de résultats de recherche web

Avec Brave Search + Summarize :
- ✅ Résumé automatique des résultats
- ✅ Synthèse multi-sources
- ✅ Détection des informations contradictoires
- ✅ Hiérarchisation par pertinence

### Résumé de conversations

- ✅ Conservation du contexte
- ✅ Identification des décisions et actions
- ✅ Groupement par thèmes
- ✅ Mise en évidence des points non résolus

## Bonnes pratiques

### Pour de meilleurs résumés

1. **Soyez spécifique** sur ce que vous voulez résumer
2. **Précisez le format** souhaité (bullet points, paragraphe, etc.)
3. **Indiquez la longueur** si vous avez des préférences
4. **Demandez des points spécifiques** à inclure ou exclure
5. **Vérifiez les sources** citées dans le résumé

### Exemples de requêtes efficaces

| ❌ Moins bon | ✅ Meilleur | Pourquoi |
|-------------|-----------|---------|
| "Résume" | "Résume ce document en 5 points clés" | Plus précis |
| "Donne le résumé" | "Fais un résumé structuré avec introduction et conclusion" | Plus détaillé |
| "Dis-moi ce qu'il y a" | "Quels sont les arguments principaux et les preuves ?" | Plus ciblé |

## Paramètres avancés

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

## Exemples concrets

### Scénario 1 : Résumé de rapport technique

**Vous** : "Voici un rapport technique de 100 pages sur l'architecture de notre système. Peux-tu me le résumer en me concentrant sur les parties concernant la sécurité et la scalabilité ?"

**Assistant** :
```
Résumé du rapport technique - Focus Sécurité et Scalabilité

**Sécurité** :
- 🔒 Protocole de chiffrement : AES-256 pour toutes les communications
- 🛡️ Authentification : OAuth 2.0 + MFA obligatoire
- 🔍 Audit : Journaux conservés 90 jours, analyses hebdomadaires

**Scalabilité** :
- 📈 Architecture : Microservices avec Kubernetes
- ⚡ Capacité : Jusqu'à 10 000 requêtes/seconde
- 💾 Stockage : Base de données distribuée avec réplication multi-région

**Recommandations** :
1. Mettre à jour les certificats SSL trimestriellement
2. Augmenter la capacité de stockage de 20% d'ici Q3
```

### Scénario 2 : Résumé de recherche web

**Vous** : "Recherche les dernières nouvelles sur l'IA générative et résume en 3 points"

**Assistant** :
```
Dernières nouvelles sur l'IA générative (juin 2025) :

1. **Nouveau modèle Mistral 2** : Annoncé avec 200M de paramètres, performances améliorées de 40% (Source : Mistral AI)
2. **Régulation européenne** : L'AI Act entre en vigueur, classification par niveau de risque (Source : UE)
3. **Investissements** : +30% d'investissements dans l'IA générative par rapport à 2024 (Source : CB Insights)

Souhaitez-vous des détails sur un de ces points ?
```

### Scénario 3 : Résumé de conversation

**Vous** : "Nous avons discuté de beaucoup de choses. Peux-tu me faire un récapitulatif des décisions prises ?"

**Assistant** :
```
Récapitulatif des décisions de cette conversation :

✅ **Décisions** :
1. Adopter le modèle Mistral Large pour le projet Alpha
2. Planifier une réunion de suivi jeudi à 14h
3. Allouer un budget de 5000€ pour les outils d'IA

⏳ **En attente** :
1. Validation par l'équipe juridique du contrat
2. Retour du client sur la proposition technique

❓ **Questions ouvertes** :
1. Quel fournisseur cloud utiliser ?
2. Faut-il former l'équipe sur les nouveaux outils ?
```

## Intégration avec d'autres outils

### Résumé + Recherche web

Combinez le résumé avec la recherche pour des réponses complètes :

```
Vous : "Recherche les dernières bonnes pratiques en cybersécurité et résume-les"
```

### Résumé + Documents

Résumez et comparez avec vos documents internes :

```
Vous : "Résume ce document et compare avec les standards de l'industrie"
```

### Résumé + Collection

Résumez tous les documents d'une collection :

```
Vous : "Résume tous les documents de la collection 'Projet Beta'"
```

## Limites et conseils

### Ce que le résumé peut faire

✅ Comprendre le contenu principal
✅ Identifier les points clés
✅ Extraire des informations structurées
✅ Synthétiser des informations multiples
✅ Détecter les thèmes principaux

### Ce que le résumé ne peut pas faire

❌ Comprendre le contexte non écrit
❌ Interpréter des informations ambiguës
❌ Garantir l'exactitude à 100%
❌ Remplacer une lecture complète pour les décisions critiques
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

- Demandez un résumé plus détaillé
- Précisez le nombre de points souhaités
- Demandez un résumé structuré
- Essayez un autre modèle (Mistral Large donne des résumés plus complets)

</details>

<details>
<summary>Le résumé manque d'informations importantes</summary>

- Demandez spécifiquement les informations manquantes
- Vérifiez que le document a été correctement uploadé
- Essayez de résumer des sections spécifiques du document
- Demandez un résumé avec un focus particulier

</details>

<details>
<summary>Le résumé contient des informations incorrectes</summary>

- Vérifiez l'exactitude avec la source originale
- Donnez un retour négatif (👎) avec une explication
- Demandez à l'assistant de vérifier une information spécifique
- Signalez le problème à votre administrateur

</details>

<details>
<summary>Le résumé est trop long</summary>

- Demandez un résumé plus court
- Précisez un nombre maximum de points
- Demandez uniquement les points principaux
- Utilisez des bullet points pour plus de concision

</details>

## Ressources connexes

{% content-ref url="documents.md" %}
[documents.md](documents.md)
{% endcontent-ref %}

{% content-ref url="web-search.md" %}
[web-search.md](web-search.md)
{% endcontent-ref %}

{% content-ref url="collections.md" %}
[collections.md](collections.md)
{% endcontent-ref %}
