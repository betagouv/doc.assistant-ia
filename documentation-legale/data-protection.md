---
ddescription: >-
  Protection des données personnelles, RGPD et confidentialité dans l'Assistant
  IA
icon: user-shield
---

# Protection des données

Cette page explique comment vos données sont **collectées, traitées, protégées et stockées** dans le cadre de l'utilisation de l'Assistant IA, conformément au **Règlement Général sur la Protection des Données (RGPD)** et à la législation française.

## Qui est responsable de vos données ?

### Responsable du traitement

**Votre administration de rattachement** est le **responsable du traitement** des données personnelles liées à votre utilisation de l'Assistant IA.

**Pourquoi ?**

* Votre administration décide qui a accès au service
* Elle définit les règles d'utilisation internes
* Elle est responsable du traitement des données de ses agents

### Sous-traitant

La **Direction interministérielle du numérique (DINUM)** agit en tant que **sous-traitant** pour la mise à disposition technique du service.

**Rôle de la DINUM :**

* Hébergement et maintenance de la plateforme
* Fourniture de l'infrastructure technique
* Support et amélioration du service

***

## Quelles données sont collectées ?

Nous collectons uniquement les données **nécessaires** au fonctionnement du service et à la réalisation de nos missions de service public.

### Données d'identification

| Donnée              | Source     | Finalité                         | Base juridique                             | Durée              |
| ------------------- | ---------- | -------------------------------- | ------------------------------------------ | ------------------ |
| Prénom              | ProConnect | Identification, personnalisation | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |
| Nom                 | ProConnect | Identification, personnalisation | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |
| Email professionnel | ProConnect | Contact, gestion de compte       | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |
| Organisation        | ProConnect | Gestion des accès, statistiques  | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |

### Données de contenu

| Donnée                       | Source             | Finalité                                      | Base juridique                             | Durée              |
| ---------------------------- | ------------------ | --------------------------------------------- | ------------------------------------------ | ------------------ |
| Messages (conversations)     | Saisie utilisateur | Fourniture du service IA                      | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |
| Documents téléversés         | Upload utilisateur | Analyse par l'IA, génération de réponses      | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |
| Historique des conversations | Système            | Continuité du service, expérience utilisateur | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |

### Données techniques

| Donnée             | Source     | Finalité                     | Base juridique                                | Durée |
| ------------------ | ---------- | ---------------------------- | --------------------------------------------- | ----- |
| Adresse IP         | Connexion  | Sécurité, détection des abus | Obligation légale (Loi n°2004-575)            | 1 an  |
| Logs de connexion  | Système    | Sécurité, maintenance, audit | Obligation légale (Art. 5 décret n°2021-1362) | 1 an  |
| Type de navigateur | Navigateur | Compatibilité, statistiques  | Intérêt légitime (Art. 6.1.f RGPD)            | 2 ans |
| Appareil           | Navigateur | Statistiques, amélioration   | Intérêt légitime (Art. 6.1.f RGPD)            | 2 ans |

### Données d'usage (si analyse activée)

| Donnée                    | Source  | Finalité                                        | Base juridique                     | Durée              |
| ------------------------- | ------- | ----------------------------------------------- | ---------------------------------- | ------------------ |
| Contenu des conversations | Système | Amélioration du service, évaluation des modèles | Consentement (Art. 6.1.a RGPD)     | Suppression compte |
| Fréquence d'utilisation   | Système | Statistiques, optimisation                      | Intérêt légitime (Art. 6.1.f RGPD) | 2 ans              |
| Fonctionnalités utilisées | Système | Compréhension des besoins                       | Intérêt légitime (Art. 6.1.f RGPD) | 2 ans              |

***

## Où vos données sont-elles stockées ?

### Localisation géographique

**Toutes vos données sont stockées et traitées en France.**

* **Hébergement :** Outscale (Saint-Cloud, France)
* **Infrastructure :** SecNumCloud (certification ANSSI)
* **Sauvegardes :** France (plusieurs sites)

### Pas de transfert hors UE

**Aucune donnée ne quitte le territoire français.**

* Pas de stockage aux États-Unis
* Pas de traitement par des fournisseurs américains
* Pas de transfert vers des pays tiers

### Exception : Mesure d'audience

