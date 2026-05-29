---
description: >-
  Fonctionnalités d'accessibilité et bonnes pratiques pour une utilisation
  inclusive de votre assistant IA.
icon: universal-access
---

# Accessibilité

Votre assistant IA est conçu pour être **accessible à tous les utilisateurs**, y compris ceux utilisant des technologies d'assistance. Nous nous engageons à respecter les normes d'accessibilité et à améliorer continuellement l'expérience pour tous.

{% hint style="success" %}
**Conforme aux normes** : Notre application suit les directives WCAG 2.1 AA pour l'accessibilité.
{% endhint %}

## Fonctionnalités d'accessibilité

### Navigation au clavier

L'ensemble de l'interface est **100% navigable au clavier** :

| Raccourci | Action | Description |
|----------|--------|-------------|
| `Tab` | Navigation | Passe au champ ou bouton suivant |
| `Shift + Tab` | Navigation inverse | Passe au champ ou bouton précédent |
| `Entrée` | Sélection | Active le bouton ou lien sélectionné |
| `Échap` | Fermer | Ferme les menus, modales et popups |
| `↑/↓` | Navigation dans les listes | Déplace la sélection dans les menus déroulants |
| `Ctrl + /` | Aide clavier | Affiche tous les raccourcis clavier |

### Raccourcis clavier spécifiques

| Raccourci | Action |
|----------|--------|
| `Ctrl + K` | Recherche globale | Recherchez dans toute la documentation |
| `Ctrl + N` | Nouvelle conversation | Commencez une nouvelle discussion |
| `Ctrl + Shift + N` | Nouveau document | Uploadez un nouveau document |
| `Ctrl + ,` | Préférences | Ouvrez les paramètres |
| `Ctrl + .` | Aide | Ouvrez l'aide contextuelle |

### Lecture d'écran

Votre assistant est **optimisé pour les lecteurs d'écran** (JAWS, NVDA, VoiceOver, etc.) :

✅ **Balises ARIA** : Tous les éléments interactifs ont des balises ARIA appropriées
✅ **Textes alternatifs** : Les images et icônes ont des descriptions textuelles
✅ **Structure sémantique** : Utilisation correcte des en-têtes (h1, h2, etc.)
✅ **Notifications accessibles** : Les messages et notifications sont annoncés correctement
✅ **Focus visible** : Le focus du clavier est toujours visible

#### Conseils pour les utilisateurs de lecteurs d'écran

1. **Navigation rapide** : Utilisez la touche `H` pour sauter d'en-tête en en-tête
2. **Listes** : Utilisez la touche `I` pour naviguer entre les éléments de liste
3. **Liens** : Utilisez la touche `Tab` ou `K` (dans NVDA) pour naviguer entre les liens
4. **Formulaires** : Utilisez la touche `F` pour naviguer entre les champs de formulaire

### Contraste et couleurs

- ✅ **Contraste élevé** : Tous les textes respectent un ratio de contraste minimum de 4.5:1
- ✅ **Mode sombre** : Disponible pour réduire la fatigue oculaire
- ✅ **Daltonisme** : Palette de couleurs adaptée aux différents types de daltonisme
- ✅ **Taille de police ajustable** : Agrandissez le texte selon vos besoins

#### Mode sombre

Activez le mode sombre pour une meilleure visibilité :

1. Allez dans **Paramètres** > **Apparence**
2. Sélectionnez **Mode sombre** ou **Suivre les préférences du système**
3. Le mode sera appliqué immédiatement

#### Personnalisation des couleurs

1. Allez dans **Paramètres** > **Apparence** > **Couleurs personnalisées**
2. Ajustez les couleurs de fond, de texte, des liens, etc.
3. Prévoyez vos couleurs pour les différents éléments

### Texte et lisibilité

#### Ajustement de la taille du texte

1. Utilisez les raccourcis du navigateur :
   - `Ctrl + +` : Agrandir le texte
   - `Ctrl + -` : Réduire le texte
   - `Ctrl + 0` : Réinitialiser la taille

2. Ou dans les paramètres de l'application :
   - Allez dans **Paramètres** > **Apparence**
   - Ajustez la **Taille de la police**

#### Espacement du texte

Pour les utilisateurs ayant des difficultés de lecture :

1. Allez dans **Paramètres** > **Accessibilité**
2. Activez **Espacement du texte augmenté**
3. Ajustez :
   - Espacement entre les lettres
   - Espacement entre les mots
   - Hauteur de ligne

