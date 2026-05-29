---
description: Présentation des concepts de base de l'Assistant IA - Fonctionnement, objectifs, public cible
icon: book-open
---

# Concepts de base de l'Assistant IA

L'Assistant IA est un outil conversationnel conçu spécifiquement pour **les agents des administrations de l'État et de leurs organismes de tutelle**. Cette section présente ses fondements, son fonctionnement et ses principes directeurs.

## Qu'est-ce que l'Assistant IA ?

L'Assistant IA est une **interface conversationnelle** basée sur des **grands modèles de langage (LLM)** qui permet aux agents publics de :

- **Dialoguer** naturellement avec une intelligence artificielle
- **Rechercher** des informations sur le web et dans des documents
- **Automatiser** des tâches de rédaction et d'analyse
- **Organiser** leur travail grâce à des projets et collections

### Caractéristiques clés

| Caractéristique | Description |
|----------------|-------------|
| **Souveraineté** | Hébergé en France sur infrastructure SecNumCloud |
| **Open Source** | Code source disponible publiquement |
| **Sécurité** | Conforme aux normes de sécurité de l'État |
| **Accessibilité** | Accessible à tous les agents éligibles |
| **Gratuité** | Service financé par l'État, sans coût pour les utilisateurs |

---

## Public cible

### Qui peut utiliser l'Assistant IA ?

L'Assistant IA est destiné à :

✅ **Tous les agents** des administrations de l'État
✅ **Les agents** des organismes sous tutelle de l'État
✅ **Les partenaires et prestataires** autorisés par leur administration de rattachement

### Conditions d'accès

1. **Être agent** d'une administration de l'État ou d'un organisme sous sa tutelle
2. **Disposer d'un compte ProConnect** valide
3. **Avoir l'autorisation** de son administration (l'accès est maintenant généralisé)

**Aucun code d'accès n'est nécessaire.**

---

## Fonctionnement technique

### Architecture

```
Utilisateur (Agent public)
    ↓ (ProConnect)
Application Web (assistant.numerique.gouv.fr)
    ↓ (API sécurisée)
Albert API (Service IA interministériel)
    ↓ (Modèles IA)
Infrastructure SecNumCloud (Outscale)
    ↓
Données stockées en France
```

### Composants principaux

1. **Interface utilisateur** : Application web responsive
2. **Service d'authentification** : ProConnect pour l'identification
3. **Albert API** : Service central d'accès aux modèles IA
4. **Base de données** : Stockage des conversations et documents
5. **Service de recherche** : Intégration avec Brave Search API
6. **Service de documents** : Traitement et indexation des fichiers

---

## Capacités et limitations

### Ce que l'Assistant IA peut faire

✅ **Conversation intelligente**
- Dialogue naturel en français (et autres langues)
- Maintien du contexte sur plusieurs échanges
- Continuation automatique des conversations

✅ **Recherche d'information**
- Recherche web en temps réel
- Analyse de documents (PDF, images, bureautique)
- Accès à des informations actualisées

✅ **Génération de contenu**
- Rédaction de textes (mails, notes, rapports)
- Résumé automatique de documents
- Traduction de textes
- Reformulation et amélioration de style

✅ **Organisation du travail**
- Création de projets avec instructions communes
- Gestion de collections de documents
- Historique complet des conversations
- Recherche dans l'historique

### Ce que l'Assistant IA ne peut PAS faire

❌ **Prendre des décisions administratives**
- Ne peut pas générer des actes administratifs individuels
- Ne peut pas signer ou valider des documents officiels

❌ **Garantir l'exactitude absolue**
- Peut faire des erreurs factuelles
- Toujours vérifier les informations générées

❌ **Traiter des données sensibles**
- Pas conçu pour les données classifiées
- Pas adapté aux données personnelles non anonymisées