**PostHog** (outil de mesure d'audience) est hébergé en Allemagne.

* **Données envoyées :** Statistiques d'usage **anonymisées**
* **Pas de données personnelles** transmises
* **Conformité RGPD** garantie
* **Clauses contractuelles** de protection des données

***

## Protection et sécurité des données

### Isolement des données

* **Multi-tenancy sécurisé** : Isolation complète entre utilisateurs
* **Pas de partage** : Vos données ne sont **jamais** accessibles par d'autres utilisateurs
* **Compartimentage** : Séparation logique entre les données

### Gestion des accès

**Principes :**

* **Moindre privilège** : Chaque utilisateur a uniquement les permissions nécessaires
* **Authentification forte** : ProConnect (basé sur FranceConnect)

***

## Sous-traitants

Nous faisons appel à des sous-traitants pour l'hébergement et la mesure d'audience. Avant de leur transmettre vos données, nous nous sommes assurés de la mise en œuvre de garanties adéquates et du respect de conditions strictes de confidentialité, d'usage et de protection des données.

| Partenaire       | Pays      | Rôle                   | Garanties                                |
| ---------------- | --------- | ---------------------- | ---------------------------------------- |
| **Outscale**     | France    | Hébergement            | SecNumCloud, clauses contractuelles      |
| **IndieHosters** | France    | Administration cluster | Clauses de sous-traitance                |
| **PostHog**      | Allemagne | Mesure d'audience      | Clauses de sous-traitance, anonymisation |

***

## Sécurité des fonctionnalités

### Recherche web

**Fournisseur :** Brave Search API

**Protection :**

* Vos messages ne sont pas envoyés tels quels : le modèle formule une requête internet basée sur votre message
* Pas de tracking utilisateur : les requêtes envoyées pendant vos conversations ne sont pas traçables par le fournisseur Brave
* Les requêtes sont conservées par Brave pendant **90 jours** (voir leur [DPA](https://cdn.search.brave.com/search-api/web/v1/client/_app/immutable/assets/brave-search-api-dpa-2025-09-09.DRXCoye6.pdf))

**Alternative :** Vous pouvez désactiver la recherche web dans vos paramètres

### Téléversement de documents

**Sécurité :**

* **Scan antivirus** : Tous les documents sont scannés avant traitement
* **Limite de taille** : 10 Mo par fichier (configurable)
* **Types autorisés** : Formats sûrs uniquement (PDF, images, bureautique)
* **Isolement** : Traitement dans un environnement sécurisé

**Nettoyage :**

* Documents temporaires supprimés après traitement
* Pas de conservation au-delà de la durée de la conversation (sauf si explicitement sauvegardé)

### Historique des conversations

**Protection :**

* Accès restreint à l'utilisateur propriétaire
* Possibilité de suppression à tout moment

**Durée :**

* Conservé tant que le compte est actif
* Suppression possible à tout moment par l'utilisateur
* (À venir) Suppression automatique au bout de 12 mois d'inactivité

***

## Option "Autoriser l'analyse de conversation"

**Par défaut :** Désactivée

**Si activée :**

* L'équipe produit DINUM peut accéder à vos conversations
* **Uniquement** à des fins d'amélioration et de support
* Les données **ne sont jamais** utilisées pour entraîner des modèles
* Les données **ne sont jamais** partagées avec des tiers

**Si désactivée :**

* Vos conversations restent **strictement privées**
* Seuls vous et les administrateurs techniques peuvent y accéder en cas de problème.

**Où modifier :** Paramètres > Autoriser l'analyse de conversation

***

## À quoi servent vos données ?

### Finalités principales

1. **Fourniture du service**
   * Permettre l'accès à l'Assistant IA
   * Générer des réponses aux questions
   * Maintenir l'historique des conversations
   * Analyser les documents téléversés
2. **Sécurité et protection**
   * Authentifier les utilisateurs
   * Détecter et prévenir les abus
   * Protéger contre les attaques
   * Garantir l'intégrité du service
3. **Amélioration du service** (si analyse activée)
   * Évaluer la pertinence des réponses
   * Identifier les besoins des utilisateurs
   * Optimiser les fonctionnalités
   * Orienter la feuille de route
4. **Statistiques et reporting** (anonymisées)
   * Comprendre l'usage global
   * Mesurer l'adoption
   * Identifier les tendances
   * Justifier les investissements

***

## Qui a accès à vos données ?

### Accès par défaut

| Acteur                     | Accès                     | Justification            |
| -------------------------- | ------------------------- | ------------------------ |
| **Vous**                   | Toutes vos données        | Propriétaire des données |
| **Votre administration**   | Statistiques anonymisées  | Pilotage du déploiement  |
| **Équipe technique DINUM** | Données techniques (logs) | Maintenance et support   |

### Accès conditionnel

| Acteur                   | Accès                     | Condition                                | Justification               |
| ------------------------ | ------------------------- | ---------------------------------------- | --------------------------- |
| **Équipe produit DINUM** | Contenu des conversations | **Option "Autoriser l'analyse" activée** | Amélioration du service     |
| **Support DINUM**        | Conversations spécifiques | **Signalement d'un problème**            | Résolution des incidents    |
| **Auditeurs**            | Données anonymisées       | Audit de sécurité                        | Conformité et certification |

### Accès interdit

❌ **Jamais partagées avec :**

* Des tiers commerciaux
* Des fournisseurs de modèles d'IA (Mistral, etc.)
* Des autorités étrangères
* D'autres utilisateurs

❌ **Jamais utilisées pour :**

* L'entraînement de modèles d'IA
* Le marketing ou la publicité
* La revente ou l'exploitation commerciale
* Le profilage non autorisé

***

## Vos droits sur vos données

Conformément au RGPD, vous disposez des droits suivants sur vos données personnelles :

### 1. Droit d'accès

**De quoi s'agit-il ?** Savoir quelles données nous détenons sur vous.

**Comment l'exercer ?**

* Contacter votre administration de rattachement
* Ou contacter le DPO de la DINUM : dpd@pm.gouv.fr

**Délai de réponse :** 1 mois

### 2. Droit de rectification

**De quoi s'agit-il ?** Corriger des données inexactes ou incomplètes.

**Comment l'exercer ?**

* Modifier directement dans votre profil (pour certaines données)
* Contacter votre administration

**Délai de réponse :** 1 mois

### 3. Droit à l'effacement ("droit à l'oubli")

**De quoi s'agit-il ?** Supprimer vos données.

**Limites :**

* ✅ Possible pour vos conversations et documents
* ❌ Impossible si conservation légale obligatoire (logs de sécurité)

**Comment l'exercer ?**

* Supprimer manuellement vos conversations
* Demander la suppression de votre compte

### 4. Droit à la portabilité

**De quoi s'agit-il ?** Récupérer vos données dans un format structuré.

**Données concernées :**

* Vos conversations
* Vos documents téléversés

**Format :** JSON, PDF ou autre format ouvert

**Statut :** Demande manuelle uniquement

### 5. Droit d'opposition

**De quoi s'agit-il ?** Refuser le traitement de vos données.

**Cas possibles :**

* Désactiver l'analyse des conversations
* Refuser la mesure d'audience
* Opposer à un traitement spécifique

**Comment l'exercer ?**

* Dans vos paramètres (pour l'analyse)
* Par demande écrite

### 6. Droit à la limitation

**De quoi s'agit-il ?** Limiter temporairement le traitement.

**Cas possibles :**

* Contester l'exactitude des données
* Exercer votre droit d'opposition

### 7. Droit de ne pas faire l'objet d'une décision automatisée

**Application :** Conformément à ses modalités d'utilisation, l'Assistant IA n'est **pas utilisé** pour prendre des décisions administratives individuelles vous concernant.

***

## Comment exercer vos droits ?

### Étape 1 : Contacter votre administration

**Méthode recommandée :**

1. Identifiez votre administration de rattachement
2. Contactez son **Délégué à la Protection des Données (DPO/DPD)**
3. Faites votre demande par écrit (email ou courrier)

**Où trouver le contact DPO ?**

* Liste publique : [https://www.data.gouv.fr/fr/datasets/5c926a7a634f410578005c68/](https://www.data.gouv.fr/fr/datasets/5c926a7a634f410578005c68/)
* Intranet de votre administration
* Demander à votre hiérarchie

### Étape 2 : Utiliser les modèles de la CNIL

La CNIL fournit des modèles de demandes : [https://www.cnil.fr/fr/modeles/courrier](https://www.cnil.fr/fr/modeles/courrier)

### Étape 3 : Contacter la DINUM (si nécessaire)

Si vous ne pouvez pas contacter votre administration :

**Email :** mesdonnees@modernisation.gouv.fr

**Courrier :**

```
Services du Premier ministre
À l'attention du délégué à la protection des données (DPD)
56 rue de Varenne
75007 Paris
```

**La DINUM transmettra votre demande à votre administration de rattachement.**

## Ressources supplémentaires

* [**Mentions légales**](legal.md) - Cadre juridique complet
* [**Sécurité et souveraineté**](../concepts-de-base/securite-et-souverainete.md) - Mesures techniques
* [**CNIL**](https://www.cnil.fr/) - Autorité de protection des données française
* [**RGPD**](https://eur-lex.europa.eu/legal-content/FR/TXT/?uri=CELEX%3A32016R0679) - Texte officiel du règlement
* [**Modèles de courrier CNIL**](https://www.cnil.fr/fr/modeles/courrier) - Pour exercer vos droits

***

{% hint style="success" %}
La protection de vos données est une **priorité absolue** pour la DINUM. Nous mettons tout en œuvre pour garantir la **confidentialité, la sécurité et la conformité** de vos données personnelles. En cas de question, n'hésitez pas à contacter votre DPO ou l'équipe de la DINUM.
{% endhint %}
