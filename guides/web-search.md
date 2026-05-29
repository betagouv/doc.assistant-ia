---
description: >-
  Recherche web en temps réel avec Brave Search et résumé automatique des résultats
  pour des réponses rapides et précises.
icon: globe
---

# Recherche web

Votre assistant peut effectuer des **recherches web en temps réel** pour trouver des informations à jour, avec résumé automatique des résultats grâce à l'intégration avec Brave Search.

{% hint style="success" %}
**Recherche intelligente** : Votre assistant comprend votre intention de recherche et reformule les requêtes pour de meilleurs résultats.
{% endhint %}

## Comment utiliser la recherche web

### Méthode 1 : Commande explicite

Demandez explicitement à l'assistant de faire une recherche web :

```
Vous : "Recherchez sur le web : quelles sont les dernières actualités sur l'IA en 2025 ?"
Assistant : "Je vais effectuer une recherche web pour vous..."
```

### Méthode 2 : Questions nécessitant des infos récentes

L'assistant peut **automatiquement** déclencher une recherche web si :
- Votre question porte sur des **actualités récentes**
- Votre question nécessite des **informations à jour**
- La réponse n'est pas disponible dans la base de connaissances

Exemples :
```
Vous : "Quels sont les derniers résultats des élections 2025 ?"
Vous : "Quel est le taux de change euro/dollar aujourd'hui ?"
Vous : "Quelles sont les prévisions météo pour demain ?"
```

### Méthode 3 : Combinaison avec des documents

L'assistant peut **combiner** recherche web et documents internes :

```
Vous : "Quelles sont les dernières tendances en cybersécurité et comment notre politique interne les traite-t-elle ?"
Assistant : "Je vais rechercher les tendances récentes ET consulter nos documents internes..."
```

## Fonctionnalités avancées

### Résumé automatique des résultats

Les résultats de recherche sont **automatiquement résumés** pour vous fournir :

- 📌 **Points clés** extraits des sources
- 🔗 **Liens pertinents** vers les articles complets
- 📊 **Synthèse** des informations principales
- ⏱️ **Gain de temps** : pas besoin de lire tous les articles

Exemple de sortie :
```
Assistant : "Voici les points clés sur les tendances IA 2025 :

1. **Modèles multi-modaux** : Combinaison de texte, image et audio (Source : TechCrunch)
2. **Agents autonomes** : Développement rapide des agents IA autonomes (Source : MIT Technology Review)
3. **Régulation** : Nouveaux cadre légaux en Europe et aux États-Unis (Source : Reuters)

Souhaitez-vous que je développe un de ces points ?"
```

### Filtrage des résultats

L'assistant filtre automatiquement :
- ✅ **Sources fiables** (médias reconnus, sites gouvernementaux)
- ✅ **Contenu récent** (priorité aux informations à jour)
- ✅ **Pertinence** (correspondance avec votre question)
- ❌ **Contenu non pertinent**
- ❌ **Sources peu fiables**

### Personnalisation de la recherche

Vous pouvez affiner votre recherche avec des paramètres :

| Paramètre | Exemple | Description |
|-----------|---------|-------------|
| **Site spécifique** | "site:github.com" | Recherche sur un site particulier |
| **Période** | "après:2025-01-01" | Résultats après une date |
| **Type de fichier** | "filetype:pdf" | Fichiers PDF uniquement |
| **Langue** | "lang:fr" | Résultats en français |

Exemple :
```
Vous : "Recherchez site:gouv.fr après:2025-01-01 lang:fr les dernières lois sur l'IA"
```

## Intégration Brave Search

Votre assistant utilise **Brave Search** pour :

- 🛡️ **Respect de la vie privée** : Pas de tracking des utilisateurs
- 🚀 **Rapidité** : Résultats instantanés
- 🌍 **Couverture mondiale** : Accès à des sources internationales
- 🔍 **Index complet** : Moteur de recherche indépendant

### Pourquoi Brave ?

- **Ne vend pas vos données** à des annonceurs
- **Pas de bulle de filtres** : résultats non personnalisés
- **Transparence** : politique claire sur la confidentialité
- **Indépendance** : pas dépendant des géants du web

## Bonnes pratiques

### Formuler de bonnes requêtes

| ❌ À éviter | ✅ Recommandé | Pourquoi |
|-----------|--------------|---------|
| "IA" | "Quelles sont les dernières avancées en IA générative en 2025 ?" | Plus spécifique = meilleurs résultats |
| "météo" | "Quelle est la météo à Paris demain ?" | Précis = réponse ciblée |
| "actualités" | "Quelles sont les actualités tech aujourd'hui ?" | Trop large = trop de résultats |

### Évaluer les résultats

- ✅ **Vérifiez les sources** citées dans les résultats
- ✅ **Croisez les informations** avec d'autres sources
- ⚠️ **Méfiez-vous** des informations non vérifiées
- ❌ **Ne partagez pas** d'informations sensibles trouvées en ligne

### Limites à connaître