❌ **Accéder à des bases de données internes**
- Pas de connexion directe aux systèmes d'information ministériels
- (Fonctionnalité d'intégration avec Docs et Fichiers en développement)

❌ **Générer des images ou du code exécutable**
- Focus sur le texte et l'analyse de documents
- Pas de génération d'images (DALL-E, Stable Diffusion, etc.)

---

## Modèles d'IA utilisés

### Modèle principal

**Mistral Medium 3.1**
- Développé par Mistral AI
- Modèle performant pour les tâches de compréhension et génération de texte
- Optimisé pour le français
- Hébergé sur infrastructure souveraine

### Autres modèles disponibles

Selon la configuration de votre administration, d'autres modèles peuvent être accessibles :

| Modèle | Description | Cas d'usage recommandés |
|--------|-------------|------------------------|
| Mistral Small | Modèle léger et rapide | Tâches simples, tests |
| Mistral Medium | Équilibre performance/coût | Usage général |
| Mistral Large | Modèle puissant | Tâches complexes, analyse approfondie |

**À noter :** La liste des modèles disponibles peut évoluer en fonction des évaluations et des coûts.

### Sélection du modèle

Vous pouvez choisir le modèle dans :
1. **Les paramètres de conversation** (pour une conversation spécifique)
2. **Les préférences globales** (modèle par défaut pour toutes les nouvelles conversations)

**Conseil :** Testez différents modèles pour trouver celui qui correspond le mieux à vos besoins.

---

## Projets et organisation

### Qu'est-ce qu'un projet ?

Un **projet** est un espace de travail qui regroupe :

- **Plusieurs conversations** liées à un même thème
- **Une instruction commune** partagée par toutes les conversations du projet
- **Un contexte spécifique** pour adapter le comportement de l'Assistant

**Exemple :**
```
Projet: "Rédaction administrative"
└── Instruction: "Tu es un rédacteur administratif expert. Utilise un style formel et précis. Respecte les règles de la langue française."
    ├── Conversation 1: Rédaction d'une note de service
    ├── Conversation 2: Préparation d'un compte-rendu
    └── Conversation 3: Analyse d'un texte réglementaire
```

### Qu'est-ce qu'une collection ?

Une **collection** est un ensemble de **documents** que vous pouvez :

- **Organiser** par thème ou projet
- **Interroger** ensemble
- **Partager** (selon les permissions)

**Exemple :**
```
Collection: "Textes réglementaires 2026"
├── Décret n°2026-123 du 15 janvier 2026
├── Circulaire du 20 mars 2026
└── Note de service DGAFP/2026/45
```

### Différence entre projet et collection

| Élément | Projet | Collection |
|---------|--------|------------|
| **Contenu** | Conversations | Documents |
| **Instruction** | Oui (pour l'Assistant) | Non |
| **Contexte** | Pour adapter l'Assistant | Pour organiser les documents |
| **Utilisation** | Organiser son travail | Centraliser ses documents |

---

## Sécurité et souveraineté

### Infrastructure

- **Hébergement :** Outscale (SecNumCloud)
- **Localisation :** France (Saint-Cloud)
- **Certification :** Label SecNumCloud
- **Homologation :** En cours par la DINUM

### Protection des données

- **Chiffrement :** Toutes les communications sont chiffrées (TLS)
- **Isolement :** Données strictement séparées entre utilisateurs
- **Accès :** Restreint aux utilisateurs autorisés
- **Sauvegarde :** Données sauvegardées régulièrement

### Conformité

- **RGPD** : Respect des règles de protection des données
- **Loi SREN** : Conformité avec la stratégie de sécurité numérique de l'État
- **ANSSI** : Suivi des recommandations de l'Agence nationale de la sécurité des systèmes d'information

Pour plus de détails : [Sécurité et souveraineté](security-and-sovereignty.md)

---

## Bonnes pratiques

### Pour obtenir de meilleurs résultats

1. **Soyez précis** dans vos questions
2. **Fournissez du contexte** quand c'est pertinent
3. **Structurez** vos demandes (objectif, rôle, contexte)
4. **Itérez** : affinez votre demande en fonction des réponses
5. **Vérifiez** toujours les informations générées

### Pour utiliser l'outil de manière responsable

1. **Ne soumettez pas** de données sensibles
2. **Respectez** les règles de votre administration
3. **Consultez** votre référent IA en cas de doute
4. **Signalez** les problèmes ou comportements inattendus
5. **Participez** à l'amélioration via les retours

### Pour organiser votre travail

1. **Utilisez des projets** pour regrouper vos conversations par thème
2. **Créez des collections** pour vos documents fréquents
3. **Archivez** les anciennes conversations
4. **Nommez clairement** vos conversations et projets
5. **Utilisez la recherche** pour retrouver vos échanges

---

## Évolution du service

L'Assistant IA est en **amélioration continue**. Voici quelques évolutions prévues :

### Fonctionnalités en développement

- **Intégration avec Docs** : Connexion directe avec l'éditeur collaboratif de LaSuite
- **Intégration avec Fichiers** : Accès direct à votre drive de LaSuite
- **Reconnaissance vocale** : Dictée de prompts et transcription audio
- **Export des conversations** : Téléchargement de vos échanges
- **Application mobile** : Version dédiée pour smartphones et tablettes

### Feuille de route

Pour suivre l'évolution du produit :
- [Feuille de route officielle](https://albert.sites.beta.gouv.fr/)
- [Journal des changements](https://docs.assistant-ia.com/changelog)
- Canal Tchap dédié aux annonces

---

## Ressources supplémentaires

- **[Pour commencer](../getting-started/getting-started.md)** - Guide de démarrage
- **[Troubleshooting](../troubleshooting/troubleshooting.md)** - Résoudre les problèmes
- **[FAQ](../troubleshooting/faq.md)** - Questions fréquentes
- **[Mentions légales](../reference/legal.md)** - Aspects juridiques
- **[Protection des données](../reference/data-protection.md)** - RGPD et confidentialité

---

{% hint style="info" %}
L'Assistant IA est un outil **en évolution constante**. Vos retours sont essentiels pour nous aider à l'améliorer. N'hésitez pas à [faire un retour](https://formulaire.beta.numerique.gouv.fr/r/assistant) ou à rejoindre la communauté sur [Tchap](https://tchap.gouv.fr/).
{% endhint %}
