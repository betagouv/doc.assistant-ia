---
description: >-
  Sélectionnez et utilisez différents modèles de langage (Mistral, etc.) directement
  dans l'interface de chat.
icon: microchip
---

# Sélection des modèles

Votre assistant prend en charge **plusieurs modèles de langage** (LLM) que vous pouvez sélectionner directement dans l'interface de chat. Chaque modèle a ses propres forces, spécialisations et cas d'usage.

{% hint style="success" %}
**Multi-modèles** : Changez de modèle à tout moment pour adapter la réponse à vos besoins spécifiques.
{% endhint %}

## Modèles disponibles

Voici les modèles actuellement disponibles (la liste peut varier selon la configuration de votre organisation) :

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th></th></tr></thead><tbody><tr><td><h4><i class="fa-brain" style="color:$primary;"></i></h4></td><td><strong>Mistral Large</strong></td><td>Modèle puissant et polyvalent, excellent pour les tâches complexes et le raisonnement.</td><td>🇫🇷/🇬🇧/🇪🇺</td></tr><tr><td><h4><i class="fa-rocket" style="color:$primary;"></i></h4></td><td><strong>Mistral Small</strong></td><td>Modèle rapide et économique, idéal pour les tâches simples et les réponses rapides.</td><td>🇫🇷/🇬🇧/🇪🇺</td></tr><tr><td><h4><i class="fa-code" style="color:$primary;"></i></h4></td><td><strong>Code Llama</strong></td><td>Spécialisé pour la programmation, la compréhension et la génération de code.</td><td>🌍</td></tr><tr><td><h4><i class="fa-lightbulb" style="color:$primary;"></i></h4></td><td><strong>Modèle par défaut</strong></td><td>Modèle optimisé pour la plupart des tâches générales.</td><td>🌍</td></tr></tbody></table>

## Comment changer de modèle

{% stepper %}
{% step %}
#### Méthode 1 : Sélecteur dans le champ de message

1. Ouvrez une conversation avec l'assistant
2. Dans le champ de message, cliquez sur l'icône du modèle actuel (en haut à droite)
3. Un menu déroulant s'affiche avec tous les modèles disponibles
4. Sélectionnez le modèle souhaité
5. Le modèle change immédiatement pour la conversation en cours

{% hint style="info" %}
Le changement de modèle s'applique uniquement à la conversation active. Chaque conversation peut utiliser un modèle différent.
{% endhint %}
{% endstep %}

{% step %}
#### Méthode 2 : Commande textuelle

Vous pouvez aussi demander à l'assistant de changer de modèle :

```
Vous : "Utilise Mistral Large pour cette question"
Assistant : "D'accord, je passe à Mistral Large. Quelle est votre question ?"
```

Ou plus spécifiquement :
```
Vous : "Réponds avec le modèle Code Llama : comment optimiser cette fonction Python ?"
```
{% endstep %}

{% step %}
#### Méthode 3 : Préférence par défaut

1. Allez dans **Paramètres** > **Préférences**
2. Sélectionnez votre **modèle par défaut** préféré
3. Ce modèle sera utilisé pour toutes les nouvelles conversations

{% hint style="warning" %}
Vous pouvez toujours changer de modèle manuellement pour une conversation spécifique.
{% endhint %}
{% endstep %}
{% endstepper %}

## Quand utiliser chaque modèle

| Besoin | Modèle recommandé | Pourquoi |
|--------|-------------------|---------|
| **Questions générales** | Modèle par défaut ou Mistral Small | Équilibre parfait entre qualité et vitesse |
| **Analyse complexe** | Mistral Large | Meilleure compréhension et raisonnement |
| **Génération de code** | Code Llama | Spécialement entraîné pour le code |
| **Tâches créatives** | Mistral Large | Meilleure créativité |
| **Réponses rapides** | Mistral Small | Plus rapide, moins coûteux |
| **Résumé long** | Mistral Large | Meilleure gestion du contexte |

## Personnalisation des modèles

Si votre organisation le permet, vous pouvez personnaliser les paramètres de certains modèles :

### Paramètres communs

