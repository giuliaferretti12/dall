---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /background.svg
# some information about your slides (markdown enabled)
title: "Revue3.0 : Écrire, Transmettre,"
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev
themeConfig:
  primary: '#000000'
fonts:
  sans: 'Robot'
  serif: 'Robot Slab'
  mono: 'Fira Code'
---

# Revue3.0 : Écrire, Transmettre, Découvrir

Un Partenariat dirigé par Marcello Vitali-Rosati et subventionné par le Conseil de recherches en sciences humaines.

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  La gestion d'un partenariat de recherche <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/giuliaferretti12/dall" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

Université de Sherbrooke | 9 avril 2025

<!--

-->

---

# Qu'est-ce qu'un projet de partenariat ?

Quelques données

- 2.5 millions au maximum
- Entre 4 et 7 ans
- Recherche au delà des institutions post-secondaires
- Coproductions connaissances
- Accessibilité de la recherche et mobilisation des connaissances
- Concours à deux étapes
- Avant du concurs : appui d'un établissement

<div style="position: relative; width: 100%; height: 100vh;">
    <img src="/crsh-logo.jpeg" style="position: absolute; width: 40%; height: auto; left: 55%; top: 0%;" />
</div>

---
layout: center
---

# Notre partenariat

<div style="position: relative; padding: 2rem;">
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: blue; opacity: 0.2; border-radius: 1rem; z-index: 0;"></div>
  <p>Repenser les formes de production, de diffusion et de légitimation de la connaissance en sciences humaines afin que les revues savantes puissent rester les protagonistes des savoirs de demain.</p>
  </div>
  <br>
  <div style="position: relative; padding: 2rem;">
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: blue; opacity: 0.2; border-radius: 1rem; z-index: 0;"></div>
  <p>Imaginer et guider le futur des revues savantes.</p>
  </div>

---
layout: image-right
image: /equipe.png
---

# Quelques données

- 25 co-chercheur.e.s
- 22 partenaires
- Coordination basée à l'Université de Montréal

---
layout: image
image: partenaires-infra.png
---

---
layout: image
image: partenaires-revues.png
---

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<!--
Here is another comment.
-->
---
layout: center
---

# Tout a commencé avec...

Espace numérique = écriture

