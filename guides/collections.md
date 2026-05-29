---
description: >-
  Organisez et gérez vos documents en collections pour une recherche et un accès
  optimisés.
icon: folder
---

# Collections

Les **collections** vous permettent d'organiser vos documents, conversations et connaissances en groupes logiques pour un accès plus facile et une recherche plus ciblée. Cada collection peut avoir ses propres paramètres de partage, de recherche et d'indexation.

{% hint style="success" %}
**Organisation intelligente** : Les collections peuvent être partagées avec des équipes spécifiques et configurées pour des cas d'usage particuliers.
{% endhint %}

## Créer et gérer des collections

### Créer une nouvelle collection

{% stepper %}
{% step %}
#### Accéder à l'interface de collections

1. Dans la barre latérale, cliquez sur **Collections**
2. Ou allez dans **Paramètres** > **Gestion des collections**
{% endstep %}

{% step %}
#### Configurer la collection

1. Cliquez sur **+ Nouvelle collection**
2. Donnez un **nom clair et descriptif** à votre collection
   - Exemples : "Projet Alpha - Documentation", "Équipe Marketing - Ressources", "Client X - Contrats"
3. Ajoutez une **description** (optionnel mais recommandé)
4. Sélectionnez un **icône** pour faciliter l'identification visuelle
5. Choisissez une **couleur** pour le codage visuel
{% endstep %}

{% step %}
#### Définir les paramètres

Configurez les options de votre collection :

- **Visibilité** : Publique, Privée, Partagée avec des équipes spécifiques
- **Indexation** : Activer/désactiver l'indexation pour la recherche
- **Langue principale** : Pour une meilleure détection automatique
- **Catégorie** : Classifiez votre collection (Projet, Équipe, Client, etc.)

{% endstep %}

{% step %}
#### Finaliser la création

Cliquez sur **Créer** et votre collection sera prête à l'emploi.
{% endstep %}
{% endstepper %}

### Types de collections

| Type | Description | Cas d'usage |
|------|-------------|------------|
| **Projet** | Documents liés à un projet spécifique | "Projet Phoenix - Documentation" |
| **Équipe** | Ressources partagées par une équipe | "Équipe Dev - Guides techniques" |
| **Client** | Documents relatifs à un client | "Client Acme - Contrats" |
| **Personnelle** | Documents privés | "Mes notes de réunion" |
| **Thématique** | Documents sur un sujet commun | "RGPD - Réglementation" |

## Ajouter du contenu à une collection

### Ajouter des documents

1. Ouvrez la collection cible
2. Glissez-déposez des fichiers directement dans la collection
3. Ou cliquez sur **+ Ajouter des documents** et sélectionnez vos fichiers

### Ajouter des conversations

Pour sauvegarder une conversation dans une collection :

1. Pendant ou après une conversation, cliquez sur **⋯** (menu)
2. Sélectionnez **Ajouter à une collection**
3. Choisissez la collection de destination
4. Ajoutez une **description** pour référence future

### Ajouter des liens web

1. Dans la collection, cliquez sur **+ Ajouter un lien**
2. Entrez l'URL de la page web
3. Ajoutez un **titre** et une **description**
4. L'assistant peut automatiquement extraire et indexer le contenu

## Rechercher dans les collections

### Recherche de base

1. Sélectionnez une collection
2. Utilisez la barre de recherche en haut
3. Les résultats seront limités à cette collection

### Recherche avancée

Utilisez des opérateurs pour affiner vos recherches :

| Opérateur | Exemple | Description |
|-----------|---------|-------------|
| `collection:` | `collection:"Projet Alpha"` | Rechercher dans une collection spécifique |
| `type:` | `type:document` | Filtrer par type (document, conversation, lien) |
| `date:` | `date:2025-01-*` | Filtrer par date |
| `author:` | `author:Jean` | Filtrer par auteur |

Exemple de requête avancée :
```
collection:"Équipe Dev" type:document date:2025-* "guide technique"
```

