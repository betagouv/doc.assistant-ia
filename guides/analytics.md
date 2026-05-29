---
description: >-
  Scorez les messages, suivez les statistiques d'utilisation et analysez les
  performances de votre assistant IA.
icon: chart-bar
---

# Analytique et scoring

Votre assistant IA intègre des **fonctionnalités d'analytique et de scoring** pour vous aider à évaluer la qualité des réponses, suivre l'utilisation et améliorer continuellement l'expérience. Ces fonctionnalités sont conçues pour respecter votre vie privée tout en fournissant des insights utiles.

{% hint style="success" %}
**Amélioration continue** : Vos retours aident à améliorer la qualité des réponses pour tous les utilisateurs.
{% endhint %}

## Scoring des messages

### Comment scorer un message

Après chaque réponse de l'assistant, vous pouvez lui attribuer un score :

{% stepper %}
{% step %}
#### Trouver les boutons de scoring

À la fin de chaque réponse, vous verrez deux boutons :
- **👍** (Pouce levé) : Réponse utile
- **👎** (Pouce baissé) : Réponse non utile
{% endstep %}

{% step %}
#### Donnez votre feedback

Cliquez sur le bouton qui correspond à votre avis :
- **👍** : La réponse a répondu à votre question ou a été utile
- **👎** : La réponse n'était pas pertinente, incorrecte ou incomplète
{% endstep %}

{% step %}
#### Ajouter un commentaire (optionnel)

Après avoir cliqué sur 👎, vous pouvez ajouter un **commentaire** pour expliquer :
- Ce qui n'allait pas avec la réponse
- Ce qui manquait
- Comment la réponse pourrait être améliorée

Cela aide l'assistant à apprendre et à s'améliorer.
{% endstep %}
{% endstepper %}

### Échelle de scoring

Les scores sont utilisés pour :

| Score | Signification | Impact |
|-------|---------------|--------|
| **👍** | Réponse utile | Améliore la confiance dans ce type de réponse |
| **👎** | Réponse non utile | Signale un problème à corriger |
| **+ Commentaire** | Feedback détaillé | Fournit des informations précises pour l'amélioration |

### Quand scorer ?

✅ **Scorez toujours** quand une réponse est particulièrement utile ou non utile
✅ **Ajoutez un commentaire** si vous pouvez expliquer pourquoi
✅ **Scorez les réponses importantes** qui impactent votre travail
✅ **Signalez les erreurs** factuelles ou importantes

❌ **Ne scorez pas** si vous êtes neutre ou indécis
❌ **Ne scorez pas** par habitude sans réfléchir
❌ **N'abusez pas** du scoring négatif pour des préférences personnelles

## Statistiques d'utilisation

### Statistiques personnelles

Accédez à vos propres statistiques :

1. Allez dans **Paramètres** > **Mes statistiques**
2. Vous verrez :
   - **Nombre total de conversations**
   - **Nombre de messages échangés**
   - **Taux de satisfaction** (pourcentage de réponses marquées 👍)
   - **Modèles les plus utilisés**
   - **Types de questions les plus fréquents**

### Statistiques par collection

Pour les collections que vous gérez :

1. Ouvrez la collection
2. Cliquez sur **Statistiques** (icône 📊)
3. Vous verrez :
   - **Nombre de documents**
   - **Fréquence d'utilisation**
   - **Types de fichiers les plus consultés**
   - **Mots-clés les plus recherchés**

### Statistiques d'équipe (si autorisé)

Les administrateurs peuvent voir les statistiques agrégées :

- **Utilisation globale** de l'assistant dans l'organisation
- **Tendances d'utilisation** par période
- **Modèles les plus populaires**
- **Types de questions courantes**

{% hint style="info" %}
Les statistiques d'équipe sont **anonymisées** et ne contiennent pas d'informations personnelles identifiables.
{% endhint %}

## Langfuse Integration

Votre assistant utilise **Langfuse** pour l'analyse avancée et le scoring des messages :

### Fonctionnalités Langfuse

- 📊 **Suivi des conversations** : Historique complet des interactions
- 🎯 **Scoring avancé** : Évaluation détaillée des réponses
- 📈 **Tableaux de bord** : Visualisation des données d'utilisation
- 🔍 **Analyse des tendances** : Identification des schémas d'utilisation
- 🎨 **Personnalisation** : Adaptation des paramètres selon les retours