[https://www.ecrituresnumeriques.ca/fr](https://www.ecrituresnumeriques.ca/fr)

---
layout: cover
background: chaire.png
---



---
layout: cover
background: https://www.revue20.org/images/entete-p.jpg
---

# Revue2.0

## Développement de partenariat

2018-2021

[https://www.revue20.org/](https://www.revue20.org/)

---
layout: image-right
image: https://www.revue20.org/images/entete-p.jpg
---

# Revue2.0 

## Les objectifs

- Produire un modèle épistémologique pour les revues à l'époque du numérique

- Proposer un nouveau modèle éditorial pour les revues savantes en sciences humaines

<!--
**produire un modèle épistémologique pour les revues à l'époque du numérique**: retracer la mission historique des revues (voir comment celle-ci peut être remplie ou définie à l'époque du numérique) 
- e.g. changement du terme publication 
- problème de l'integration des revues dans un écosystème en évolution
- tâches pour rejoindre les **communautés savantes** sur le web

**proposer un nouveau modèle éditorial pour les revues savantes en sciences humaine**: 
- cahier de charges pour les acteurs de l'édition savante (pour assurer la pérennité et la visibilité des revues sur le web) => création d'outils et de protocoles mieux adaptés aux besoins des chercheurs et éditeurs
-->

---
layout: image-right
image: https://www.revue20.org/images/entete-p.jpg
---

# Les partenaires

- Érudit
- Open Editions
- Huma-Num
- Revue CyberGéo
- Revue Études Françaises
- Revue Intermédialités
- Revue Itinéraires
- Revue Mémoires du livre
- Revue Internationale de photolittérature

---
layout: image-right
image: calendrier.png
---

# Articulation du projet

Enjeu conversationnel : revue en tant que espace/outil pour mettre en place des conversations tout au long de la chaîne éditoriale

1. **Production des contenus** : technologies numériques - production de contenus - propositions de bonnes pratiques

2. **Validation des contenus** : technologies numériques - acceptation, citation, dialogue avec l'auteur

3. **Diffusion des contenus** : technologies numériques - accessibilité et visibilité des contenus scientifiques



<!--Powered by [shiki-magic-move](https://shiki-magic-move.netlify.app/), Slidev supports animations across multiple code snippets.

Add multiple code blocks and wrap them with <code>````md magic-move</code> (four backticks) to enable the magic move. For example:

````md magic-move {lines: true}
```ts {*|2|*}
// step 1
const author = reactive({
  name: 'John Doe',
  books: [
    'Vue 2 - Advanced Guide',
    'Vue 3 - Basic Guide',
    'Vue 4 - The Mystery'
  ]
})
```

```ts {*|1-2|3-4|3-4,8}
// step 2
export default {
  data() {
    return {
      author: {
        name: 'John Doe',
        books: [
          'Vue 2 - Advanced Guide',
          'Vue 3 - Basic Guide',
          'Vue 4 - The Mystery'
        ]
      }
    }
  }
}
```

```ts
// step 3
export default {
  data: () => ({
    author: {
      name: 'John Doe',
      books: [
        'Vue 2 - Advanced Guide',
        'Vue 3 - Basic Guide',
        'Vue 4 - The Mystery'
      ]
    }
  })
}
```

Non-code blocks are ignored.

```vue
<!-- step 4 --
<script setup>
const author = {
  name: 'John Doe',
  books: [
    'Vue 2 - Advanced Guide',
    'Vue 3 - Basic Guide',
    'Vue 4 - The Mystery'
  ]
}
</script>
```
````
-->

---
layout: image-right
image: https://www.revue20.org/images/entete-p.jpg
---

# L'équipe de coordination

- Marcello-Vitali Rosati
- Nicolas Sauret
- Margot Mellet
- Antoine Fauchié

<!--
Marcello (et Enrico, etc.) : l'espace centrale dans la théorie de l'éditorialisation

Nicolas comme coordinateur du projet
- concept du protocol
- attention à la communauté

rileggi intro tesi per capirci meglio-->

---

# Théorie de l'éditorialisation

> L’éditorialisation est l’ensemble des dynamiques qui constituent l’espace numérique et qui permettent, à partir de cette constitution, l’émergence du sens. Ces dynamiques sont le résultat de forces et d’actions différentes qui déterminent après coup l’apparition et l’identification d’objets particuliers (personnes, communautés, algorithmes, plateformes…). 

Source : Pour une théorie de l’éditorialisation (Vitali-Rosati 2020)

<!--Tout objet, individu, collectivité n'existe que parce qu'il est modélisé, présenté et structuré dans l'espace numérique.

Toujours liées à des environnements techniques spécifiques (l'environnement numérique est prescriptif)

En ce sens, l’éditorialisation peut être pensée comme l’ensemble des conditions matérielles de médiation qui déterminent l’émergence d’un monde.-->
<div style="position: fixed; bottom: 10vh; left: 80%; transform: translateX(-50%); display: flex; gap: 3rem;">
<img src="/marcello.jpg" style="width: 250px; height: auto; border-radius: 12px;" />
</div>

---

# Communautés, pratiques, protocoles

- Protocoles éditoriales en tant que pratiques négociées et adoptées systématiquement par des communautés/collectifs spécifiques

- Protocoles reconfigurent les relations numériques.

Source : [https://these.nicolassauret.net/](https://these.nicolassauret.net/)

<div style="position: fixed; bottom: 15vh; left: 70%; transform: translateX(-50%); display: flex; gap: 3rem;">
<img src="/nicolas.jpg" style="width: 250px; height: auto; border-radius: 12px;" />
</div>

---
layout: iframe-right
url: https://www.revue20.org/le-projet/experimentations/
---

# Livrables 
Prototypes, expérimentations et ateliers qui se poursuivent dans le cadre de Revue3.0

- Stylo (éditeur de texte sémantique)
  - Évaluation ouverte avec Hypothesis
  - Indexation par mots clés contrôlés
  - Chaînes de publications
- Analyse de gros corpus de revues
- Atelier de réflexion et travail autour du langage IEML

[https://www.revue20.org/le-projet/experimentations/](https://www.revue20.org/le-projet/experimentations/)

---

# Dispositifs de gestion

- 📍 Coordination montréalaise
- 🌐 Site internet comme vitrine-dispositif assurant la cohérence de la recherche
- 💬 Mattermost pour une communication plus fluide

<div style="position: fixed; bottom: 18vh; left: 38%; transform: translateX(-50%); display: flex; gap: 3rem;">
  <img src="/montreal.jpg" style="width: 250px; height: auto; border-radius: 12px;" />
  <img src="/revue20.png" style="width: 250px; height: auto; border-radius: 12px;" />
  <img src="/mattermost.png" style="width: 250px; height: auto; border-radius: 12px;" />
</div>

<!--
Gouvernance souple : la coordination assure à la fois le suivi direct et la gestion opérationnelle du projet.

Relations directes : la direction sollicite directement les partenaires et co-chercheur.e.s, ce qui favorise la fluidité des échanges.

Limites : cette souplesse peut toutefois poser des problèmes en cas de conflits, notamment en l’absence d’un système clair de légitimation ou de protection des décisions. La coordination générale doit ainsi justifier chaque décision prise, sans cadre formel qui en garantisse la validité.

Enjeux de **communication** : cruciaux pour le bon fonctionnement du projet (cf. les difficultés rencontrées avec CyberGéo).
-->

---
layout: iframe-right
url: https://revue30.org/
class: custom-iframe-content
---

# Vers Revue3.0

## Du prototype à la mise en œuvre à grande échelle

<!--ambition-->
- Multiplications des projets
- Pluralité des savoirs <!--questionnement des critères de scientificité d'une revue, à niveau de formats, contenus (cfr. recherche-création)-->
- Pluralité de formes de production, diffusion et légitimation de la connaissance
- Pour que les revues savantes puissent rester les protagonistes des savoirs de demain

---
layout: image-right
image: /background.svg
---

## Donc...

- La temporalité du projet s’étend au-delà de sa durée officielle
- Ramification et multiplication des projets
- Multiplication du nombre des partenaires et de co-chercheur.euse.s
- Une évolution constante de la composition de l'équipes, à tous les niveaux du projet

---
layout: two-cols
---

<div style="position: relative; padding: 2rem;">
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: gray; opacity: 0.2; border-radius: 1rem; z-index: 0;"></div>
  <h1>Revue2.0</h1>
  <b>Production des contenus</b>
  <p><small>Quels sont les outils
d'écriture utilisés ? Comment ils façonnent-ils la pensée et l'argumentation
scientifique ?</small></p>
  <b>Validation des contenus</b>
  <p><small>Comment le processus de validation de connaissance est-il affecté – au plan épistémologique et institutionnel – par les technologies numériques ?</small></p>
  <b>Diffusion des contenus</b>
  <p><small>Comment les publications en ligne sont-elles rendues accessibles ? Comment leur confère-t-on de la visibilité ? Quels
publics lisent ces contenus ?</small></p>
  </div>

::right:: 

<div style="position: relative; padding: 2rem;">
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: orange; opacity: 0.2; border-radius: 1rem; z-index: 0;"></div>

  <div style="position: relative; z-index: 1;">
    <h1>Revue3.0</h1>
    <b>Écrire</b>
    <p><small>Comment les formes matérielles d'écriture affectent-elle la pensée et la recherche ?</small></p>
    <b>Transmettre</b>
    <p><small>Comment les modes de circulation et de légitimation des contenus savants conditionnent-ils la pensée et la recherche ?</small></p>
    <b>Découvrir</b>
    <p><small>Comment les formes concrètes de lecture et d'appropriation des publications scientifique affectent-elles la pensée et la recherche ?</small></p>
  </div>
</div>

<!--
Écrire : 
Reprendre la main sur l'écrit ; repenser nos pratiques ; protocoles d'écriture et légitimité (IA?) ; le collectif

Transmettre : 
Circulation ; enrichissement sémantique ; transformation/traduction (incommensurabilité ?) ; web sémantique ; IEML

Découvrir : Découvrabilité (performativité du texte découvrable -- qui se présente même à qui ne le cherchait pas, néologisme propre du numérique) ; pratiques de révision ; pratiques d'annotation bibliographique ; la modélisation des actions/stratégies adoptées pour favoriser la découvrabilité des contenus.

De manière générale : De manière générale, on passe des enquêtes de terrain et prototypes (Revue2.0) aux grandes questions assumant le positionnement matérialiste de manière plus claire et radicale (Reve3.0).
-->
---
layout: center
---

# Vers le financement

Ce n’était pas un parcours sans détours...

---

# Le temps de « l' attente »

- Chaînes d'éditions, Single Source Publishing → Fabrique
- Modèles et des savoir → Enjeux d'équité, diversité, inclusion, décolonisation (EDID)
- LLMs, "IA" comme modélisation de l'intelligence
- Production de subalternes
- Pratiques de révision, remédiation
- Approches du nouveau matérialisme

<div style="position: fixed; top: 60%; left: 0; width: 80vw; height: auto; z-index: 9999;">
  <img src="/historique-demandes.png" style="width: 100%; height: 100%; object-fit: cover;" />
</div>

---

# L'évolution du projet face aux critiques du CRSH

## Question de rhétorique ?

Caractère aléatoire de l'attribution des financements.


<div style="position: relative; padding: 0.5rem;">
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: blue; opacity: 0.2; border-radius: 1rem; z-index: 0;"></div>
  
  <div style="position: relative; z-index: 1; font-size: 1.1rem; line-height: 1.6;">
    <p><strong>« La production d'outils, ce n'est pas de la recherche »</strong></p>
    <p>Mais alors, qu’est-ce qu’une infrastructure de recherche ?</p>
    <ul>
      <li>Pour le CRSH : conditions préalables à la recherche</li>
      <li>Pour Revue3.0 : le savoir émerge de dispositifs matériels déterminés</li>
    </ul>
    <p><strong>« Les solutions techniques proposées ne sont pas innovantes »</strong></p>
    <p>Le nôtre est un projet de recherche :</p>
    <ul>
      <li>Notre objet d’étude : les formes de modélisation du monde dans les environnements numériques</li>
      <li>Les grands modèles de langage (LLM) sont des formes spécifiques de modélisation de l’intelligence</li>
    </ul>
  </div>
</div>

---

# L'évolution du projet face aux critiques du CRSH

## Une question de fonds ?

Améliorations du projets suite aux retours de évaluateur·ice·s 

<div style="position: relative; padding: 0.5rem;">
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: orange; opacity: 0.2; border-radius: 1rem; z-index: 0;"></div>

  <div style="position: relative; z-index: 1; font-size: 1.1rem; line-height: 1.6;">
    <p><strong>« Votre engagement EDID n'est pas pris au sérieux »</strong></p>
    <ul>
      <li>Notre projet s'engage dans une remise en question des critères traditionnels de scientificité.</li>
      <li>Nous valorisons la pluralité des formes et des formats de production de savoir.</li>
    </ul>
    <p><strong>« Votre méthodologie n'est pas précise, votre cadre théorique n'est pas assez développé »</strong></p>
    <ul>
      <li>Un dialogue constant entre éditorialisation et nouveau matérialisme.</li>
      <li>Clarification de notre positionnement épistémologique : expliciter le lien entre pratique et recherche, expérimentation et théorie.</li>
    </ul>
  </div>
</div>


---
layout: center
---

# Une fois le financement obtenu... faire le projet

---
layout: image-right
image: /background-3.svg
---

## Des axes aux projets

Faciliter les **fonctionnements** spécifiques des équipes de travail

Valoriser la **diversité** des contributions, intérêts, expertises

Valoriser la diversité de **modèles épistémologiques** des revues partenaires

> <small>Dans le cadre de l’édition scientifique, chaque outil, chaque plateforme, chaque protocole ou pratique véhiculent une vision du monde particulière. Il est essentiel de reconnaître et valoriser cette spécificité, que ce soit dans les compositions des équipes, les méthodes de travail, les systèmes de communication et d'archivage, etc.</small>

---
layout: iframe-right
url: https://baserow.ecrituresnumeriques.ca/form/jsFu69p4JYhZtzcJisO4nAVja2OgLwRkdqxM32a7_v0
---

# Projets formels : non plus des prototypes

<small>Face à cette multiplication, les prototypes ont laissé place à des projets, _définis formellement_ selon les critères suivants :</small>

- <small>Au moins un partenaire externe et deux co-chercheurs</small>
- <small>Au moins un axe de recherche spécifique</small>
- <small>Chaque projet doit produire au minimum :</small>
  - <small>Un livrable technique</small>
  - <small>Deux livrables d'ordre théorique</small>
- <small> Un **formulaire** pour proposer des nouveaux projets</small> →


Mais, **Dans la pratique...**

---

| **Axe 1 Écrire** | **Axe 2 Transmettre** | **Axe 3 Découvrir** | **Transversaux** |
|--------------|-------------------|-----------------|----------|
| Suggestion automatique de références bibliographiques | Expérimentations avec IEML dans Stylo/ Isidore | Protocoles annotations Sens Public |  Refonte métadonnées Stylo |
| Référentiel des flux éditoriaux | Création automatique d'un contexte sémantique dans les articles Stylo | Modélisation du site | Export Stylo (sites revues) |
| Pink my Stylo | | Révision bibliographique avec IA | Export Imaginations |
| Expérimentations avec Cosma | | | Modélisation du site Revue3.0 |

<!--
À partir des projets pilotes menés dans le cadre de Revue3.0

- Édition avec Stylo
- Indexation de mots clés
- évaluation ouverte (cfr. Thèse de Nicolas)

1. Tous les projets ne s’inscrivent pas naturellement dans un axe de recherche.
2. Il ne s’agit pas d’un simple problème d’alignement entre projets et axes,
mais plutôt d’un décalage entre les intérêts de recherche des responsables d’axes et la nature même de certains projets.
3. Cela concerne en particulier les projets issus de Revue2.0, notamment ceux autour de l’outil Stylo.
-->
---
layout: center
---

# Au-delà des livrables : Groupes de travail

Modification survenue progressivement, à partir des rencontres avec les membres du partenariat.

<div style="position: relative; padding: 2rem;">
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: blue; opacity: 0.2; border-radius: 1rem; z-index: 0;"></div>
<div v-click>
  <h2>À la suite de la <a href="https://revue30.org/documents/compte-rendu-premieree-assemblee-pleiniere/" target="_blank">première réunion plénière du partenariat</a></h2>
  <p>🤖 Atelier « Recherche, édition et IA »</p>
</div>

<br>

<div v-click>
  <h2>En réaction à la <a href="https://revue30.org/documents/rencontre-large-revues/" target="_blank">rencontre large des revues</a></h2>
  <p>🌎 Groupe de travail sur les enjeux de décolonisation du savoir</p>
  <p>✍️ Groupe de travail sur la visibilité des évaluateur·ice·s</p>
  <p>🎨 Groupe de travail sur les formes et formats de la recherche</p>
</div>
</div>

<!--Dopo il lancio del partenariato : è emersa la preoccupazione dei membri nei confronti dell'impatto di metodi computazionali per la produzione di conoscenze. 

Durante l'incontro delle riviste, ci siamo trovati di fronte a 3 esigenze fondamentali delle riviste
1. la difficoltà di "accettare" delle proposte scientifiche di persone provenienti dal Sud del mondo/di dottorandi/o da milieux non accademici (come nel caso degli ingegneri di ricerca in Francia)  => rimettere piuttosto in questione i nostri termini di scientificità => glossario per osservare in che modo certi termini (come quello di pubblicazione, sapere, etc.) sono definiti all'interno del sud del mondo => obiettivo di includere nella riflessione delle riviste che provengono dal Sud Globale

2. la difficoltà di trovare "évaluateurs" per le riviste in scienze umane: si tratta di un tipo di compito poco valorizzato nel milieux de la recherche : 
riflessioni sul ruolo che tali valutatori apportano alla conoscenza.
=> stato dell'arte sulle riflessioni sul tema
=> una serie di conversazioni con gli evaluateurs
=> una serie di atelier con le riviste per parlare della questione
=> un sito/documento che raccoglie qualche cosiglio/bonnes pratiques et le risorse bibliografiche

3. la difficoltà di trovare finanziamenti per delle riviste che adottano forme di pubblicazioni che non rispecchiano i criteri di scientificità del CRSH (come nel caso di MuseMedusa) => progetto per dopo
-->

---
layout: section
---

# Maintenir la cohérence face à la multiplication

## Centralisation ?

---
layout: two-cols
---

# Enjeux

<div style="position: relative; padding: 2rem;">
<ol>
  <li><span style="background-color: #A6C8FF; padding: 0.2em; border-radius: 5px;">Visibilité, valorisation, découvrabilité</span></li> <!-- blu pastello pallido -->
  <li><span style="background-color: #F9E59F; padding: 0.2em; border-radius: 5px;">Cohérence de la recherche</span></li> <!-- giallo pastello pallido -->
  <li><span style="background-color: #F7A7A7; padding: 0.2em; border-radius: 5px;">Documentation et archivage</span></li> <!-- rosso pastello pallido -->
  <li><span style="background-color: #A6E1A1; padding: 0.2em; border-radius: 5px;">Information des membres</span></li> <!-- verde pastello pallido -->
  <li><span style="background-color: #A1D8D8; padding: 0.2em; border-radius: 5px;">Espaces de discussion</span></li> <!-- verde acqua pastello pallido -->
  <li><span style="background-color: #D3A9F7; padding: 0.2em; border-radius: 5px;">Connaissance des activités et intérêts de recherche des autres membres</span></li> <!-- viola pastello pallido -->
</ol>
</div>

::right::

# Dispositifs

<div style="position: relative; padding: 2rem;">
<ul>
  <li>Site du projet : <span style="background-color: #A6C8FF; padding: 0.2em; border-radius: 5px;">1</span> <span style="background-color: #F9E59F; padding: 0.2em; border-radius: 5px;">2</span> <span style="background-color: #F7A7A7; padding: 0.2em; border-radius: 5px;">3</span> <span style="background-color: #A6E1A1; padding: 0.2em; border-radius: 5px;">4</span></li> 
  <li>Discourse : <span style="background-color: #A6C8FF; padding: 0.2em; border-radius: 5px;">1</span> <span style="background-color: #A1D8D8; padding: 0.2em; border-radius: 5px;">5</span></li>
  <li>Liste de diffusion<!--newsletter + formulaire pour les membres--> : <span style="background-color: #A6E1A1; padding: 0.2em; border-radius: 5px;">4</span> <span style="background-color: #A1D8D8; padding: 0.2em; border-radius: 5px;">5</span> <span style="background-color: #D3A9F7; padding: 0.2em; border-radius: 5px;">6</span></li> <!-- rosso pastello pallido -->
  <li>Mattermost : <span style="background-color: #A1D8D8; padding: 0.2em; border-radius: 5px;">5</span></li> <!-- seulement pour les membres de l'équipe de coordination de l'UdeM, système utilisé dans le cadre de la CRCEN-->
  <li>GitLab : <span style="background-color: #F9E59F; padding: 0.2em; border-radius: 5px;">2</span> <span style="background-color: #F7A7A7; padding: 0.2em; border-radius: 5px;">3</span></li> <!-- verde acqua pastello pallido -->
  <li>Zotero : <span style="background-color: #F7A7A7; padding: 0.2em; border-radius: 5px;">3</span> <span style="background-color: #D3A9F7; padding: 0.2em; border-radius: 5px;">6</span></li> <!-- publications accéssibles via le site -->
</ul>
</div>


<!--
Aussi : chaque projet peut prévoir un système propre en interne
-->

---

## Gouvernance
Un dispositif organisationnel

<div style="display: flex; justify-content: center; align-items: center; height: 64vh; position: relative;">
  <img src="/gouvernance.png" style="max-width: 90%; height: auto; border-radius: 12px;" />
</div>

---
layout: section
---

# Gouvernance -- dans la pratique...

---
layout: image-left
image: /background-4.svg
---

# Coordination des projets ou de GT

- Unités clés du partenariat
- Chaque projet ou GT est coordonné par un·e responsable dédié·e
- Le·la coordinateur·ice fait le lien entre le projet, la coordination générale et les responsables d’axe
- Il·elle veille à l’avancement opérationnel du projet et au respect du calendrier
- Il·elle assure la communication interne et externe
- Il·elle rédige des rapports d’avancement

Une fiche de poste est en cours de rédaction

<!--tâches concrètes, pour responsabiliser la personne : moment de la rédaction du rapport est un moment de clarification de son rôle auprès des directeurs d'axe et des autres membres du projet ; important également pour la documentation-->

---
layout: image-left
image: /background-3.svg
---

# Direction d'axe

- Élément essentiel pour la cohérence du projet 
- Fonction stratégique et politique (encadrement des équipes et de la recherche)
- Élaboration de rapports d'axe

Description du rôle en cours de finalisation

---
layout: image-left
image: /background.svg
---

## Comité exécutif

- 1 representant·e par axe, 1 representant·e des étudiant·e·s, un represent·e des partenaires, directeur, coordination générale
- Rencontre au moins 3 fois par an (dont au moins une fois avant la réunion plénière)
- Discussions du comité sont à l'origine d'un rapport global du partenariat, qui sera soumis au comité scientifique et présenté lors de la réunion plénière

---
layout: image-left
image: /background-2.svg
---

## Comité scientifique

- Organe consultatif
- Exprime ses retours suite à la soumission du rapport global du partenariat
- Quand pertinent, valide les propositions de projets

---
layout: image-left
image: /background-3.svg
---

## Assembée plénière

- Se réunit une fois par an
- Rassemble tous les membres du projet
- Validation du budget annuel
- Approbation du calendrier annuel des activités
- Présentation et vote des nouvelles propositions
- Moment de discussion et opportunité de développement de nouvelles collaborations
<!--Esapce pour présenter les activités du partenariat (projets, GT, conférences, etc.), espace pour écouter les revues, espace pour table ronde sur des tématiques EDI et d'autres thématiques proposées par le chercheur·euse·s, moment pour un atelier technique/bricolage sur les formats de balisage/chaînes éditoriales, -->

---
layout: image-left
image: /background-4.svg
---

## Comité formation et diffusion

- Calendrier des activités de formation 
- Calendrier des activités de diffusion

## Comité EDID

- Charte EDID
- Groupes de travail
- Ateliers et tables rondes

---
layout: center
---

## Les défis 

<div style="position: relative; padding: 0.5rem;">
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: green; opacity: 0.2; border-radius: 1rem; z-index: 0;"></div>
  <ul>
  <li>Archivage et pérennisation des outils, plateformes et documentations pour garantir leur accessibilité à long terme<!--formats de texte brut--></li>
  <li>Gestion de la mutabilité de l'équipe de coordination et des équipes partenaires</li>
  <li>Organisation des échanges et rencontres à distance, dans un contexte de saturation des communications numériques</li>
  <li>Clarification des rôles de chaque membre, ainsi que des liens entre ces rôles, la recherche générale du partenariat et les projets spécifiques</li>
  <li>Gestion des relations institutionnelles et collaboration avec d'autres projets</li>
  </ul>
</div>

---
layout: cover
background: /background.svg
---

# Merci !
