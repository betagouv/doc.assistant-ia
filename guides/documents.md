---
description: >-
  Comment l'assistant analyse et utilise vos documents : contexte complet pour
  les petits fichiers, indexation RAG pour les longs documents, et ce que l'IA
  "voit" vraiment.
icon: file
---

# Gestion des documents

L'assistant ne "lit" pas vos documents comme vous. Il les transforme en texte, puis les analyse selon deux modes distincts selon leur taille. Voici ce qui se passe concrètement.

***

## 📄 Documents courts : traitement en contexte complet

**Si votre document fait moins d'une dizaine de pages de texte**, l'assistant l'intègre **entièrement** dans le contexte de la conversation.

Cela signifie qu'il a accès à l'intégralité du contenu simultanément. Il peut alors :

* **Analyser les liens** entre toutes les sections
* **Repérer les contradictions** ou répétitions
* **Extraire des informations** précise sans limite de zone
* **Répondre à des questions** portant sur n'importe quelle partie du document

{% hint style="info" %}
**Exemple** : Un contrat de 8 pages sera entièrement "chargé" dans la mémoire de la conversation. Vous pouvez demander : _"Quels sont les articles concernant les pénalités de retard ?"_ et l'assistant parcourra l'ensemble pour vous répondre.
{% endhint %}

***

## 📚 Documents longs : indexation et recherche RAG

**Au-delà d'une dizaine de pages**, ou dans le cadre d'un **projet**, vos documents sont **découpés en sections** (on parle de _chunks_) et stockés dans une base de recherche spécialisée.

L'assistant dispose alors de **deux outils principaux** pour y accéder :

### 🔍 1. Le résumé

Un résumé automatique du document est généré et stocké. Cela permet à l'assistant de comprendre **la thématique globale** avant même de plonger dans les détails.

### 🎯 2. La recherche RAG (Recherche Augmentée par Génération)

Lorsque vous posez une question, l'assistant :

1. **Interprète votre demande**
2. **Recherche dans la base** les paragraphes les plus proches sémantiquement
3. **Sélectionne les extraits pertinents**
4. **Génère une réponse** basée sur ces extraits

{% hint style="success" %}
**Concrètement** : Si vous demandez _"Quelles sont les spécifications techniques du module X ?"_, l'assistant ne lira pas les 200 pages du manuel. Il identifiera les 3 paragraphes qui parlent de ce module et s'y référera pour répondre.
{% endhint %}

***

## 👁️ Ce que l'assistant "voit" vraiment

**Votre document est converti en texte brut.** L'assistant **ne voit pas** :

* ❌ **La mise en page** (colonnes, encadrés, position des éléments)
* ❌ **Les numéros de page** (les références type _"voir page 4"_ sont inutiles)
* ❌ **Les schémas, images ou graphiques** (sauf si leur légende ou texte alternatif est présent)
* ❌ **Les annotations manuscrites** ou surlignages
* ❌ **Les informations de format** (police, couleur, taille)

**Il voit uniquement** :

* ✅ **Le texte** extrait du document
* ✅ **La structure hiérarchique** (titres, sous-titres, listes, tableaux)
* ✅ **Les mots et leur agencement** dans les phrases et paragraphes

### ⚠️ Conséquence importante

Pour que l'assistant **trouve l'information que vous cherchez**, celle-ci doit être **clairement identifiable par son contenu textuel**.

| ❌ À éviter                           | ✅ À privilégier                                          |
| ------------------------------------ | -------------------------------------------------------- |
| _"Le tableau en haut de la page 12"_ | _"Le tableau comparant les performances trimestrielles"_ |
| _"Le paragraphe sous le schéma"_     | _"Le paragraphe expliquant le processus de validation"_  |
| _"La note en bas de page"_           | _"La note précisant les exceptions à la règle"_          |

**Pourquoi ?** Parce que l'assistant recherche des **mots-clés** et des **concepts**, pas des positions visuelles.

***

## 💡 Bonnes pratiques pour optimiser le traitement

### Pour les documents courts

* **Structurez avec des titres clairs** : L'assistant s'appuie sur la hiérarchie du texte
* **Soyez explicite** dans vos noms de sections

### Pour les documents longs

* **Utilisez des mots-clés précis** dans vos questions : _"Dans le chapitre sur la conformité RGPD, quelles sont les obligations ?"_
* **Évitez les références spatiales** : Préférez le contenu à la position
* **Demandez des résumés ciblés** : _"Résume-moi la section sur les procédures d'urgence"_

### Dans tous les cas

* **Privilégiez les formats texte** (PDF avec texte, DOCX, TXT) aux images ou scans
* **Testez avec une question simple** pour confirmer que le document est bien indexé

***

## ❓ Questions fréquentes

<details>

<summary>Pourquoi l'assistant ne trouve pas une information que je vois dans mon document ?</summary>

* L'information est peut-être dans une **image ou un schéma** sans texte alternatif
* Le document a peut-être été **mal extrait** (PDF scanné, format corrompu)
* Votre question utilise des **références visuelles** ("à droite", "en bas") incompréhensibles pour l'IA
* L'information est dans un **tableau complexe** dont la structure n'a pas été préservée

**Solution** : Reformulez votre question avec des mots-clés du contenu, ou vérifiez le format du document.

</details>

<details>

<summary>Comment savoir si mon document est en full context ou en RAG ?</summary>

* **Full context** : Document de moins de 5 pages, discuté dans une conversation unique
* **RAG** : Document de plus de 5 pages, ou ajouté à une base documentaire/projet

Vous pouvez toujours demander à l'assistant : _"Comment as-tu accès à ce document ?"_

</details>

<details>

<summary>Mon document fait 4 pages mais l'assistant semble ne pas tout voir. Pourquoi ?</summary>

La limite de "environ 5 pages" concerne le **nombre de pages de texte pur**. Si votre document contient beaucoup d'information très denses, la quantité de texte effective peut être supérieure à ce que vous attendez, ce qui réduit le contexte disponible.

</details>
