---
description: Sécurité, souveraineté et protection des données dans l'Assistant IA
icon: shield-check
---

# Sécurité et souveraineté

L'Assistant IA a été conçu avec la **sécurité** et la **souveraineté** comme priorités absolues. Cette page détaille les mesures mises en place pour garantir la protection de vos données et le respect des contraintes spécifiques à l'administration publique.

## Infrastructure souveraine

### Hébergement

**📍 Localisation :** France (Centre de données Outscale à Saint-Cloud)

**🏢 Fournisseur :** [Outscale](https://www.outscale.com/) - Filiale de Dassault Systèmes

**🔒 Certification :** [SecNumCloud](https://cyber.gouv.fr/secnumcloud-pour-les-fournisseurs-de-services-cloud)

* Label de sécurité attribué par l'ANSSI
* Niveau de sécurité le plus élevé pour les services cloud en France
* Conformité aux exigences de souveraineté française et européenne

## Protection des données

### Isolement des données

* **Multi-tenancy sécurisé** : Isolation complète entre utilisateurs
* **Pas de partage** : Vos données ne sont **jamais** accessibles par d'autres utilisateurs
* **Compartimentage** : Séparation logique

### Gestion des accès

**Principes :**

* **Moindre privilège** : Chaque utilisateur a uniquement les permissions nécessaires
* **Authentification forte** : ProConnect (basé sur FranceConnect)

***

## Conformité réglementaire

### RGPD (Règlement Général sur la Protection des Données)

**Responsable du traitement :** Votre administration de rattachement

**Sous-traitant :** DINUM (pour la mise à disposition du service)

**Base juridique :** Mission d'intérêt public (Article 6 du décret n° 2019-1088)

**Droits des utilisateurs :**

* Accès à ses données
* Rectification
* Effacement (dans les limites légales)
* Portabilité
* Opposition
* Limitation du traitement

Pour exercer vos droits : [Protection des données](../documentation-legale/data-protection.md)

### Loi SREN (Sécurité et Résilience des Espaces Numériques)

L'Assistant IA est conçu pour respecter les exigences de la [loi SREN](https://www.numerique.gouv.fr/publications/rn-num/loi-sren/) :

✅ **Souveraineté numérique** : Infrastructure et services sous contrôle français/européen ✅ **Résilience** : Architecture redondante et résistante ✅ **Protection des données** : Mesures adaptées au niveau de sensibilité

### Instruction Interministérielle n°901

Respect des exigences pour le traitement des informations classifiées :

* **Diffusion Restreinte** : **Non autorisé** dans l'Assistant IA (sauf configuration spécifique)
* **Secret** : **Interdit**
* **Très Secret** : **Interdit**

{% hint style="warning" %}
**Important :** L'Assistant IA n'est **pas homologué** pour le traitement de données classifiées. Ne soumettez **jamais** de données sensibles au sens de l'ANSSI.
{% endhint %}

***

## Gestion des données personnelles

### Données collectées

| Catégorie          | Données                                        | Finalité                | Durée de conservation      |
| ------------------ | ---------------------------------------------- | ----------------------- | -------------------------- |
| **Identification** | Prénom, nom, email professionnel, organisation | Gestion des comptes     | Suppression du compte      |
| **Contenu**        | Messages, documents téléversés                 | Fourniture du service   | Suppression du compte      |
| **Technique**      | Adresse IP, logs d'utilisation                 | Sécurité, maintenance   | 1 an                       |
| **Analytique**     | Données d'usage anonymisées                    | Amélioration du service | 2 ans (si analyse activée) |

### Traitement des données

**Localisation :** Toutes les données sont **traitées et stockées en France**

**Transfert hors UE :** **Aucun** - Les données ne quittent jamais le territoire français

**Sous-traitants :**

| Partenaire   | Pays      | Rôle                   | Garanties                                |
| ------------ | --------- | ---------------------- | ---------------------------------------- |
| Outscale     | France    | Hébergement            | SecNumCloud, clauses contractuelles      |
| IndieHosters | France    | Administration cluster | Clauses de sous-traitance                |
| PostHog      | Allemagne | Mesure d'audience      | Clauses de sous-traitance, anonymisation |

### Option "Autoriser l'analyse de conversation"

**Par défaut :** Désactivée

**Si activée :**

* L'équipe produit DINUM peut accéder à vos conversations
* **Uniquement** à des fins d'amélioration et de support
* Les données **ne sont jamais** utilisées pour entraîner des modèles
* Les données **ne sont jamais** partagées avec des tiers

**Si désactivée :**

* vos conversations restent **strictement privées**
* Seuls vous et les administrateurs techniques (en cas de problème) peuvent y accéder.

**Où modifier :** Paramètres > Confidentialité > Autoriser l'analyse de conversation

***

## Sécurité des fonctionnalités

### Recherche web

**Fournisseur :** Brave Search API

**Protection :**

* Vos messages ne sont pas envoyé tels quels : le modèle formule une requête internet basée sur votre message
* Pas de tracking utilisateur : les requêtes envoyées pendant vos conversations ne sont pas traçables par le fournisseur de service Brave.
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
* Possibilité de suppression

**Durée :**

* Conservé tant que le compte est actif
* Suppression possible à tout moment par l'utilisateur
* (À venir) Suppression au bout de 12 mois d'inactivité

## Ressources supplémentaires

* [**Protection des données**](../documentation-legale/data-protection.md) - Détails RGPD
* [**Mentions légales**](../documentation-legale/legal.md) - Aspects juridiques
* [**Signaler un incident**](https://formulaire.beta.numerique.gouv.fr/r/assistant) - Signalement de problème de sécurité
* [**Documentation ANSSI**](https://www.ssi.gouv.fr/) - Bonnes pratiques de sécurité
* [**SecNumCloud**](https://cyber.gouv.fr/secnumcloud-pour-les-fournisseurs-de-services-cloud) - Certification

***

{% hint style="success" %}
L'Assistant IA est conçu pour offrir **le plus haut niveau de sécurité et de souveraineté** possible pour un outil d'IA générative. Cependant, **vous conservez la responsabilité** de l'usage que vous en faites. En cas de doute, consultez votre référent IA ou votre DPO.
{% endhint %}