### Recherche globale

Pour rechercher dans **toutes vos collections** :
1. Allez dans l'onglet **Tout** ou **Recherche globale**
2. Entrez votre requête
3. Les résultats montreront de quelle collection provient chaque élément

## Gestion avancée des collections

### Partager une collection

{% stepper %}
{% step %}
#### Sélectionner la collection

1. Ouvrez la collection que vous souhaitez partager
2. Cliquez sur **Partager** (icône 👥)
{% endstep %}

{% step %}
#### Ajouter des membres

1. Entrez les **noms ou emails** des personnes à ajouter
2. Ou sélectionnez une **équipe** complète
3. Choisissez le **niveau d'accès** :
   - **Lecture seule** : Visualisation uniquement
   - **Lecture/Écriture** : Peut ajouter et modifier du contenu
   - **Administrateur** : Peut gérer les paramètres de la collection
{% endstep %}

{% step %}
#### Définir les permissions

- **Accès limité** : Seuls les membres ajoutés peuvent voir la collection
- **Accès public** (si autorisé) : Tous les utilisateurs de l'organisation peuvent voir la collection
- **Accès externe** : Permettre l'accès à des personnes en dehors de l'organisation (avec caution)

{% hint style="warning" %}
Soyez prudent avec le partage externe. Respectez toujours les politiques de confidentialité de votre organisation.
{% endhint %}
{% endstep %}

{% step %}
#### Envoyer les invitations

Cliquez sur **Envoyer les invitations**. Les membres recevront une notification et pourront accéder à la collection.
{% endstep %}
{% endstepper %}

### Modifier une collection

1. Ouvrez la collection
2. Cliquez sur **⋯** (menu) > **Modifier la collection**
3. Modifiez le nom, la description, l'icône ou les paramètres
4. Cliquez sur **Enregistrer**

### Supprimer une collection

{% hint style="danger" %}
**Attention** : La suppression d'une collection est irréversible et supprimera tout son contenu.
{% endhint %}

1. Ouvrez la collection
2. Cliquez sur **⋯** (menu) > **Supprimer la collection**
3. Confirmez la suppression en entrant le nom de la collection
4. Cliquez sur **Supprimer définitivement**

### Archiver une collection

Si vous ne souhaitez plus utiliser une collection mais voulez conserver son contenu :

1. Ouvrez la collection
2. Cliquez sur **⋯** (menu) > **Archiver**
3. La collection sera masquée mais conservée
4. Vous pourrez la **désarchiver** plus tard si besoin

## Organiser les collections

### Créer des sous-collections

Organisez vos collections de manière hiérarchique :

1. Dans une collection, cliquez sur **+ Nouvelle sous-collection**
2. Donnez-lui un nom
3. Les sous-collections héritent des permissions de la collection parente

Exemple de structure :
```
Projet Alpha
├── Documentation
│   ├── Technique
│   └── Utilisateur
├── Réunions
│   └── Comptes-rendus
└── Livrables
```

### Trier et filtrer

- **Trier par** : Nom, Date de création, Date de modification, Taille
- **Filtrer par** : Type, Catégorie, Visibilité
- **Affichage** : Liste, Grille, Carte

### Collections favorites

Marquez vos collections les plus utilisées :

1. Sur une collection, cliquez sur **⭐** (étoile)
2. Les collections favorites apparaissent en haut de la liste
3. Accès rapide depuis la barre latérale

## Fonctionnalités spéciales

### Indexation avancée

Les collections peuvent avoir des paramètres d'indexation spécifiques :

- **Profondeur d'indexation** : Basique, Complète, Avancée
- **Langues** : Sélectionnez les langues à indexer
- **Mots-clés** : Ajoutez des mots-clés pour améliorer la recherche
- **Exclusions** : Fichiers ou dossiers à exclure de l'indexation

### Recherche dans le contenu

Avec l'indexation avancée, vous pouvez :

