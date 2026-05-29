---
ddescription: Protection des données personnelles, RGPD et confidentialité dans l'Assistant IA
icon: user-shield
---

# Protection des Données Personnelles

Cette page explique comment vos données sont **collectées, traitées, protégées et stockées** dans le cadre de l'utilisation de l'Assistant IA, conformément au **Règlement Général sur la Protection des Données (RGPD)** et à la législation française.

## Qui est responsable de vos données ?

### Responsable du traitement

**Votre administration de rattachement** est le **responsable du traitement** des données personnelles liées à votre utilisation de l'Assistant IA.

**Pourquoi ?**
- Votre administration décide qui a accès au service
- Elle définit les règles d'utilisation internes
- Elle est responsable du traitement des données de ses agents

### Sous-traitant

La **Direction interministérielle du numérique (DINUM)** agit en tant que **sous-traitant** pour la mise à disposition technique du service.

**Rôle de la DINUM :**
- Hébergement et maintenance de la plateforme
- Fourniture de l'infrastructure technique
- Support et amélioration du service

---

## Quelles données sont collectées ?

Nous collectons uniquement les données **nécessaires** au fonctionnement du service et à la réalisation de nos missions de service public.

### Données d'identification

| Donnée | Source | Finalité | Base juridique | Durée |
|--------|--------|----------|----------------|-------|
| Prénom | ProConnect | Identification, personnalisation | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |
| Nom | ProConnect | Identification, personnalisation | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |
| Email professionnel | ProConnect | Contact, gestion de compte | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |
| Organisation | ProConnect | Gestion des accès, statistiques | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |

### Données de contenu

| Donnée | Source | Finalité | Base juridique | Durée |
|--------|--------|----------|----------------|-------|
| Messages (conversations) | Saisie utilisateur | Fourniture du service IA | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |
| Documents téléversés | Upload utilisateur | Analyse par l'IA, génération de réponses | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |
| Historique des conversations | Système | Continuité du service, expérience utilisateur | Mission d'intérêt public (Art. 6.1.e RGPD) | Suppression compte |

### Données techniques

| Donnée | Source | Finalité | Base juridique | Durée |
|--------|--------|----------|----------------|-------|
| Adresse IP | Connexion | Sécurité, détection des abus | Obligation légale (Loi n°2004-575) | 1 an |
| Logs de connexion | Système | Sécurité, maintenance, audit | Obligation légale (Art. 5 décret n°2021-1362) | 1 an |
| Type de navigateur | Navigateur | Compatibilité, statistiques | Intérêt légitime (Art. 6.1.f RGPD) | 2 ans |
| Appareil | Navigateur | Statistiques, amélioration | Intérêt légitime (Art. 6.1.f RGPD) | 2 ans |

### Données d'usage (si analyse activée)

| Donnée | Source | Finalité | Base juridique | Durée |
|--------|--------|----------|----------------|-------|
| Contenu des conversations | Système | Amélioration du service, évaluation des modèles | Consentement (Art. 6.1.a RGPD) | Suppression compte |
| Fréquence d'utilisation | Système | Statistiques, optimisation | Intérêt légitime (Art. 6.1.f RGPD) | 2 ans |
| Fonctionnalités utilisées | Système | Compréhension des besoins | Intérêt légitime (Art. 6.1.f RGPD) | 2 ans |

---

## Où vos données sont-elles stockées ?

### Localisation géographique

**🇫🇷 Toutes vos données sont stockées et traitées en France.**

- **Hébergement :** Outscale (Saint-Cloud, France)
- **Infrastructure :** SecNumCloud (certification ANSSI)
- **Sauvegardes :** France (plusieurs sites)

### Pas de transfert hors UE

**❌ Aucune donnée ne quitte le territoire français.**

- Pas de stockage aux États-Unis
- Pas de traitement par des fournisseurs américains
- Pas de transfert vers des pays tiers

### Exception : Mesure d'audience

