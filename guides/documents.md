---
description: >-
  Glisser-déposer des fichiers, collection automatique, et gestion avancée des documents
  avec indexation RAG améliorée.
icon: file
---

# Gestion des documents

Votre assistant IA prend en charge le glisser-déposer de fichiers directement dans l'interface de chat, avec collection automatique et indexation avancée pour une recherche optimale.

{% hint style="success" %}
**Glisser-déposer activé** : Vous pouvez déposer des fichiers n'importe où sur la page pour les ajouter à votre conversation.
{% endhint %}

## Comment ajouter des documents

### Méthode 1 : Glisser-déposer

{% stepper %}
{% step %}
#### Préparer votre fichier

Assurez-vous que votre fichier est dans un format supporté :
- 📄 **Documents** : PDF, Word (.docx), Markdown (.md), Texte (.txt)
- 📊 **Feuilles de calcul** : Excel (.xlsx), CSV
- 🖼️ **Images** : PNG, JPG, WebP (pour analyse visuelle si activé)
- 📧 **Emails** : EML, MSG

{% hint style="warning" %}
**Types de fichiers interdits** : Certains types de fichiers sont bloqués pour des raisons de sécurité (exécutables, scripts, etc.).
{% endhint %}
{% endstep %}

{% step %}
#### Déposer le fichier

1. Ouvrez votre conversation avec l'assistant
2. Localisez le fichier sur votre ordinateur
3. **Glissez** le fichier depuis votre explorateur de fichiers
4. **Déposez** le n'importe où sur la page de chat

Le fichier sera automatiquement uploadé et processe.
{% endstep %}

{% step %}
#### Attendre le traitement

L'assistant va :
1. ✅ Vérifier le type de fichier
2. ✅ Extraire le texte (pour les PDFs, Word, etc.)
3. ✅ Indexer le contenu pour la recherche
4. ✅ Confirmer l'ajout avec un message

{% hint style="info" %}
Les fichiers volumineux peuvent prendre quelques secondes à traiter. Un indicateur de progression s'affichera.
{% endhint %}
{% endstep %}
{% endstepper %}

### Méthode 2 : Bouton d'upload

1. Cliquez sur l'icône **📎** (trombone) dans le champ de message
2. Sélectionnez le fichier depuis votre ordinateur
3. Cliquez sur **Ouvrir** pour uploader

### Méthode 3 : Collection automatique

Si l'option est activée, les documents que vous mentionnez ou référencez dans vos questions peuvent être **automatiquement collectés** par l'assistant.

Exemple :
```
Vous : "Pouvez-vous me dire ce qui est écrit dans le rapport_2025.pdf ?"
Assistant : "Je vais chercher le document 'rapport_2025.pdf' dans les documents disponibles..."
```

## Gestion des collections

Organisez vos documents en collections pour une meilleure organisation :

### Créer une nouvelle collection

1. Cliquez sur **Collections** dans la barre latérale
2. Cliquez sur **+ Nouvelle collection**
3. Donnez un nom à votre collection (ex: "Projet Alpha", "Documentation RH")
4. Ajoutez une description (optionnel)
5. Cliquez sur **Créer**

### Ajouter des documents à une collection

1. Ouvrez une collection existante
2. Glissez-déposez des fichiers dans la collection
3. Ou utilisez le bouton **+ Ajouter des documents**

### Rechercher dans une collection

Pour limiter la recherche à une collection spécifique :

```
Vous : "Recherchez dans la collection 'Projet Alpha' : quelle est la date de livraison ?"
```

## Fonctionnalités avancées

### Indexation RAG améliorée

Votre assistant utilise la **Recherche Augmentée par Génération (RAG)** pour :

- 🔍 **Chunking intelligent** : Diviser les grands documents en sections gérables
- 🧠 **Embeddings** : Créer des représentations vectorielles pour une recherche sémantique
- 🎯 **Reranking** : Prioriser les résultats les plus pertinents
- 🔄 **Mise à jour automatique** : Re-indexer les documents modifiés

### Traitement des documents

| Fonctionnalité | Description |
|--------------|-------------|
| **Extraction de texte** | Récupère le texte des PDFs, Word, etc. |
| **Analyse de structure** | Comprend les titres, sections, listes |
| **Détection de langue** | Identifie automatiquement la langue du document |
| **Nettoyage** | Supprime le formatage inutile |
| **Indexation** | Ajoute au système de recherche |

### Partage de documents

Partagez des documents avec d'autres utilisateurs ou équipes :

1. Ouvrez le document dans votre collection
2. Cliquez sur **Partager**
3. Sélectionnez les utilisateurs ou équipes
4. Choisissez le niveau de permission (Lecture seule, Lecture/Écriture)
5. Cliquez sur **Envoyer l'invitation**

{% hint style="warning" %}
Le partage est soumis aux politiques de sécurité de votre organisation.
{% endhint %}

## Bonnes pratiques

### Nommage des fichiers

- ✅ Utilisez des noms **clairs et descriptifs**
- ✅ Incluez des **dates ou versions** si pertinent
- ✅ Évitez les **caractères spéciaux** (#, %, &, etc.)
- ❌ Évitez les noms génériques comme "document.pdf" ou "fichier.txt"

Exemples :
- ✅ `rapport_ventes_Q1_2025.pdf`
- ✅ `guide_utilisateur_v2.1.docx`
- ❌ `fichier.pdf`

### Organisation des documents

- **Par projet** : Un dossier par projet
- **Par type** : Documents techniques, commerciaux, RH
- **Par date** : Archives par mois/année
- **Par équipe** : Documents spécifiques à une équipe

### Sécurité des documents

- ❌ **Ne téléchargez pas** de documents confidentiels ou sensibles
- ❌ **Ne partagez pas** de documents contenant des informations personnelles
- ✅ **Vérifiez** les politiques de votre entreprise avant de télécharger
- ✅ **Utilisez** les collections privées pour les documents sensibles

## Résolution des problèmes

<details>
<summary>Le fichier ne s'uploade pas</summary>

- Vérifiez que le type de fichier est supporté
- Vérifiez la taille du fichier (limite : 50Mo par défaut)
- Essayez avec un autre navigateur
- Vérifiez votre connexion internet
- Contactez le support si le problème persiste

</details>

<details>
<summary>Le document n'apparaît pas dans la recherche</summary>

- Attendez quelques minutes pour que l'indexation se termine
- Vérifiez que le document a été uploadé avec succès
- Essayez de re-uploader le document
- Vérifiez que vous recherchez dans la bonne collection

</details>

<details>
<summary>L'extraction de texte ne fonctionne pas</summary>

- Le document peut être protégé par un mot de passe
- Le document peut être corrompu
- Le format peut ne pas être supporté
- Essayez de convertir le document en PDF ou TXT

</details>

<details>
<summary>Je reçois une erreur "Type de fichier interdit"</summary>

Certains types de fichiers sont bloqués pour des raisons de sécurité :
- Fichiers exécutables (.exe, .bat, .sh, etc.)
- Scripts (.js, .py, .php, etc.)
- Archives (.zip, .rar, etc.)
- Fichiers système

Utilisez des formats de document standard (PDF, Word, TXT, etc.).

</details>

## Ressources connexes

{% content-ref url="collections.md" %}
[collections.md](collections.md)
{% endcontent-ref %}

{% content-ref url="summarize.md" %}
[summarize.md](summarize.md)
{% endcontent-ref %}

{% content-ref url="web-search.md" %}
[web-search.md](web-search.md)
{% endcontent-ref %}