- Rechercher **dans le texte complet** des documents
- Trouver des **citations spécifiques**
- Rechercher par **métadonnées** (auteur, date, etc.)
- Utiliser la **recherche sémantique** pour trouver des concepts similaires

### Intégration avec les outils

Les collections s'intègrent avec d'autres fonctionnalités :

- **Recherche web** : Stockez les résultats de recherche dans une collection
- **Résumé** : Résumez tous les documents d'une collection
- **Analytique** : Suivez l'utilisation de chaque collection

## Bonnes pratiques

### Nommage des collections

- ✅ **Soyez descriptif** : "Projet Alpha - Spécifications Techniques"
- ✅ **Utilisez des préfixes** : "[Client] Acme - Contrats 2025"
- ✅ **Ajoutez des dates** si pertinent : "Réunion Hebdo - 2025-06"
- ❌ **Évitez** : "Collection 1", "Mes docs", "Nouveau dossier"

### Organisation

- **Regroupez par projet** : Une collection par projet majeur
- **Regroupez par équipe** : Collections partagées par équipe
- **Regroupez par type** : Collections séparées pour différents types de documents
- **Archivez l'ancien contenu** : Gardez votre espace de travail propre

### Sécurité

- **Vérifiez les permissions** avant de partager
- **Utilisez des collections privées** pour les documents sensibles
- **Archivez au lieu de supprimer** pour les documents importants
- **Respectez les politiques** de votre organisation

## Résolution des problèmes

<details>
<summary>Je ne vois pas une collection partagée</summary>

- Vérifiez que vous avez été ajouté à la collection
- Vérifiez vos notifications pour les invitations
- Vérifiez que vous êtes dans le bon espace de travail
- Contactez l'administrateur de la collection

</details>

<details>
<summary>La recherche dans une collection ne fonctionne pas</summary>

- Vérifiez que l'indexation est activée pour cette collection
- Attendez que l'indexation se termine (peut prendre quelques minutes)
- Vérifiez que vous utilisez les bons termes de recherche
- Essayez une recherche plus large

</details>

<details>
<summary>Je ne peux pas ajouter de documents à une collection</summary>

- Vérifiez que vous avez les permissions d'écriture
- Vérifiez la limite de stockage de votre organisation
- Vérifiez le type de fichier (certains types peuvent être bloqués)
- Essayez avec un fichier plus petit

</details>

<details>
<summary>Une collection a disparu</summary>

- Vérifiez dans l'onglet **Archivées**
- Vérifiez si vous avez été retiré de la collection
- Contactez votre administrateur
- Vérifiez la corbeille (si disponible)

</details>

## Exemples d'utilisation

### Scénario 1 : Gestion de projet

**Collection** : "Projet Phoenix - Documentation"

**Contenu** :
- Spécifications techniques
- Comptes-rendus de réunion
- Diagrammes d'architecture
- Documentation utilisateur
- Backlog produit

**Permissions** : Équipe projet (Lecture/Écriture), Client (Lecture seule)

### Scénario 2 : Ressources d'équipe

**Collection** : "Équipe Marketing - Ressources"

**Contenu** :
- Guides de branding
- Modèles de présentation
- Études de marché
- Calendrier éditorial
- Bibliothèques d'images

**Permissions** : Tous les membres de l'équipe Marketing

### Scénario 3 : Archivage client

**Collection** : "Client Acme - Contrats et Documents"

**Contenu** :
- Contrats signés
- Propositions commerciales
- Correspondance
- Factures
- Rapports de projet

**Permissions** : Équipe commerciale + Client Acme (accès externe)

## Ressources connexes

{% content-ref url="documents.md" %}
[documents.md](documents.md)
{% endcontent-ref %}

{% content-ref url="summarize.md" %}
[summarize.md](summarize.md)
{% endcontent-ref %}

{% content-ref url="web-search.md" %}
[web-search.md](web-search.md)
{% endcontent-ref %}