### Comment accéder à Langfuse

1. Allez dans **Paramètres** > **Analytique avancée**
2. Cliquez sur **Ouvrir Langfuse** (si vous avez les permissions)
3. Vous serez redirigé vers le tableau de bord Langfuse

### Métriques Langfuse

| Métrique | Description |
|----------|-------------|
| **Temps de réponse** | Temps moyen pour générer une réponse |
| **Longueur des réponses** | Nombre moyen de tokens par réponse |
| **Taux de satisfaction** | Pourcentage de réponses marquées 👍 |
| **Taux de scoring** | Pourcentage de messages qui reçoivent un score |
| **Utilisation par modèle** | Répartition des modèles utilisés |

## PostHog Integration

PostHog est utilisé pour **l'analytique de l'application** (si activé) :

### Fonctionnalités PostHog

- 👁️ **Session recording** (enregistrements anonymisés) : Comprendre comment les utilisateurs interagissent
- 📊 **Event tracking** : Suivre les actions clés dans l'application
- 🎯 **Feature flags** : Activer/désactiver des fonctionnalités pour des tests
- 📈 **Funnel analysis** : Comprendre les parcours utilisateurs
- 🌍 **Heatmaps** : Visualiser les zones les plus cliquées

### Respect de la vie privée

- ✅ **Anonymisation** : Toutes les données sont anonymisées
- ✅ **Opt-out possible** : Vous pouvez désactiver le suivi analytique
- ✅ **Conformité RGPD** : Respect des réglementations européennes
- ✅ **Transparence** : Politique claire sur les données collectées

### Gérer vos préférences

1. Allez dans **Paramètres** > **Confidentialité**
2. Trouvez la section **Analytique**
3. Activez ou désactivez :
   - **Suivi d'utilisation**
   - **Enregistrements de session** (anonymisés)
   - **Partage des données** avec l'équipe produit (anonymisées)

## Tableaux de bord

### Tableau de bord utilisateur

Votre propre tableau de bord personnel :

- **Activité récente** : Vos dernières conversations
- **Historique des scores** : Vos évaluations des réponses
- **Utilisation des modèles** : Quels modèles vous utilisez le plus
- **Temps de réponse moyen** : Performance de l'assistant pour vous

### Tableau de bord d'équipe

Pour les administrateurs et managers :

- **Adoption globale** : Combien d'utilisateurs actifs
- **Satisfaction moyenne** : Score global de l'équipe
- **Modèles populaires** : Quels modèles sont les plus utilisés
- **Tendances** : Évolution de l'utilisation au fil du temps

### Tableau de bord des collections

Pour chaque collection :

- **Nombre d'accès** : Combien de fois la collection a été consultée
- **Documents populaires** : Quels documents sont les plus consultés
- **Recherches fréquentes** : Quels termes sont les plus recherchés
- **Utilisateurs actifs** : Qui utilise cette collection

## Rapports et export

### Générer un rapport

1. Allez dans **Analytique** > **Rapports**
2. Sélectionnez le type de rapport :
   - **Rapport d'utilisation** : Statistiques globales
   - **Rapport de satisfaction** : Analyse des scores
   - **Rapport par collection** : Focus sur une collection spécifique
   - **Rapport personnalisé** : Créez votre propre rapport
3. Sélectionnez la période (jour, semaine, mois, personnalisé)
4. Cliquez sur **Générer le rapport**

### Exporter les données

Les données peuvent être exportées dans plusieurs formats :

- **CSV** : Pour analyse dans Excel ou Google Sheets
- **JSON** : Pour intégration avec d'autres systèmes
- **PDF** : Pour impression ou partage
- **Excel** : Format tableur avancé

### Planification des rapports

Configurez des rapports automatiques :

1. Allez dans **Analytique** > **Planification**
2. Cliquez sur **+ Nouveau rapport planifié**
3. Configurez :
   - **Type de rapport**
   - **Fréquence** (quotidien, hebdomadaire, mensuel)
   - **Destinataires** (emails)
   - **Format** (CSV, PDF, etc.)
4. Activez le rapport

## Confidentialité et sécurité

### Ce que nous suivons

✅ **Métadonnées d'utilisation** : Nombre de conversations, modèles utilisés, etc.
✅ **Scores et feedbacks** : Vos évaluations des réponses
✅ **Statistiques agrégées** : Données anonymisées pour l'amélioration du service

