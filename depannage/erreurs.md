---
description: Guide de dépannage pour résoudre les problèmes courants avec l'Assistant IA
icon: wrench
---

# Comprendre les erreurs de l'Assistant

Cette section vous aide à résoudre les problèmes les plus courants rencontrés avec l'Assistant IA. **L'Assistant vous indiquera toujours l'erreur qu'il rencontre**, soit via un message d'erreur technique, soit par un message explicite comme :

> _"Je n'arrive pas à accéder à internet, vérifiez que la configuration me l'autorise."_

Pensez à **rafraîchir la page** (F5 ou Ctrl+R) pour vérifier s'il n'y a pas un **bandeau d'erreur** en haut de l'interface indiquant l'indisponibilité de certaines fonctionnalités. Ces dernières peuvent être configurées par l'équipe de l'Assistant ou mises à jour automatiquement lorsque des fonctionnalités cassées sont détectées.

Si vous rencontrez un **vrai message d'erreur technique** (qui ne ressemble pas à une réponse normale de l'Assistant), vous pouvez réessayer dans une nouvelle conversation. La plupart de ces erreurs vous empêcherons de continuer dans cette conversation, car celle-ci est en message d'erreur.

***

## Problèmes de connexion

### Je n'arrive pas à me connecter

**Symptômes :**

* La page de connexion ne répond pas
* Erreur après identification ProConnect
* Message "Accès refusé"

**Solutions :**

