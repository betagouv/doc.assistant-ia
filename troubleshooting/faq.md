---
ddescription: Questions fréquentes sur l'Assistant IA - Accès, fonctionnement, sécurité
icon: clipboard-question
---

# Questions fréquentes

## Accès et éligibilité

### Qui peut accéder à l'Assistant IA ?

**Réponse :** L'Assistant IA est accessible à **tous les agents des administrations de l'État et de leurs organismes de tutelle**. Il suffit de se connecter via ProConnect avec vos identifiants professionnels.

_Aucun code d'accès n'est nécessaire._

### Comment accéder à l'Assistant IA ?

1. Rendez-vous sur [assistant.numerique.gouv.fr](https://assistant.numerique.gouv.fr)
2. Connectez-vous via **ProConnect** avec vos identifiants professionnels
3. Vous êtes prêt à utiliser l'Assistant !

### Pourquoi n'ai-je pas accès alors que je suis agent public ?

Plusieurs raisons possibles :

* Votre administration n'a pas encore déployé l'accès (contactez votre référent IA)
* Problème technique avec ProConnect (vérifiez vos identifiants)
* Votre navigateur n'est pas compatible (essayez Chrome, Firefox ou Edge)

Si le problème persiste, contactez votre référent IA ministériel.

***

## Fonctionnement

### Comment bien formuler mes questions ?

Pour obtenir de meilleurs résultats :

✅ **À faire :**

* Soyez **précis** : décrivez clairement le contexte et l'objectif
* **Structurez** votre demande avec des phrases courtes
* **Donnez des exemples** ou extrayez le texte pertinent
* **Itérez** : affinez votre demande en fonction des réponses

❌ **À éviter :**

* Questions trop vagues ("Parle-moi de l'administration")
* Demandes trop complexes en un seul message
* Attente de réponses sans vérifier les faits

**Exemple de bonne formulation :**

```
Rôle : Tu es un expert en communication publique.
Objectif : Reformule ce mail pour le rendre plus clair et professionnel.
Contexte : [coller le texte ici]
```

### Puis-je utiliser l'Assistant IA pour des tâches administratives ?

**Oui, mais avec précaution :**

* L'Assistant peut vous aider à **rédaction de projets de textes, synthèses, recherches d'information**
* **Ne l'utilisez PAS** pour prendre des décisions administratives individuelles (actes unilatéraux visant des personnes nommément désignées)
* Toujours **vérifier et valider** les informations générées

### Quels types de fichiers puis-je téléverser ?

**Formats supportés :**

* **Documents :** PDF, Markdown (.md), Word (.docx), PowerPoint (.pptx), Excel (.xlsx)
* **Images :** JPG, PNG, WEBP
* **Autres :** TXT, CSV (selon configuration)

**Limites :**

* Taille maximale : généralement 10 Mo par fichier (variable)
* Nombre de fichiers : plusieurs peuvent être téléversés simultanément

### Combien de temps mes conversations sont-elles conservées ?

Vos conversations sont conservées **tant que votre compte est actif**. Vous pouvez :

* **Archiver** des conversations pour les cacher de la vue principale
* **Supprimer** des conversations définitivement
* **Exporter** vos échanges si nécessaire (fonctionnalité à venir)

***

## Sécurité et confidentialité

### Mes données sont-elles sécurisées ?

**Oui, plusieurs niveaux de protection :**

* **Hébergement souverain** : Infrastructure SecNumCloud en France
* **Isolement** : Vos données sont strictement séparées de celles des autres utilisateurs
* **Accès restreint** : Seuls vous et les administrateurs autorisés pouvez accéder à vos conversations

### Qui peut accéder à mes conversations ?

**Par défaut :**

* **Vous seul** avez accès à vos conversations
* Les **administrateurs techniques** de la DINUM peuvent accéder aux données&#x20;

**En cas d'analyse activée :**

* L'équipe produit peut consulter vos échanges **à des fins d'amélioration du service uniquement**
* Les données ne sont **jamais** utilisées pour entraîner des modèles
* Les données ne sont **jamais** partagées avec des tiers

### Mes données sont-elles utilisées pour entraîner des modèles ?

**Non, absolument pas.**

* Vos conversations **ne sont jamais** utilisées pour entraîner des modèles d'IA
* Vos données **n'apparaîtront jamais** dans les réponses à d'autres utilisateurs
* La DINUM n'entraîne pas de modèles, elle utilise des modèles existants du marché

### Puis-je utiliser l'Assistant avec des données sensibles ?

**Non, l'Assistant IA n'est pas conçu pour traiter des données sensibles.**

**À NE PAS faire :**

* ❌ Données médicales
* ❌ Données classifiées (Diffusion restreinte, Secret, Très Secret)
* ❌ Données sensibles au sens  de l'ANSSI

**À faire :**

* ✅ Anonymisez les données lorsque vous le pouvez
* ✅ Consultez votre référent IA ou DPO en cas de doute
* ✅ Préférez les données déjà publiques

***

## Modèles et fonctionnalités

### Quel modèle d'IA est utilisé ?

**Modèle principal actuel :** Mistral Medium 2508

D'autres modèles peuvent être utilisée lorsque l'Assistant connaît une forte charge, afin que votre expérience soit la plus pérenne possible : si les serveurs du modèle principal sont surchargé, vous basculez sur un autre modèle, qui répond aux mêmes exigences de sécurité et de souveraineté.&#x20;

De plus, si certaines fonctionalités sont dégradées du fait du changement de modèle, un bandeau d'erreur s'affichera en haut de la page de l'Assistant.



### Pourquoi les réponses varient-elles selon les modèles ?

Chaque modèle a ses propres caractéristiques :

* **Force** : Certains modèles sont meilleurs pour des tâches spécifiques
* **Style** : Les réponses peuvent avoir des tonalités différentes
* **Connaissances** : Les dates de coupure des données d'entraînement varient
* **Capacités** : Certains modèles gèrent mieux les longs contextes ou les documents

### La recherche web est-elle toujours activée ?

**Deux modes disponibles :**

1. **Recherche manuelle** : Vous cliquez sur l'icône 🌐 pour activer la recherche
2. **Recherche intelligente** : Activez cette option dans vos paramètres pour que l'Assistant décide automatiquement quand faire une recherche

**À noter :**

* La recherche utilise **Brave Search API**
* Les requêtes sont conservées par Brave pendant **90 jours** (voir leur [déclaration de traitement](https://cdn.search.brave.com/search-api/web/v1/client/_app/immutable/assets/brave-search-api-dpa-2025-09-09.DRXCoye6.pdf))
* Les résultats sont résumés et intégrés dans la réponse

***

## Projets et organisation

### C'est quoi un projet ?

Un **projet** est un espace qui regroupe plusieurs conversations avec :

* Une **instruction commune** partagée par toutes les conversations du projet
* Un **contexte documentaire spécifique** pour adapter le comportement de l'Assistant
* Une **organisation simplifiée** de vos échanges par thème

**Exemples d'utilisation :**

* Un projet "Rédaction administrative" avec des instructions pour adopter un style formel
* Un projet "Analyse juridique" avec un contexte sur les textes de référence
* Un projet "Veille technologique" pour suivre l'actualité d'un domaine

### Comment créer un projet ?

1. Cliquez sur "Nouveau projet" dans la barre latérale
2. Donnez un nom à votre projet
3. Définissez l'instruction commune (optionnel mais recommandé)
4. Ajoutez éventuellement des documents de référence
5. Commencez une nouvelle conversation dans ce projet



***

## Techniques

### Quelle est la limite de contexte ?

La taille maximale d'une conversation (vos messages + les réponses + les extraits de documents) est d'environ **100 000 mots** (soit environ 300-400 pages de texte).

**Bonnes pratiques :**

* Commencez une nouvelle conversation pour les longs échanges
* Résumez régulièrement les points clés
* Archivez les anciennes conversations

### Pourquoi ai-je une erreur de limite de contexte ?

Cette erreur apparaît lorsque la conversation atteint la limite maximale. **Solutions :**

1. Commencez une **nouvelle conversation**
2. **Résumez** les points importants de l'ancienne conversation dans un nouveau message
3. **Divisez** votre travail en plusieurs conversations thématiques
4. **Archivez** les conversations terminées

### Puis-je exporter mes conversations ?

La fonctionnalité d'export est **en développement**. En attendant, vous pouvez :

* **Copier-coller** manuellement le contenu
* **Prendre des captures d'écran** pour les échanges importants

***

## Support et communauté

### Où puis-je discuter avec d'autres utilisateurs ?

Rejoignez la communauté sur **Tchap** : [Canal Assistant IA](https://tchap.gouv.fr/#/room/!eAHyPLdVHMxNhKAbaC:agent.dinum.tchap.gouv.fr)

### Qui contacter en cas de problème technique ?

1. **Votre référent IA** ministériel (premier niveau de support)
2. **L'équipe DINUM** via les canaux officiels
3. [**Signaler un problème**](report-issue.md) pour les bugs techniques

### Comment signaler un bug ?

Rendez vous sur la page Signaler un problème :

{% content-ref url="report-issue.md" %}
[report-issue.md](report-issue.md)
{% endcontent-ref %}

***

## Divers

### L'Assistant IA est-il meilleur que ChatGPT ?

**Différences principales :**

| Critère             | Assistant IA                                                                                                                             | ChatGPT                                                                                                                              |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **Souveraineté**    | ✅ Hébergé en France (SecNumCloud)                                                                                                        | ❌ Hébergé aux États-Unis                                                                                                             |
| **Confidentialité** | ✅ Données ne sortent pas de France                                                                                                       | ❌ Données peuvent être stockées à l'étranger                                                                                         |
| **Accès**           | ✅ Réservé aux agents publics                                                                                                             | ❌ Ouvert au grand public                                                                                                             |
| **Modèles**         | Modèles ouverts et propriétaires d'environ 120 milliard de paramètres, limités par des logiques de coût et d'empreinte environnementales | Modèles propriétaires de plusieurs téras de paramètres (1000 milliards, soit 10 fois plus coûteux), avec des meilleurs performances  |
| **Sécurité**        | ✅ Adapté aux contraintes de l'État                                                                                                       | ❌ Non conçu pour les besoins publics                                                                                                 |

L'Assistant IA est **spécifiquement conçu** pour répondre aux besoins des agents publics dans un cadre **souverain et sécurisé**.

### Puis-je utiliser l'Assistant IA sur mobile ?

**Oui**, l'application web est **disponible sur votre navigateur** et fonctionne sur :

* Smartphones (iOS et Android)
* Tablettes
* Ordinateurs portables

**Recommandations :**

* Ajoutez un marque-page sur l'Assistant qui peut prendre la forme d'une icone sur mobile ou d'un raccourci sur ordinateur.



***

## Besoin d'aide supplémentaire ?

Si vous ne trouvez pas de réponse à votre question :

* [**Consultez le guide de dépannage**](../depannage/erreurs.md) pour les problèmes techniques
* [**Signalez un problème**](report-issue.md) à l'équipe
* **Contactez votre référent IA** ministériel