#### Police de caractères

Choisissez parmi plusieurs polices adaptées :

| Police | Description | Adaptée pour |
|--------|-------------|-------------|
| **Open Sans** | Police moderne et lisible | Usage général |
| **Dyslexie** | Conçue pour les dyslexiques | Dyslexie |
| **Atkinson Hyperlegible** | Haute lisibilité | Faible vision |
| **Roboto** | Police neutre et claire | Usage général |
| **Verdana** | Police à empattement large | Lisibilité |

Pour changer de police :
1. Allez dans **Paramètres** > **Apparence**
2. Sélectionnez votre police préférée dans **Police de l'application**

### Sous-titres et transcriptions

Pour les contenus audio et vidéo intégrés :

- ✅ **Sous-titres** : Disponibles pour tout le contenu vidéo
- ✅ **Transcriptions** : Texte complet disponible pour les fichiers audio
- ✅ **Vitesse de lecture** : Ajustable pour les contenus audio/vidéo

## Paramètres d'accessibilité

### Comment accéder aux paramètres

1. Cliquez sur votre **photo de profil** ou **avatar** en haut à droite
2. Sélectionnez **Paramètres**
3. Allez dans l'onglet **Accessibilité**

### Options disponibles

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><h4><i class="fa-keyboard" style="color:$primary;"></i></h4><td><strong>Navigation au clavier</strong></td><td>Activez/désactivez les raccourcis clavier étendus</td></tr><tr><td><h4><i class="fa-low-vision" style="color:$primary;"></i></h4><td><strong>Mode haute visibilité</strong></td><td>Focus et bordures plus visibles</td></tr><tr><td><h4><i class="fa-font" style="color:$primary;"></i></h4><td><strong>Taille du texte</strong></td><td>Ajustez la taille de la police par défaut</td></tr><tr><td><h4><i class="fa-palette" style="color:$primary;"></i></h4><td><strong>Couleurs</strong></td><td>Personnalisez les couleurs de l'interface</td></tr><tr><td><h4><i class="fa-closed-captioning" style="color:$primary;"></i></h4><td><strong>Sous-titres</strong></td><td>Activez toujours les sous-titres</td></tr><tr><td><h4><i class="fa-mouse-pointer" style="color:$primary;"></i></h4><td><strong>Pointer de souris</strong></td><td>Agrandissez le pointeur de la souris</td></tr></tbody></table>

## Bonnes pratiques

### Pour les utilisateurs

1. **Personnalisez** votre expérience selon vos besoins
2. **Testez** les différentes options pour trouver ce qui vous convient le mieux
3. **Signalez** tout problème d'accessibilité à notre équipe
4. **Mettez à jour** régulièrement votre navigateur et vos outils d'assistance
5. **Utilisez** les raccourcis clavier pour une navigation plus rapide

### Pour les créateurs de contenu

Si vous créez du contenu à partager avec d'autres utilisateurs :

1. **Utilisez des titres hiérarchiques** (h1, h2, h3) pour structurer votre contenu
2. **Ajoutez des textes alternatifs** à toutes les images et diagrammes
3. **Décrivez les liens** de manière claire (évitez "Cliquez ici")
4. **Utilisez des contrastes suffisants** entre le texte et l'arrière-plan
5. **Structurez les listes** correctement avec des puces ou des numéros
6. **Évitez** de transmettre des informations uniquement par la couleur

## Conformité et normes

### WCAG 2.1

Notre application respecte les **Web Content Accessibility Guidelines (WCAG) 2.1** au niveau **AA** :

✅ **Percevable** : Toutes les informations sont présentées de manière perceptible
✅ **Utilisable** : Tous les éléments d'interface sont utilisables
✅ **Compréhensible** : Toutes les informations et interfaces sont compréhensibles
✅ **Robuste** : Le contenu est suffisamment robuste pour être interprété par divers outils

### RGAA

Nous suivons également le **Référentiel Général d'Amélioration de l'Accessibilité (RGAA)** version 4.1 pour la conformité française.

### Section 508

Pour les utilisateurs aux États-Unis, notre application respecte la **Section 508** de la Rehabilitation Act.

## Support et feedback

### Signaler un problème d'accessibilité

Si vous rencontrez un problème d'accessibilité :

1. **Décrivez le problème** en détail
2. **Indiquez** :
   - La page ou fonctionnalité concernée
   - Le navigateur ou l'outil d'assistance utilisé
   - Les étapes pour reproduire le problème