| Paramètre | Description | Valeurs typiques |
|-----------|-------------|------------------|
| **Température** | Contrôle la créativité/randomité | 0.0 (déterministe) - 1.0 (créatif) |
| **Top P** | Contrôle la diversité des réponses | 0.1 - 1.0 |
| **Top K** | Nombre de tokens à considérer | 1 - 100 |
| **Max Tokens** | Longueur maximale de la réponse | 512 - 4096 |

### Comment ajuster les paramètres

1. Sélectionnez un modèle dans le sélecteur
2. Cliquez sur l'icône **⚙️** (paramètres) à côté du nom du modèle
3. Ajustez les curseurs pour chaque paramètre
4. Cliquez sur **Appliquer**

Exemple de configuration pour l'analyse technique :
- Température : 0.3 (réponses précises)
- Top P : 0.9
- Max Tokens : 2048

Exemple de configuration pour la créativité :
- Température : 0.8 (réponses variées)
- Top P : 0.95
- Max Tokens : 1024

## Comparaison des modèles

### Forces relatives

| Modèle | Raisonnement | Code | Créativité | Vitesse | Coût |
|--------|-------------|------|------------|---------|------|
| Mistral Large | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | $$$ |
| Mistral Small | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | $ |
| Code Llama | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐⭐ | $$ |
| Modèle par défaut | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | $$ |

### Exemples concrets

#### Pour l'analyse de données
```
Vous : "Analyse ces données de vente et identifie les tendances principales. [Utilise Mistral Large]"
```

#### Pour la génération de code
```
Vous : "Écris une fonction Python pour parser ce JSON. [Utilise Code Llama]"
```

#### Pour la créativité
```
Vous : "Invente 10 idées de noms pour un produit de cybersécurité. [Utilise Mistral Large avec température 0.9]"
```

## Préférences et historique

### Historique des modèles utilisés

Votre assistant garde une trace des modèles que vous avez utilisés :

1. Allez dans **Paramètres** > **Historique des modèles**
2. Voir quels modèles vous avez utilisés le plus souvent
3. Identifiez vos préférences

### Modèles favoris

Marquez vos modèles préférés pour un accès rapide :

1. Dans le sélecteur de modèles, cliquez sur **⭐** à côté d'un modèle
2. Les modèles favoris apparaissent en haut de la liste
3. Utilisez jusqu'à 5 modèles favoris

## Dépannage

<details>
<summary>Le sélecteur de modèles n'apparaît pas</summary>

- Vérifiez que votre organisation a activé la fonction multi-modèles
- Essayez de rafraîchir la page
- Vérifiez que vous utilisez la dernière version de l'application
- Contactez votre administrateur

</details>

<details>
<summary>Un modèle ne répond pas</summary>

- Le modèle peut être temporairement indisponible
- Vérifiez votre connexion internet
- Essayez un autre modèle
- Attendez quelques minutes et réessayez

</details>

<details>
<summary>Les réponses sont incohérentes</summary>

- Essayez de réduire la température
- Vérifiez que vous utilisez le bon modèle pour la tâche
- Reformulez votre question pour être plus précis
- Essayez un autre modèle

</details>

<details>
<summary>Je ne vois pas mon modèle préféré</summary>

- Votre organisation peut avoir restreint certains modèles
- Contactez votre administrateur pour demander l'accès
- Vérifiez si le modèle est disponible dans votre région

</details>

## Bonnes pratiques

1. **Commencez simple** : Utilisez le modèle par défaut pour la plupart des tâches
2. **Adaptez-vous** : Changez de modèle selon la complexité de la tâche
3. **Expérimentez** : Essayez différents modèles pour voir lequel fonctionne le mieux
4. **Évaluez** : Donnez des retours (👍/👎) pour aider à améliorer les recommandations
5. **Personnalisez** : Ajustez les paramètres pour optimiser les résultats

## Ressources connexes

{% content-ref url="web-search.md" %}
[web-search.md](web-search.md)
{% endcontent-ref %}

{% content-ref url="documents.md" %}
[documents.md](documents.md)
{% endcontent-ref %}

{% content-ref url="summarize.md" %}
[summarize.md](summarize.md)
{% endcontent-ref %}
