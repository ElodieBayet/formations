# HyperText Markup Language

## Sommaire 
* [Prérequis](#prerequis)
0. [Ch.0 - Le HTML](#ch0---le-html)
1. [Ch.1 - Sémantique et structure du langage HTML](#ch1---semantique-et-structure-du-langage-HTML)
2. [Ch.2 - Métadonnées de documentL](#ch2---metadonnees-de-document)
3. [Ch.3 - Éléments de section](#ch3---elements-de-section)
4. [Ch.4 - Éléments textuels groupants](#ch4---elements-textuels-groupants)
5. [Ch.5 - Éléments phrasés](#ch5---elements-phrases)
6. [Ch.6 - Principes avancés des liaisons externes](#ch6---principes-avances-des-liaisons-externes)
7. [Ch.7 - Éléments éditatbles](#ch7---elements-editatbles)
8. [Ch.8 - Éléments de contenu embarqué](#ch8---elements-de-contenu-embarque)
9. [Ch.9 - Éléments de tableaux](#ch9---elements-de-tableaux)
10. [Ch.10 - Éléments de formulaires](#ch10---elements-de-formulaires)
11. [Ch.11 - Éléments interactifs](#ch11---elements-interactifs)
12. [Ch.12 - Éléments relatifs aux scripts](#ch12---elements-relatifs-aux-scripts)
13. [Ch.13 - Éléments personnalisés](#ch13---elements-personnalises)
14. [Ch.14 - Connaissance complémentaire](#ch14---connaissance-complementaire)

## Prérequis 
- [Fondamentaux Informatiques](/fondamentaux-informatiques.md)

---

## Ch.0 - **Le HTML**

### 0.0 :: Description
- Historique : Tim Berners-Lee et le World Wide Web
- Standardisation
- Utilisation
- Évolution technologique

---

## Ch.1 - **Sémantique et structure du langage HTML**

Présentation du mécanisme du langage HTML

### 1.0 :: Anatomie d'une balise
- Ouverture et fermeture
- Dite 'Autonome'
- Attributs

### 1.1 :: Le document
- Racine : `<html>`
- Section d'en-tête : `<head>`
- Section de contenu : `<body>`

### 1.2 :: Les Éléments
- Commentaire
- Métadonnes _Metadata_
- Flux _flow_
- Section _sectionning_
- Titres _heading_
- Textuel _phrasing_
- Contenu embarqué _embedding_
- Contenu interactif _interactive_
- Contenu manipulable _palpable_
- Contenu pour script _script_

### 1.3 Attributs
- Universels
- Spécifiques

## 1.4 :: Comportement
- Modèle de boîte
- Comportement block _block_
- Comportement en ligne _inilne_

---

## Ch.2 - **Métadonnées de document**
    
### 2.0 :: Balise de titre de docmuent `<title>`
- Fonctionnement
- Utilisation
- Attributs
    
### 2.1 :: Balise de référence d'URL `<base>`
- Fonctionnement
- Utilisation
- Attributs
    
### 2.2 :: Balise de liaisons de ressources `<link>`
- Fonctionnement
- Utilisation
- Attributs : `media`, `type`, `rel`, `href`, etc.
    
### 2.3 :: Balise de métadonnées `<meta>`
- Fonctionnement
- Utilisation
- Libelés standards : `name` et `content`
- Libelés autres
- Directives : `http-equiv`
- Encodage : `charset`
    
### 2.4 :: Balise de styles CSS `<style>`
- Fonctionnement
- Utilisation
    
---

## Ch.3 - **Éléments de section**

### 3.0 :: Balise de page `<main>`
- Fonctionnement
- Utilisation

### 3.1 :: Balises d'en-tête `<header>` et de pied `<footer>`
- Fonctionnement
- Utilisation

### 3.2 :: Balises `<section>` et `<article>`
- Fonctionnement
- Utilisation

### 3.3 :: Balise de navgation `<nav>`
- Fonctionnement
- Utilisation

### 3.4 :: Balise de contenu d'aparté `<aside>`
- Fonctionnement
- Utilisation

### 3.5 :: Balise `<address>`
- Fonctionnement
- Utilisation

### 3.6 :: Compléments d'utilisation
- Article et section
- Titres et les sections

---

## Ch.4 - **Éléments textuels groupants**

### 4.0 :: Balise neutre `<div>`
- Fonctionnement
- Utilisations

### 4.1 :: Balise de citation `<blockquote>`
- Fonctionnement
- Utilisations

### 4.2 :: Balise de paragraphe `<p>`
- Fonctionnement
- Utilisations

### 4.3 :: Balise de préformatage `<pre>`
- Fonctionnement
- Utilisations

### 4.4 :: Balise de liste `<ol>`, `<ul>`, `<li>`
- Fonctionnement
- Utilisations

### 4.5 :: Balises de description listées `<dl>`, `<dt>` et `<dd>`
- Fonctionnement
- Utilisations
    
### 4.6 :: Balises figuratives `<figure>` et `<figcaption>`
- Fonctionnement
- Utilisations

### 4.7 :: Balise `<menu>`
- Fonctionnement
- Utilisations

### 4.8 :: Balise `<hr>`
- Fonctionnement
- Utilisations

---

## Ch.5 - **Éléments phrasés**

### 5.0 :: Balise de conteneur `<span>`
- Fonctionnement
- Utilisations

### 5.1 :: Balise d'ancre `<a>`
- Fonctionnement
- Utilisations

### 5.2 :: Balise d'emphase `<em>`
- Fonctionnement
- Utilisations
    
### 5.3 :: Balises de mise en évidence significative et non-significative `<strong>` et `<b>`
- Distinctions importantes
- Fonctionnement
- Utilisations

### 5.4 :: Balises typographiques d'indice et d'exposant `<sub>` et `<sup>`
- Fonctionnement
- Utilisations

### 5.5 :: Balise typographique de texte barré `<s>`
- Fonctionnement
- Utilisations

### 5.6 :: Balises de définition de temps `<time>`
- Fonctionnement
- Utilisations
    
### 5.7 :: Balise de commentaires `<small>`
- Fonctionnement
- Utilisations

### 5.8 :: Balise d'évidence non-significative `<i>`
- Fonctionnement
- Utilisations

### 5.9 :: Balises avec annotation non-textuelle `<u>`
- Fonctionnement
- Utilisations

### 5.10 :: Balise de démarquation de pertinence `<mark>`
- Fonctionnement
- Utilisations

### 5.11 :: Balise de référence citative `<cite>`
- Fonctionnement
- Utilisations

### 5.12 :: Balise de citation courte `<q>`
- Fonctionnement
- Utilisations

### 5.13 :: Balise d'abréviation `<abbr>`
- Fonctionnement
- Utilisations

### 5.14 :: Balise de définition `<dfn>`
- Fonctionnement
- Utilisations

### 5.15 :: Balise de césure `<wbr>`
- Fonctionnement
- Utilisations

### 5.16 :: Balise de retour chariot `<br>`
- Fonctionnement
- Utilisations

### 5.17 :: Balise d'association de contenu orienté-machine `<data>`
- Fonctionnement
- Utilisations

### 5.18 :: Balise de code machine `<code>` et de résultat `<samp>`
- Fonctionnement
- Utilisations

### 5.19 :: Balise de représentation d'expression mathématique `<var>`
- Fonctionnement
- Utilisations

### 5.20 :: Balise de représentation clavier `<kbd>`
- Fonctionnement
- Utilisations

### 5.21 :: Balises de texte bidirectionnel outrepassé `<bdo>` et isolé `<bdi>`
- Distinctions importantes
- Fonctionnement
- Utilisations

### 5.22 :: Balises d'annotation d'Asie orientale `<ruby>`, `<rt>` et `<rt>`
- Fonctionnement
- Utilisations

### 5.23 :: Compléments d'utilisation sémantique

---

## Ch.6 - **Principes avancés des liaisons externes**

Mécanisme de connexion entre deux ressources.

### 6.0 :: Principes de fonctionnement
- Liaisons vers des ressources externes
- Hyperliens : _following_, _downloading_, _auditing_
- Liaisons propres aux éléments `<a>` et `<area>`

### 6.1 :: Les types de liaisons
- Le type `alternate`
- Le type `author`
- Le type `bookmark`
- Le type `canonical`
- Le type `dns-prefetch`
- Le type `external`
- Le type `help`
- Le type `icon`
- Le type `license`
- Le type `manifest`
- Le type `modulepreload`
- Le type `nofollow`
- Le type `noopener`
- Le type `noreferrer`
- Le type `opener`
- Le type `pingback`
- Le type `preconnect`
- Le type `prefetch`
- Le type `preload`
- Le type `prerender`
- Le type `search`
- Le type `stylesheet`
- Le type `tag`
- Les types séquentiels `next` et `prev`

---

## Ch.7 - **Éléments éditatbles**

### 7.0 :: Balises d'insertion `<ins>` et de suppression `<del>`
- Fonctionement
- Utilisation
- Attributs

### 7.1 :: Complément d'utilisation
- Édition de paragraphes
- Édition de listes
- Édition de tableaux

---

## Ch.8 - **Éléments de contenu embarqué**

### 8.0 :: Principes génériques
- Description
- Images
- Multimédia
- Autres contenus
- Attributs de dimensions

### 8.1 :: Balise image `<img>`
- Fonctionnement
- Utilisation
- Attributs

### 8.2 :: Balise de sources distinctes `<source>`
- Fonctionnement
- Utilisation
- Attributs

### 8.3 :: Balise de contenu imagé `<picture>`
- Fonctionnement
- Utilisation
- Attributs

### 8.4 :: Principes de fonctionnement liés aux images statiques
- Compréhension d'image adaptatives
- Comportements liés à `srcset` et `sizes`
- Modèle de fonctionnement

### 8.5 :: Balise de pistes intégrées `<track>`
- Fonctionnement
- Utilisation
- Attributs

### 8.6 :: Balise de contenu audio `<audio>`
- Fonctionnement
- Utilisation
- Attributs

### 8.7 :: Balise de contenu vido `<video>`
- Fonctionnement
- Utilisation
- Attributs

### 8.8 :: Principes de fonctionnement liés au multimédia
- Erreurs
- Origine de la ressources
- Types MIME
- Chargement et états
- Contrôle de lecture
- Bonnes pratiques liées à la conception et l'implémentation

### 8.9 :: Balise d'imbrication de page HTML externe `<iframe>`
- Fonctionnement
- Utilisation
- Attributs

### 8.10 :: Balises de contenu plug-in `<object>` et `<param>`
- Fonctionnement
- Utilisation
- Attributs

### 8.11 :: Balise de contenu applicatif `<embed>`
- Fonctionnement
- Utilisation
- Attributs

### 8.12 :: Balises zones cliquables `<map>` et `<area>`
- Fonctionnement
- Utilisation
- Attributs

### 8.13 :: Balise de langage mathématique balisé `<math>`
- Fonctionnement
- Utilisation
- Attributs

### 8.14 :: Balise de contenu visuel vectoriel `<svg>`

---

## Ch.9 - **Éléments de tableaux**
	
### 9.0 :: Construction basique `<table>`, `<th>`, `<td>` et `<tr>`
- Fonctionement
- Utilisation

### 9.1 :: Subdivisions `<thead>`, `<tbody>` et `<tfoot>`
- Fonctionement
- Utilisation

### 9.2 :: Balises complémentaires `<caption>`, `<colgroup>` et `<col>`
- Fonctionement
- Utilisation

### 9.3 :: Attributs communs
- Fonctionement
- Utilisation

### 9.4 :: Complément d'utlisation
- Raisonnement _données tabulaires_

---

## Ch.10 - **Éléments de Formulaires**

### 10.0 :: Principe de fonctionnement
- Description
- Association de données
- Configuration pour la réception côté serveur
- Optimisation mobile first

### 10.1 :: Balises formulaire `<form>`
- Principes liés à la soumission
- Construction
- Attributs

### 10.2 :: Balise de labélisation de champ `<label>`
- Fonctionnement
- Utilisation
- Attributs

### 10.3 :: Balise de champ d'insertion `<input>`
- Le type caché `hidden`
- Le type texte `text` et le type recherche `search`
- Le type téléphone `tel`
- Le type URL `url`
- Le type e-mail `email`
- Le type mot-de-passe `password`
- Le type date `date`
- Le type mois `month`
- Le type semaine `week`
- Le type time `time`
- Le type date et temps local `local`
- Le type nombre `number`
- Le type plage `range`
- Le type couleur `color`
- Le type case-à-cochée multiple `checkbox`
- Le type case-à-cochée unique `radio`
- Le type chargement de fichier `file`
- Le type button `button`
- Le type bouton d'envoi `submit`
- Le type bouton image `image`
- Le type bouton de réinitialisation `reset`

### 10.4 :: Attributs communs à l'élément `<input>`
- Les attributs `maxlength` et `minlength`
- L'attribut `size`
- L'attribut `readonly`
- L'attribut `required`
- L'attribut `multiple`
- L'attribut `pattern`
- Les attributs `min` et `max`
- L'attribut `step`
- L'attribut `list`
- L'attribut `placeholder`

### 10.5 :: Balise de liste déroulante `<select>`, `<option>` et `<optgroup>`
- Fonctionnement
- Utilisation
- Attributs

### 10.6 :: Balise de liste suggestive `<datalist>`
- Fonctionnement
- Utilisation
- Attributs

### 10.7 :: Balise de texte multilignes `<textarea>`
- Fonctionnement
- Utilisation
- Attributs

### 10.8 :: Balise de résultat `<output>`
- Fonctionnement
- Utilisation
- Attributs

### 10.9 :: Balise de progession de complétion `<progress>`
- Fonctionnement
- Utilisation
- Attributs

### 10.10 :: Balise de valeur scalaire ou fractionaire `<meter>`
- Fonctionnement
- Utilisation
- Attributs

### 10.11 :: Balise bouton `<button>`
- Fonctionnement
- Utilisation
- Attributs

### 10.12 :: Sections de formulaire `<fieldset>` et `<legend>`
- Fonctionnement
- Utilisation
- Attributs

### 10.13 :: Contrôle et validation de formulaire
- Infrastructure
- Autocomplétion
- Définition de contraintes de validation
- Attributs spécifiques à la validation

### 10.14 :: Complément d'utlisation

---

## Ch.11 - **Éléments interactifs**

### 11.0 :: Balise `<details>`

### 11.0 :: Balise `<summary>`
    
### 11.0 :: Balise `<dialog>`

### 11.3 :: Balise de commandes personnalisées `<menu>` /!\
- Fonctionnalité expérimentale
- Définition de commandes par éléments : `<a>`, `<button>`, `<input>` et `<option>`
- Utilisation des touche d'accès `accesskey` sur des éléments

---

## Ch.12 - **Éléments relatifs aux scripts**

### 12.0 :: Balise JavaScript `<script>`
- Principe de fonctionnement
- Utilisations
- Attributs

### 12.1 :: Balise d'affichage sans script `<noscript>`
- Fonctionnement
- Utilisation

### 12.2 :: Balise de modèle de contenu `<template>`
- Fonctionnement
- Utilisation

### 12.1 :: Balise de composant presonalisé `<slot>`
- Fonctionnement
- Utilisation

### 12.1 :: Balise de rendu graphique `<canvas>`
- Utilisations
- Attributs
- Contexte de rendu en 2D
- Contexte de rendu d'image _bitmap_
- Inreface `OffscreenCanvas`
- Espace de rendu des couleurs

---

## Ch.13 - **Éléments personnalisés**

Construction personnelle d'éléments HTML (cf. Angular, Vue.js, etc)

### 13.0 :: Principe de fonctionnement

### 13.1 :: Exploitation
- Création d'éléments personnalisés
- Création d'éléments orienté-formulaire
- Cération d'éléments avec roles, états et propriétés par défaut
- Construction d'éléments natifs

---

## Ch.14 - **Connaissance complémentaire**

### 14.0 - Éléments obsolètes ou dépréciés
`<acronym>` – `<applet>` – `<basefont>` – `<bgsound>` – `<big>` – `<blink>` – `<center>` – `<content>` – `<dir>` – `<font>` – `<frame>` – `<hgroup>` – `<image>` –
`<keygen>` – `<marquee>` – `<menuitem>` – `<nobr>` – `<noembed>` – `<noframes>` – `<plaintext>` – `<rb>` – `<rtc>` – `<shadow>` – `<spacer>` – `<strike>` – `<tt>` – `<xmp>s`

### 14.1 - Éléments désactivés
- `disabled`et `enabled`

### 14.2 - Constructions usuelles sans éléments dédiés
- Le fil d'arianne
- Le nuage de mot-clés
- Le fil de conversation
- Les notes de pied de pages

### 14.3 - Architecture de pages
- Arborescence
- Bonnes pratiques structurelles