- ⚠️ **Accès limité** : Certains sites bloquent les robots de recherche
- ⚠️ **Paywalls** : Les articles payants ne seront pas accessibles
- ⚠️ **Actualité** : Les informations peuvent être obsolètes quelques heures après la recherche
- ⚠️ **Biais** : Tous les moteurs de recherche ont des biais potentiels

## Sécurité et confidentialité

### Ce que votre assistant NE fait PAS :

- ❌ **Ne stocke pas** votre historique de recherche (sauf si configuré)
- ❌ **Ne partage pas** vos requêtes avec des tiers
- ❌ **Ne suit pas** votre activité sur le web
- ❌ **N'affiche pas** de publicités ciblées

### Bonnes pratiques :

- ✅ Utilisez la recherche web pour des **informations publiques** uniquement
- ✅ **Ne recherchez pas** d'informations personnelles ou sensibles
- ✅ **Vérifiez** toujours les sources avant de partager des informations
- ✅ **Respectez** les droits d'auteur et les politiques d'utilisation

## Résolution des problèmes

<details>
<summary>La recherche ne retourne aucun résultat</summary>

- Vérifiez que votre question est claire et spécifique
- Essayez de reformuler avec des mots-clés différents
- Vérifiez que vous n'avez pas désactivé la recherche web
- Essayez une recherche plus large
- Contactez le support si le problème persiste

</details>

<details>
<summary>Les résultats sont obsolètes</summary>

- La recherche web peut avoir une légère latence
- Essayez d'ajouter "après:[date]" à votre requête
- Vérifiez directement sur les sites sources
- La fonction de résumé peut parfois omettre des détails récents

</details>

<details>
<summary>Les résultats ne sont pas pertinents</summary>

- Soyez plus spécifique dans votre requête
- Ajoutez plus de contexte à votre question
- Utilisez des filtres (site:, après:, etc.)
- Essayez de poser la question différemment
- L'assistant apprend de vos retours : donnez un 👎 si les résultats ne sont pas bons

</details>

<details>
<summary>Je ne vois pas les liens vers les sources</summary>

- Les liens sont généralement affichés à la fin de chaque point
- Cliquez sur "Voir la source" ou le titre du point
- Certains résultats peuvent ne pas avoir de liens directs
- Vérifiez que votre interface affiche correctement les liens

</details>

## Exemples concrets

### Scénario 1 : Recherche d'actualités

**Vous** : "Quelles sont les dernières nouvelles sur la réglementation IA en Europe ?"

**Assistant** :
```
Voici les dernières informations sur la réglementation IA en Europe (juin 2025) :

1. **AI Act** : Entrée en vigueur complète prévue pour décembre 2025
   - Classification des systèmes IA par niveau de risque
   - Interdiction des pratiques de scoring social
   Source : [Commission Européenne](https://ec.europa.eu)

2. **Nouvelles lignes directrices** : Publiées par l'EDPB sur l'utilisation de l'IA dans le traitement des données
   - Obligations renforcées pour les fournisseurs de modèles de langage
   Source : [EDPB](https://edpb.europa.eu)

Souhaitez-vous que je rechercher des détails sur un point spécifique ?
```

### Scénario 2 : Comparaison de produits

**Vous** : "Comparez les derniers smartphones Samsung et Apple en 2025"

**Assistant** :
```
Comparaison des flagships 2025 :

| Critère | Samsung Galaxy S25 | iPhone 16 Pro |
|---------|-------------------|---------------|
| **Écran** | 6.8" Dynamic AMOLED 2X, 120Hz | 6.7" Super Retina XDR, 120Hz |
| **Processeur** | Snapdragon 8 Gen 4 | A18 Pro |
| **Appareil photo** | Triple 200MP + 12MP + 10MP | Triple 48MP + 12MP + 12MP |
| **Batterie** | 5000 mAh | 4400 mAh |
| **Prix** | À partir de 1299€ | À partir de 1399€ |

Sources : [GSMArena](https://gsmarena.com), [TechRadar](https://techradar.com)

Souhaitez-vous plus de détails sur un modèle en particulier ?
```

### Scénario 3 : Tutoriel ou guide

**Vous** : "Comment configurer un VPN sur Windows 11 ?"

**Assistant** :
```
Voici les étapes pour configurer un VPN sur Windows 11 :

1. **Ouvrir les paramètres** : Appuyez sur Win + I > Réseau et Internet > VPN
2. **Ajouter un VPN** : Cliquez sur "Ajouter un VPN"
3. **Configurer** : Sélectionnez le fournisseur, entrez le nom, le serveur, etc.

Pour un guide détaillé, consultez :
- [Guide officiel Microsoft](https://support.microsoft.com)
- [Tutoriel NordVPN](https://nordvpn.com)

Souhaitez-vous que je résume un de ces guides ?
```

## Ressources connexes

{% content-ref url="documents.md" %}
[documents.md](documents.md)
{% endcontent-ref %}

{% content-ref url="summarize.md" %}
[summarize.md](summarize.md)
{% endcontent-ref %}

{% content-ref url="models.md" %}
[models.md](models.md)
{% endcontent-ref %}