1. **Vérifiez votre connexion ProConnect**
   * Assurez-vous d'utiliser vos identifiants professionnels
   * Si vous avez oublié votre mot de passe, réinitialisez-le via [ProConnect](https://proconnect.gouv.fr/)
2. **Vérifiez votre éligibilité**
   * L'Assistant IA est accessible à tous les agents des **administrations de l'État et de leurs organismes de tutelle**
   * Si vous pensez avoir droit à l'accès mais que la connexion échoue, contactez votre référent IA ministériel
3. **Problèmes techniques**
   * Essayez un autre navigateur (Chrome, Firefox, Edge recommandés)
   * Vide le cache de votre navigateur
   * Désactivez les extensions qui pourraient bloquer la connexion
4. **Maintenance en cours**
   * Vérifiez l'état du service sur [la page de statut](https://statut.numerique.gouv.fr/)

{% hint style="info" %}
Si le problème persiste, [signalez-le à l'équipe](../troubleshooting/report-issue.md).
{% endhint %}

### Les réponses sont incomplètes ou coupées

**Solutions :**

1. **Attendez quelques secondes** - La génération peut être lente selon la charge
2. **Actualisez la conversation**
3. **Reformulez votre demande** de manière plus concise
4. **Divisez les questions complexes** en plusieurs messages

***

## Problèmes avec les documents

### Je ne peux pas téléverser de documents

**Symptômes :**

* Bouton de téléversement grisé
* Erreur lors du glisser-déposer
* Message **"Type de fichier non supporté"** (affiché par l'Assistant)

**Solutions :**

1. **Vérifiez le type de fichier**
   * Formats supportés : PDF, images (JPG, PNG, WEBP), documents bureautiques (.md, .docx, .pptx, .xlsx)
   * Taille maximale : 10 Mo par fichier (variable selon la configuration)
2. **Vérifiez la disponibilité de la fonctionnalité**
   * Le téléversement de documents peut être temporairement désactivé pour maintenance
   * Un **bandeau d'erreur** peut apparaître en haut de page
3. **Essayez un autre navigateur**
4. **Vérifiez vos permissions**
   * Certaines restrictions peuvent s'appliquer selon votre administration

### L'Assistant ne comprend pas mon document

**Solutions :**

1. **Vérifiez la qualité du document**
   * Les PDF mal scannés ou les images de mauvaise qualité peuvent ne pas être lisibles
   * Essayez de fournir le texte directement
2. **Soyez précis dans vos questions**
   * Au lieu de "Qu'est-ce qu'il y a dans ce document ?", demandez "Quel est le montant total mentionné dans la section budget ?"
3. **Donnez du contexte**
   * "Ce document est un compte rendu de réunion. Peux-tu m'en faire un résumé ?"

***

## Problèmes avec la recherche web

### La recherche web ne fonctionne pas

**Symptômes :**

* Bouton de recherche web grisé
* Pas de résultats de recherche
* Erreur **"Impossible d'effectuer la recherche"** ou **"La recherche web est désactivée"** (affiché par l'Assistant)

**Solutions :**

1. **Vérifiez que la recherche est activée**
   * Cliquez sur l'icône 🌐 dans la barre de message
   * Ou activez la "recherche intelligente" dans vos paramètres
2. **Vérifiez votre question**
   * La recherche fonctionne mieux avec des questions claires et précises
   * Évitez les questions trop vagues
3. **Problème temporaire**
   * Le service de recherche peut être temporairement indisponible
   * **Rafraîchissez la page** pour vérifier l'affichage d'un bandeau d'erreur
   * Réessayez plus tard
4. **Fonctionnalité désactivée par votre administration ?**
   * Certaines administrations limitent l'accès à la recherche web pour des raisons de sécurité
   * Contactez votre référent IA pour vérifier la configuration

***

## Problèmes de performance

### L'application est lente

**Solutions :**

1. **Vérifiez votre connexion internet**
2. **Fermez les onglets inutilisés**
3. **Utilisez un navigateur moderne** (Chrome, Firefox, Edge, Safari récent)
4. **Videz le cache** de votre navigateur
5. **Désactivez les extensions** gourmandes en ressources

### Les conversations mettent du temps à charger

**Solutions :**

1. **Réduisez le nombre de conversations ouvertes**
2. **Archivez les anciennes conversations**
3. **Utilisez la recherche** pour trouver des conversations spécifiques au lieu de tout parcourir

***

## Problèmes d'affichage

### L'interface ne s'affiche pas correctement

**Solutions :**

1. **Actualisez la page** (F5 ou Ctrl+R)
2. **Videz le cache** du navigateur
3. **Essayez un autre navigateur**
4. **Vérifiez la résolution** de votre écran
5. **Désactivez le mode zoom** (Ctrl+0 pour réinitialiser)

### Les messages ne s'affichent pas correctement

**Solutions :**

1. **Actualisez la conversation**
2. **Vérifiez que JavaScript est activé** dans votre navigateur
3. **Essayez de copier-coller** le message problématique

***

## Problèmes divers

### Je ne sais pas quelles données je peux mettre dans l'Assistant

**Règles générales :**

✅ **Autorisé :**

* Données publiques
* Données professionnelles non sensibles
* Informations déjà publiques ou destinées à être publiées
* Données nécessaires à l'exécution de vos missions

❌ **Interdit :**

* **Données personnelles** (RGPD) : noms, adresses, numéros de sécurité sociale, etc.
* **Données sensibles** au sens de l'ANSSI ou de la loi SREN
* **Données confidentielles** ou classifiées (Diffusion restreinte, Secret, Très Secret)
* **Données médicales**

**Bonnes pratiques :**

* **Anonymisez** les données avant de les soumettre
* **Vérifiez** avec votre référent IA ou votre DPO en cas de doute
* **Préférez** les données déjà publiques ou déclassifiées

**Pour en savoir plus :** Consultez [notre page sur la protection des données](../documentation-legale/data-protection.md)

### L'Assistant donne des réponses incorrectes

**Solutions :**

1. **Vérifiez les faits** - L'Assistant peut faire des erreurs, toujours croiser les informations
2. **Reformulez votre question** de manière plus précise
3. **Fournissez plus de contexte** ou de documents de référence
4. **Activez la recherche web** pour des informations actualisées
5. **Signalez l'erreur** pour aider à améliorer le service

**Rappel :** L'Assistant est un **outil d'aide**, pas une source de vérité absolue. Vous conservez la responsabilité finale de vérifier les informations.

***

## Besoin d'aide supplémentaire ?

Si vous ne trouvez pas de solution à votre problème :

1. [**Consultez les questions fréquentes**](../troubleshooting/faq.md)
2. [**Signalez un problème**](../troubleshooting/report-issue.md) à l'équipe technique
3. **Contactez votre référent IA** ministériel
4. **Rejoignez le canal Tchap** dédié : [#assistant-ia](https://tchap.gouv.fr/)

{% hint style="warning" %}
**Important :** En cas de **vrai message d'erreur technique** (trace, code, ou message anormal), fermez la conversation et réessayez dans une **nouvelle fenêtre**.

En cas de problème urgent ou de suspicion de fuite de données, contactez immédiatement votre référent IA ou l'équipe DINUM via les canaux officiels.
{% endhint %}