3. **Envoyez** votre rapport à : accessibilite@votreentreprise.com

### Nous contacter

Pour toute question sur l'accessibilité :

- **Email** : accessibilite@votreentreprise.com
- **Téléphone** : [Numéro dédié]
- **Formulaire en ligne** : [URL du formulaire]

### Déclaration d'accessibilité

Consultez notre **déclaration d'accessibilité** complète :

[Déclaration d'accessibilité](/accessibilite)

Cette déclaration comprend :
- Notre engagement en matière d'accessibilité
- Les normes que nous suivons
- Les limitations connues
- Nos plans d'amélioration

## Ressources supplémentaires

### Outils d'assistance recommandés

| Outil | Description | Plateforme |
|-------|-------------|-----------|
| **NVDA** | Lecteur d'écran gratuit | Windows |
| **JAWS** | Lecteur d'écran professionnel | Windows |
| **VoiceOver** | Lecteur d'écran intégré | macOS/iOS |
| **TalkBack** | Lecteur d'écran intégré | Android |
| **ZoomText** | Loupe d'écran | Windows |
| **SuperNova** | Loupe et lecteur d'écran | Windows |

### Extensions de navigateur utiles

- **Color Contrast Analyzer** : Vérifiez les ratios de contraste
- **WAVE** : Évalue l'accessibilité des pages web
- **axe DevTools** : Outil de test d'accessibilité intégré au navigateur
- **NoCoffee** : Simulez différents troubles visuels

### Formation à l'accessibilité

- [WCAG Quick Ref](https://www.w3.org/WAI/WCAG21/quickref/)
- [WebAIM](https://webaim.org/)
- [AccessiNum](https://accessinum.github.io/) (ressources en français)

## Résolution des problèmes

<details>
<summary>Le lecteur d'écran ne lit pas correctement l'interface</summary>

- Vérifiez que votre lecteur d'écran est à jour
- Essayez de rafraîchir la page (F5 ou Ctrl+R)
- Vérifiez que JavaScript est activé dans votre navigateur
- Essayez avec un autre navigateur
- Contactez le support technique

</details>

<details>
<summary>Les raccourcis clavier ne fonctionnent pas</summary>

- Vérifiez que vous n'êtes pas dans un champ de saisie
- Essayez de désactiver les raccourcis du navigateur
- Vérifiez que les raccourcis sont activés dans les paramètres
- Essayez les raccourcis de base (Tab, Entrée, Échap)

</details>

<details>
<summary>Le contraste est insuffisant</summary>

- Activez le mode sombre dans les paramètres
- Ajustez les couleurs personnalisées
- Utilisez les raccourcis du navigateur pour zoomer
- Essayez une autre police de caractères

</details>

<details>
<summary>Je ne peux pas naviguer avec le clavier</summary>

- Vérifiez que vous utilisez un navigateur moderne (Chrome, Firefox, Edge, Safari)
- Assurez-vous qu'aucun script ne bloque la navigation
- Essayez de rafraîchir la page
- Contactez le support si le problème persiste

</details>

<details>
<summary>Les sous-titres ne s'affichent pas</summary>

- Vérifiez que les sous-titres sont activés dans les paramètres
- Vérifiez que votre connexion internet est stable
- Essayez de recharger la vidéo
- Contactez le support technique

</details>

## Glossaire de l'accessibilité

| Terme | Définition |
|-------|------------|
| **ARIA** | Accessible Rich Internet Applications - spécifications pour rendre les applications web dynamiques accessibles |
| **Lecteur d'écran** | Logiciel qui lit le contenu de l'écran à voix haute pour les utilisateurs malvoyants |
| **Contraste** | Différence de luminosité ou de couleur entre deux éléments, essentielle pour la lisibilité |
| **Focus** | État actif d'un élément, indiqué visuellement pour la navigation au clavier |
| **Sémantique** | Utilisation correcte des balises HTML pour donner du sens au contenu |
| **WCAG** | Web Content Accessibility Guidelines - normes internationales pour l'accessibilité web |
| **RGAA** | Référentiel Général d'Amélioration de l'Accessibilité - normes françaises d'accessibilité |

## Ressources connexes

{% content-ref url="documents.md" %}
[documents.md](documents.md)
{% endcontent-ref %}

{% content-ref url="models.md" %}
[models.md](models.md)
{% endcontent-ref %}

{% content-ref url="../reference/configuration.md" %}
[configuration.md](../reference/configuration.md)
{% endcontent-ref %}
