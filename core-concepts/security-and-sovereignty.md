---
description: Sécurité, souveraineté et protection des données dans l'Assistant IA
icon: shield-check
---

# Sécurité et Souveraineté

L'Assistant IA a été conçu avec la **sécurité** et la **souveraineté** comme priorités absolues. Cette page détaille les mesures mises en place pour garantir la protection de vos données et le respect des contraintes spécifiques à l'administration publique.

## Infrastructure souveraine

### Hébergement

**📍 Localisation :** France (Centre de données Outscale à Saint-Cloud)

**🏢 Fournisseur :** [Outscale](https://www.outscale.com/) - Filiale de Dassault Systèmes

**🔒 Certification :** [SecNumCloud](https://cyber.gouv.fr/secnumcloud-pour-les-fournisseurs-de-services-cloud)

- Label de sécurité attribué par l'ANSSI
- Niveau de sécurité le plus élevé pour les services cloud en France
- Conformité aux exigences de souveraineté française et européenne

### Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    Infrastructure SecNumCloud                  │
│  ┌─────────────┐    ┌─────────────┐    ┌───────────────────┐  │
│  │  Application │───▶│   Albert API │───▶│   Modèles IA       │  │
│  │   Web        │    │             │    │   (Mistral, etc.)  │  │
│  └─────────────┘    └─────────────┘    └───────────────────┘  │
│  ┌─────────────┐    ┌─────────────┐                          │
│  │  Base de     │    │   Stockage   │                          │
│  │  données     │    │   documents  │                          │
│  └─────────────┘    └─────────────┘                          │
└─────────────────────────────────────────────────────────────┘
          ↓
┌─────────────────────────────────────────────────────────────┐
│                   Réseau sécurisé (France)                     │
└─────────────────────────────────────────────────────────────┘
```

### Sécurité physique

- **Datacenters en France** : Tous les serveurs sont physiques ou virtuels en France
- **Accès contrôlé** : Accès physique strictement limité et surveillé
- **Redondance** : Architecture redondante pour la haute disponibilité
- **Sauvegardes** : Sauvegardes régulières et chiffrées

---

## Protection des données

### Chiffrement

| Type | Méthode | Description |
|------|---------|-------------|
| **En transit** | TLS 1.3 | Toutes les communications sont chiffrées |
| **Au repos** | AES-256 | Données stockées chiffrées sur disque |
| **Base de données** | Chiffrement natif | Protection des données utilisateurs |

### Isolement des données

- **Multi-tenancy sécurisé** : Isolation complète entre utilisateurs
- **Pas de partage** : Vos données ne sont **jamais** accessibles par d'autres utilisateurs
- **Compartimentage** : Séparation logique et physique selon les besoins

### Gestion des accès

**Principes :**
- **Moindre privilège** : Chaque utilisateur a uniquement les permissions nécessaires
- **Authentification forte** : ProConnect (basé sur FranceConnect)
- **Audit** : Toutes les actions sont journalisées

**Rôles :**

| Rôle | Accès | Responsable |
|------|--------|--------------|
| **Utilisateur standard** | Ses propres conversations | Agent public |
| **Référent IA** | Statistiques d'usage (anonymisées) | Par ministère |
| **Administrateur DINUM** | Configuration globale | Équipe DINUM |
| **Support technique** | Accès limité pour dépannage | Équipe DINUM (sur demande) |

---

## Conformité réglementaire

### RGPD (Règlement Général sur la Protection des Données)

**Responsable du traitement :** Votre administration de rattachement

**Sous-traitant :** DINUM (pour la mise à disposition du service)

**Base juridique :** Mission d'intérêt public (Article 6 du décret n° 2019-1088)

**Droits des utilisateurs :**
- Accès à ses données
- Rectification
- Effacement (dans les limites légales)
- Portabilité
- Opposition
- Limitation du traitement

Pour exercer vos droits : [Protection des données](../reference/data-protection.md)

### Loi SREN (Sécurité et Résilience des Espaces Numériques)

L'Assistant IA est conçu pour respecter les exigences de la [loi SREN](https://www.numerique.gouv.fr/publications/rn-num/loi-sren/) :

✅ **Souveraineté numérique** : Infrastructure et services sous contrôle français/européen
✅ **Résilience** : Architecture redondante et résistante
✅ **Protection des données** : Mesures adaptées au niveau de sensibilité

### Normes ANSSI

Suivi des recommandations de l'**Agence Nationale de la Sécurité des Systèmes d'Information** :

- **PGSSI-E** (Politique Générale de Sécurité des Systèmes d'Information de l'État)
- **RGS** (Référentiel Général de Sécurité)
- **PSSIE** (Politique de Sécurité des Systèmes d'Information de l'État)

### Instruction Interministérielle n°901

Respect des exigences pour le traitement des informations classifiées :

- **Diffusion Restreinte** : **Non autorisé** dans l'Assistant IA (sauf configuration spécifique)
- **Secret** : **Interdit**
- **Très Secret** : **Interdit**

{% hint style="warning" icon="exclamation-triangle" %}
**Important :** L'Assistant IA n'est **pas homologué** pour le traitement de données classifiées. Ne soumettez **jamais** de données sensibles au sens de l'ANSSI ou de la loi SREN.
{% endhint %}

---

## Gestion des données personnelles

### Données collectées

| Catégorie | Données | Finalité | Durée de conservation |
|----------|---------|----------|----------------------|
| **Identification** | Prénom, nom, email professionnel, organisation | Gestion des comptes | Suppression du compte |
| **Contenu** | Messages, documents téléversés | Fourniture du service | Suppression du compte |
| **Technique** | Adresse IP, logs d'utilisation | Sécurité, maintenance | 1 an |
| **Analytique** | Données d'usage anonymisées | Amélioration du service | 2 ans (si analyse activée) |

### Traitement des données

**Localisation :** Toutes les données sont **traitées et stockées en France**

**Transfert hors UE :** **Aucun** - Les données ne quittent jamais le territoire français

**Sous-traitants :**

| Partenaire | Pays | Rôle | Garanties |
|-----------|------|------|-----------|
| Outscale | France | Hébergement | SecNumCloud, clauses contractuelles |
| IndieHosters | France | Administration cluster | Clauses de sous-traitance |
| PostHog | Allemagne | Mesure d'audience | Clauses de sous-traitance, anonymisation |

### Option "Autoriser l'analyse de conversation"

**Par défaut :** Activée (pour améliorer le service)

**Si activée :**
- L'équipe produit DINUM peut accéder à vos conversations
- **Uniquement** à des fins d'amélioration et de support
- Les données **ne sont jamais** utilisées pour entraîner des modèles
- Les données **ne sont jamais** partagées avec des tiers

**Si désactivée :**
- vos conversations restent **strictement privées**
- Seuls vous et les administrateurs techniques (en cas de problème) peuvent y accéder

**Où modifier :** Paramètres > Confidentialité > Autoriser l'analyse de conversation

---

## Sécurité des fonctionnalités

### Recherche web

**Fournisseur :** Brave Search API

**Protection :**
- Les requêtes sont **anonymisées** avant envoi
- Pas de tracking utilisateur
- Les requêtes sont conservées par Brave pendant **90 jours** (voir leur [DPA](https://cdn.search.brave.com/search-api/web/v1/client/_app/immutable/assets/brave-search-api-dpa-2025-09-09.DRXCoye6.pdf))

**Alternative :** Vous pouvez désactiver la recherche web dans vos paramètres

### Téléversement de documents

**Sécurité :**
- **Scan antivirus** : Tous les documents sont scannés avant traitement
- **Limite de taille** : 50 Mo par fichier (configurable)
- **Types autorisés** : Formats sûrs uniquement (PDF, images, bureautique)
- **Isolement** : Traitement dans un environnement sécurisé

**Nettoyage :**
- Documents temporaires supprimés après traitement
- Pas de conservation au-delà de la durée de la conversation (sauf si explicitement sauvegardé)

### Historique des conversations

**Protection :**
- Chiffrement des données
- Accès restreint à l'utilisateur propriétaire
- Possibilité d'archivage ou de suppression

**Durée :**
- Conservé tant que le compte est actif
- Suppression possible à tout moment par l'utilisateur

---

## Bonnes pratiques de sécurité

### Pour les utilisateurs

✅ **À faire :**
- Utilisez **uniquement** vos identifiants professionnels
- **Déconnectez-vous** après utilisation sur un poste partagé
- **Vérifiez l'URL** avant de vous connecter (https://assistant.numerique.gouv.fr)
- **Anonymisez** les données sensibles avant soumission
- **Signalez** les comportements suspects

❌ **À éviter :**
- Partager vos identifiants ProConnect
- Utiliser l'Assistant sur des réseaux non sécurisés
- Soumettre des données personnelles ou sensibles
- Ignorer les messages de sécurité

### Pour les administrateurs

✅ **Recommandations :**
- **Sensibilisez** vos agents aux bonnes pratiques
- **Définissez** une doctrine d'usage pour votre administration
- **Nominez** des référents IA
- **Surveillez** les usages via les statistiques (anonymisées)
- **Signalez** les incidents à la DINUM

### En cas d'incident

1. **Isolez** le problème (ne pas utiliser l'outil concerné)
2. **Documentez** les faits (captures d'écran, logs, etc.)
3. **Signalez** immédiatement à :
   - Votre référent IA ministériel
   - L'équipe DINUM : incident@numerique.gouv.fr
4. **Suivez** les instructions de l'équipe de sécurité

{% hint style="danger" icon="exclamation-circle" %}
**Incident de sécurité :** En cas de suspicion de **violation de données**, **compromission de compte** ou **accès non autorisé**, contactez **immédiatement** l'équipe de sécurité de la DINUM par téléphone ou via les canaux d'urgence.
{% endhint %}

---

## Transparence et audit

### Journalisation

**Activités journalisées :**
- Connexions/déconnexions
- Création/suppression de conversations
- Téléversement de documents
- Modifications de paramètres

**Durée de conservation :** 1 an (sauf obligation légale plus longue)

**Accès aux logs :** Restreint aux administrateurs techniques

### Audits de sécurité

- **Audits internes** : Réguliers (trimestriels)
- **Audits externes** : Par des organismes indépendants
- **Tests d'intrusion** : Réalisés par des experts en cybersécurité
- **Certification SecNumCloud** : Renouvellement périodique

### Rapport de transparence

Un rapport de transparence sera publié annuellement incluant :
- Nombre de signalements de sécurité
- Temps moyen de résolution
- Améliorations apportées
- Statistiques d'usage (anonymisées)

---

## Comparaison avec d'autres solutions

| Critère | Assistant IA | ChatGPT | Autres solutions |
|---------|--------------|---------|------------------|
| **Hébergement** | 🇫🇷 France (SecNumCloud) | 🇺🇸 États-Unis | Variable |
| **Juridiction** | 🇫🇷 Droit français | 🇺🇸 Droit américain | Variable |
| **Accès aux données** | 🔒 Restreint (DINUM) | 🌍 OpenAI + tiers | Variable |
| **Utilisation des données** | ❌ Pas d'entraînement | ⚠️ Possible (selon config) | Variable |
| **Chiffrement** | ✅ TLS + AES-256 | ✅ TLS | Variable |
| **Conformité RGPD** | ✅ Oui | ⚠️ Partielle | Variable |
| **Conformité SREN** | ✅ Oui | ❌ Non | ❌ Non |
| **Coût** | 🆓 Gratuit | 💰 Payant (Pro) | Variable |

---

## Ressources supplémentaires

- **[Protection des données](../reference/data-protection.md)** - Détails RGPD
- **[Mentions légales](../reference/legal.md)** - Aspects juridiques
- **[Signaler un incident](https://formulaire.beta.numerique.gouv.fr/r/assistant)** - Signalement de problème de sécurité
- **[Documentation ANSSI](https://www.ssi.gouv.fr/)** - Bonnes pratiques de sécurité
- **[SecNumCloud](https://cyber.gouv.fr/secnumcloud-pour-les-fournisseurs-de-services-cloud)** - Certification

---

{% hint style="success" icon="check-circle" %}
L'Assistant IA est conçu pour offrir **le plus haut niveau de sécurité et de souveraineté** possible pour un outil d'IA générative. Cependant, **vous conservez la responsabilité** de l'usage que vous en faites. En cas de doute, consultez votre référent IA ou votre DPO.
{% endhint %}