**PostHog** (outil de mesure d'audience) est hébergé en Allemagne.

- **Données envoyées :** Statistiques d'usage **anonymisées**
- **Pas de données personnelles** transmises
- **Conformité RGPD** garantie
- **Clauses contractuelles** de protection des données

---

## À quoi servent vos données ?

### Finalités principales

1. **Fourniture du service**
   - Permettre l'accès à l'Assistant IA
   - Générer des réponses aux questions
   - Maintenir l'historique des conversations
   - Analyser les documents téléversés

2. **Sécurité et protection**
   - Authentifier les utilisateurs
   - Détecter et prévenir les abus
   - Protéger contre les attaques
   - Garantir l'intégrité du service

3. **Amélioration du service** (si analyse activée)
   - Évaluer la pertinence des réponses
   - Identifier les besoins des utilisateurs
   - Optimiser les fonctionnalités
   - Orienter la feuille de route

4. **Statistiques et reporting** (anonymisées)
   - Comprendre l'usage global
   - Mesurer l'adoption
   - Identifier les tendances
   - Justifier les investissements

---

## Qui a accès à vos données ?

### Accès par défaut

| Acteur | Accès | Justification |
|--------|--------|---------------|
| **Vous** | Toutes vos données | Propriétaire des données |
| **Votre administration** | Statistiques anonymisées | Pilotage du déploiement |
| **Équipe technique DINUM** | Données techniques (logs) | Maintenance et support |

### Accès conditionnel

| Acteur | Accès | Condition | Justification |
|--------|--------|-----------|---------------|
| **Équipe produit DINUM** | Contenu des conversations | **Option "Autoriser l'analyse" activée** | Amélioration du service |
| **Support DINUM** | Conversations spécifiques | **Signalement d'un problème** | Résolution des incidents |
| **Auditeurs** | Données anonymisées | Audit de sécurité | Conformité et certification |

### Accès interdit

❌ **Jamais partagées avec :**
- Des tiers commerciaux
- Des fournisseurs de modèles d'IA (Mistral, etc.)
- Des autorités étrangères
- D'autres utilisateurs

❌ **Jamais utilisées pour :**
- L'entraînement de modèles d'IA
- Le marketing ou la publicité
- La revente ou l'exploitation commerciale
- Le profilage non autorisé

---

## Vos droits sur vos données

Conformément au RGPD, vous disposez des droits suivants sur vos données personnelles :

### 1. Droit d'accès

**De quoi s'agit-il ?** Savoir quelles données nous détenons sur vous.

**Comment l'exercer ?**
- Contacter votre administration de rattachement
- Ou contacter le DPO de la DINUM : dpd@pm.gouv.fr

**Délai de réponse :** 1 mois (gratuit)

### 2. Droit de rectification

**De quoi s'agit-il ?** Corriger des données inexactes ou incomplètes.

**Comment l'exercer ?**
- Modifier directement dans votre profil (pour certaines données)
- Contacter votre administration

**Délai de réponse :** 1 mois

### 3. Droit à l'effacement ("droit à l'oubli")

**De quoi s'agit-il ?** Supprimer vos données.

**Limites :**
- ✅ Possible pour vos conversations et documents
- ❌ Impossible si conservation légale obligatoire (logs de sécurité)

**Comment l'exercer ?**
- Supprimer manuellement vos conversations
- Demander la suppression de votre compte

### 4. Droit à la portabilité

**De quoi s'agit-il ?** Récupérer vos données dans un format structuré.

**Données concernées :**
- Vos conversations
- Vos documents téléversés

**Format :** JSON, PDF ou autre format ouvert

**Statut :** Fonctionnalité d'export en développement

### 5. Droit d'opposition

**De quoi s'agit-il ?** Refuser le traitement de vos données.

**Cas possibles :**
- Désactiver l'analyse des conversations
- Refuser la mesure d'audience
- Opposer à un traitement spécifique

**Comment l'exercer ?**
- Dans vos paramètres (pour l'analyse)
- Par demande écrite

### 6. Droit à la limitation

**De quoi s'agit-il ?** Limiter temporairement le traitement.

**Cas possibles :**
- Contester l'exactitude des données
- Exercer votre droit d'opposition

### 7. Droit de ne pas faire l'objet d'une décision automatisée

**Application :** L'Assistant IA n'est **pas utilisé** pour prendre des décisions administratives individuelles vous concernant.

---

## Comment exercer vos droits ?

### Étape 1 : Contacter votre administration

**Méthode recommandée :**
1. Identifiez votre administration de rattachement
2. Contactez son **Délégué à la Protection des Données (DPO/DPD)**
3. Faites votre demande par écrit (email ou courrier)

**Où trouver le contact DPO ?**
- Liste publique : [https://www.data.gouv.fr/fr/datasets/5c926a7a634f410578005c68/](https://www.data.gouv.fr/fr/datasets/5c926a7a634f410578005c68/)
- Intranet de votre administration
- Demander à votre hiérarchie

### Étape 2 : Utiliser les modèles de la CNIL

La CNIL fournit des modèles de demandes :
[https://www.cnil.fr/fr/modeles/courrier](https://www.cnil.fr/fr/modeles/courrier)

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

---

## Paramètres de confidentialité

### Gérer vos préférences

Vous pouvez contrôler l'utilisation de vos données directement dans l'application :

1. **Accéder aux paramètres** : Cliquez sur votre avatar ou l'icône ⚙️
2. **Onglet "Confidentialité"**

### Options disponibles

| Option | Description | Impact | Défaut |
|--------|-------------|--------|--------|
| **Autoriser l'analyse de conversation** | Permet à l'équipe DINUM d'accéder à vos conversations pour améliorer le service | Vos conversations peuvent être lues par l'équipe produit | ✅ Activé |
| **Autoriser la recherche intelligente** | L'Assistant décide automatiquement quand faire une recherche web | Meilleure pertinence des réponses | ✅ Activé |
| **Mesure d'audience** | Autorise la collecte de statistiques d'usage | Aide à améliorer le produit | ✅ Activé |

### Comment modifier ?

1. Allez dans **Paramètres > Confidentialité**
2. Activez/désactivez les options selon vos préférences
3. **Sauvegardez** vos modifications

{% hint style="info" %}
**Conseil :** Désactiver l'analyse des conversations si vous travaillez avec des informations particulièrement sensibles (même non classifiées).
{% endhint %}

---

## Sécurité de vos données

### Mesures techniques

| Mesure | Description |
|--------|-------------|
| **Chiffrement** | TLS 1.3 pour les communications, AES-256 pour le stockage |
| **Isolement** | Vos données sont strictement séparées des autres utilisateurs |
| **Authentification** | ProConnect (basé sur FranceConnect) |
| **Audit** | Toutes les actions sont journalisées |
| **Sauvegarde** | Données sauvegardées régulièrement et chiffrées |

### Mesures organisationnelles

- **Accès restreint** : Principe du moindre privilège
- **Formation** : Sensibilisation à la protection des données
- **Contrats** : Clauses strictes avec les sous-traitants
- **Audits** : Vérifications régulières
- **Signalement** : Procédure claire pour les incidents

---

## Questions fréquentes

### Mes conversations sont-elles privées ?

**Oui**, vos conversations sont **privées par défaut**.

- Seuls vous pouvez y accéder
- L'équipe DINUM ne peut y accéder que si vous avez activé l'option "Autoriser l'analyse"
- **Jamais** partagées avec des tiers ou utilisées pour entraîner des modèles

### Puis-je supprimer mes données ?

**Oui**, vous pouvez :
- Supprimer des conversations individuelles
- Supprimer des documents téléversés
- Demander la suppression de votre compte (via votre administration)

### Que se passe-t-il si je quitte mon administration ?

Vos données seront :
- **Conservées** pendant une période transitoire (généralement 3 mois)
- **Transférées** à votre nouvelle administration si vous changez
- **Supprimées** si vous quittez définitivement le service public

### Mes données sont-elles utilisées pour de la publicité ?

**Non, absolument pas.**

- Pas de ciblage publicitaire
- Pas de revente de données
- Pas de partage avec des annonceurs

### Qui peut me demander mes données ?

**Seules les autorités compétentes** peuvent demander l'accès à vos données, dans le cadre de :
- Une enquête judiciaire (sur réquisition)
- Un contrôle administratif
- Une obligation légale

**Procédure :** La DINUM ou votre administration vérifiera la légitimité de la demande avant toute transmission.

---

## Signalement d'un problème de protection des données

Si vous pensez que vos droits ne sont pas respectés ou que vos données sont mal utilisées :

1. **Contactez votre DPO** en premier lieu
2. **Signalez à la CNIL** : [https://www.cnil.fr/fr/plaintes](https://www.cnil.fr/fr/plaintes)
3. **Contactez la DINUM** : dpd@pm.gouv.fr

---

## Ressources supplémentaires

- **[Mentions légales](legal.md)** - Cadre juridique complet
- **[Sécurité et souveraineté](../core-concepts/security-and-sovereignty.md)** - Mesures techniques
- **[CNIL](https://www.cnil.fr/)** - Autorité de protection des données française
- **[RGPD](https://eur-lex.europa.eu/legal-content/FR/TXT/?uri=CELEX%3A32016R0679)** - Texte officiel du règlement
- **[Modèles de courrier CNIL](https://www.cnil.fr/fr/modeles/courrier)** - Pour exercer vos droits

---

{% hint style="success" icon="check-circle" %}
La protection de vos données est une **priorité absolue** pour la DINUM. Nous mettons tout en œuvre pour garantir la **confidentialité, la sécurité et la conformité** de vos données personnelles. En cas de question, n'hésitez pas à contacter votre DPO ou l'équipe de la DINUM.
{% endhint %}