### Ce que nous NE suivons PAS

❌ **Contenu des conversations** (sauf si vous le partagez explicitement pour le support)
❌ **Informations personnelles identifiables** dans les statistiques
❌ **Vos données personnelles** sans votre consentement
❌ **Votre activité** en dehors de l'application

### Vos droits

- **Droit d'accès** : Voir quelles données sont collectées sur vous
- **Droit de rectification** : Corriger les informations inexactes
- **Droit d'effacement** : Supprimer vos données
- **Droit d'opposition** : Refuser le suivi analytique
- **Droit à la portabilité** : Exporter vos données

Pour exercer ces droits, contactez : dpo@votreentreprise.com

## Bonnes pratiques

### Pour les utilisateurs

1. **Scorez régulièrement** pour aider à améliorer le service
2. **Soyez honnête** dans vos évaluations
3. **Ajoutez des commentaires** quand c'est utile
4. **Consultez vos statistiques** pour comprendre votre utilisation
5. **Ajustez vos préférences** de confidentialité selon vos besoins

### Pour les administrateurs

1. **Surveillez les tendances** d'utilisation et de satisfaction
2. **Identifiez les problèmes** récurrents via les scores négatifs
3. **Formez les utilisateurs** sur les bonnes pratiques de scoring
4. **Ajustez les modèles** en fonction des retours
5. **Communiquez** les améliorations basées sur les feedbacks

## Résolution des problèmes

<details>
<summary>Je ne vois pas mes statistiques</summary>

- Vérifiez que vous êtes connecté avec le bon compte
- Vérifiez que l'analytique est activée pour votre organisation
- Essayez de rafraîchir la page
- Contactez votre administrateur

</details>

<details>
<summary>Je ne peux pas scorer une réponse</summary>

- Vérifiez que vous n'êtes pas en mode lecture seule
- Vérifiez que la fonction de scoring est activée
- Essayez de cliquer sur les boutons 👍/👎 à côté de la réponse
- Contactez le support si le problème persiste

</details>

<details>
<summary>Mes scores ne sont pas enregistrés</summary>

- Vérifiez votre connexion internet
- Essayez de rafraîchir la page et de scorer à nouveau
- Vérifiez que vous n'avez pas désactivé JavaScript
- Contactez le support technique

</details>

<details>
<summary>Je ne veux pas être suivi</summary>

- Allez dans **Paramètres** > **Confidentialité**
- Désactivez toutes les options d'analytique
- Vos données ne seront plus collectées
- Les données déjà collectées peuvent être supprimées sur demande

</details>

## Exemples d'utilisation

### Scénario 1 : Amélioration de la qualité

**Problème** : Un utilisateur remarque que l'assistant donne souvent des réponses incorrectes sur un sujet spécifique.

**Solution** :
1. L'utilisateur score 👎 plusieurs réponses incorrectes
2. Il ajoute des commentaires expliquant le problème
3. L'équipe produit identifie le schéma via les statistiques
4. L'assistant est reconfiguré ou les documents sources sont mis à jour
5. La qualité s'améliore pour ce sujet

### Scénario 2 : Optimisation des coûts

**Problème** : Une équipe utilise beaucoup un modèle coûteux pour des tâches simples.

**Solution** :
1. L'administrateur consulte les statistiques d'utilisation des modèles
2. Il identifie que Mistral Large est utilisé pour des questions simples
3. Il recommande d'utiliser Mistral Small pour ces cas
4. L'équipe ajuste ses habitudes
5. Les coûts sont optimisés sans perte de qualité

### Scénario 3 : Identification des besoins

**Problème** : L'organisation veut savoir quelles fonctionnalités sont les plus utilisées.

**Solution** :
1. Les administrateurs consultent les statistiques globales
2. Ils voient que la recherche web et le résumé sont très populaires
3. Ils décident d'investir dans l'amélioration de ces fonctionnalités
4. Des formations sont organisées sur ces sujets
5. L'adoption et la satisfaction augmentent

## Ressources connexes

{% content-ref url="models.md" %}
[models.md](models.md)
{% endcontent-ref %}

{% content-ref url="collections.md" %}
[collections.md](collections.md)
{% endcontent-ref %}

{% content-ref url="../core-concepts/permissions.md" %}
[permissions.md](../core-concepts/permissions.md)
{% endcontent-ref %}
