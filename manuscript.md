---
title: Un zoo de yeux
keywords:
- Perception visuelle
- Anatomie
- Modélisation neurale
lang: fr-FR
date-meta: '2023-08-13'
author-meta:
- Laurent U Perrinet
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Un zoo de yeux" />
  <meta name="citation_title" content="Un zoo de yeux" />
  <meta property="og:title" content="Un zoo de yeux" />
  <meta property="twitter:title" content="Un zoo de yeux" />
  <meta name="dc.date" content="2023-08-13" />
  <meta name="citation_publication_date" content="2023-08-13" />
  <meta property="article:published_time" content="2023-08-13" />
  <meta name="dc.modified" content="2023-08-13T13:38:43+00:00" />
  <meta property="article:modified_time" content="2023-08-13T13:38:43+00:00" />
  <meta name="dc.language" content="fr-FR" />
  <meta name="citation_language" content="fr-FR" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Laurent U Perrinet" />
  <meta name="citation_author_institution" content="Institut de Neurosciences de la Timone, CNRS / Aix-Marseille Université" />
  <meta name="citation_author_orcid" content="0000-0002-9536-010X" />
  <link rel="canonical" href="https://laurentperrinet.github.io/2023-02-01_un-zoo-de-yeux/" />
  <meta property="og:url" content="https://laurentperrinet.github.io/2023-02-01_un-zoo-de-yeux/" />
  <meta property="twitter:url" content="https://laurentperrinet.github.io/2023-02-01_un-zoo-de-yeux/" />
  <meta name="citation_fulltext_html_url" content="https://laurentperrinet.github.io/2023-02-01_un-zoo-de-yeux/" />
  <meta name="citation_pdf_url" content="https://laurentperrinet.github.io/2023-02-01_un-zoo-de-yeux/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://laurentperrinet.github.io/2023-02-01_un-zoo-de-yeux/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://laurentperrinet.github.io/2023-02-01_un-zoo-de-yeux/v/958b53d0300c1e334b4001dca02298446128e34e/" />
  <meta name="manubot_html_url_versioned" content="https://laurentperrinet.github.io/2023-02-01_un-zoo-de-yeux/v/958b53d0300c1e334b4001dca02298446128e34e/" />
  <meta name="manubot_pdf_url_versioned" content="https://laurentperrinet.github.io/2023-02-01_un-zoo-de-yeux/v/958b53d0300c1e334b4001dca02298446128e34e/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://laurentperrinet.github.io/2023-02-01_un-zoo-de-yeux/v/958b53d0300c1e334b4001dca02298446128e34e/))
was automatically generated
from [laurentperrinet/2023-02-01_un-zoo-de-yeux@958b53d](https://github.com/laurentperrinet/2023-02-01_un-zoo-de-yeux/tree/958b53d0300c1e334b4001dca02298446128e34e)
on August 13, 2023.
</em></small>



## Authors



+ **Laurent U Perrinet**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-9536-010X](https://orcid.org/0000-0002-9536-010X)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [laurentperrinet](https://github.com/laurentperrinet)
    · ![Mastodon icon](images/mastodon.svg){.inline_icon width=16 height=16}
    [\@laurentperrinet@neuromatch.social](https://neuromatch.social/@laurentperrinet)
    <br>
  <small>
     Institut de Neurosciences de la Timone, CNRS / Aix-Marseille Université
     · Funded by This research was funded by the European Union ERA-NET CHIST-ERA 2018 research and innovation program under grant number ANR-19-CHR3-0008-03 “APROVIS3D”, ANR grant number ANR-20-CE23-0021 “AgileNeuroBot”, as well as from Initiative d’Excellence d’Aix-Marseille Université–A*MIDEX grant number AMX-21-RID-025 “Polychronies”.
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/laurentperrinet/2023-02-01_un-zoo-de-yeux/issues)

:::


## Résumé {.page_break_before}

La plupart d'entre nous peut aisément et instantanément explorer le monde visible qui nous entoure grâce à nos yeux et à notre système visuel qui analyse ces informations. Toutefois, des problèmes en relation avec la vision sont fréquents, qu'il s'agisse de conditions comme l'hypermétropie ou la myopie, pouvant être corrigées par le port de lunettes. Cependant, des problèmes plus sévères existent, comme les affections rétiniennes liées à l'âge ou à des facteurs génétiques. Ce sont des conditions graves pouvant entraîner des handicaps importants. Mais au fond, comment fonctionne le mécanisme des yeux ? Quelle est l'origine de ces problèmes potentiels ? Quelles leçons pouvons-nous tirer de la diversité des structures oculaires présentes dans le règne animal ? Est-il possible de remonter aux origines de leur évolution pour comprendre comment les yeux ont émergé au fil de l'évolution du monde vivant ?


## L’œil humain

L'œil humain, l'organe sensible de notre vision, suscite un émerveillement devant les mécanismes ingénieux qui le caractérisent. Penchons-nous sur quelques caractéristiques de la vision qui nous semblent naturelles, mais qui feraient pâlir d'envie n'importe quel concepteur de caméras artificielles. En effet, notre vision nous permet de capturer en continu des images en couleur haute définition avec une relative perception de la profondeur. Notre œil peut fonctionner dans des conditions de lumière variées, du plein soleil à la lueur de la lune, et s'adapter à différentes situations de visibilité. Tout cela se déroule de manière autonome, avec une consommation d'énergie relativement faible par rapport à un dispositif artificiel.

Vu de l'extérieur, l'œil présente le globe oculaire, entouré par les paupières, et au centre se trouve la pupille, autour de laquelle l'iris coloré peut se dilater ou se contracter selon la luminosité ou l'attention. Cette forme de globe sphérique lui permet de réaliser des mouvements rapides de rotation et diriger le regard vers des points d'intérêt. Une coupe transversale permet de suivre le parcours de la lumière : elle traverse d'abord une surface bombée, la cornée, ensuite passe le cristallin, qui joue le rôle d'une lentille en concentrant les rayons lumineux sur le fond de l'œil. Sur cette surface rétinienne réside un tissu qui représente le composant sensible de l'œil, la rétine.

Dans cette rétine se trouvent de nombreux neurones sensibles à la lumière et des mécanismes qui transforment ces signaux pour les acheminer vers le cerveau. Environ 100 millions de photorécepteurs sont présents qui convertissent l'énergie électromagnétique portée par les photons en réactions électrochimiques. Celles-ci génèrent une activité neuronale qui passe par différentes couches de traitement pour converger vers les quelques 1,5 million de cellules ganglionnaires dont les sorties s'unissent pour former le nerf optique, reliant ainsi la rétine au reste du cerveau. De fait, la rétine est la seule portion du système nerveux que nous pouvons directement observer !

Mais nos yeux ne se résument pas simplement à ça ! Une complexité incroyable réside autour du globe oculaire pour permettre son mouvement, maintenir son humidité par les larmes ou accomplir un simple clignement. Globalement, cet ensemble ressemble à une mécanique parfaitement réglée, presque comme une horloge, une analogie souvent utilisée pour justifier l'idée d'une conception intelligente derrière nos yeux : "Comment aurait-il pu en être autrement ?" Répondre à cet argument n'est pas évident d'emblée... En poussant davantage la curiosité, nous réalisons de plus la variété des formes oculaires dans le règne animal, démontrant que les animaux utilisent des mécanismes tout aussi ingénieux. Cette exploration peut avoir des applications technologiques futures, mais surtout, elle va nous aider à mieux comprendre notre propre vision et à répondre à la question : "Qui a conçu l'œil ?"

## La pupille, la prunelle de nos yeux

Commençons notre exploration de la diversité des yeux dans le règne animal en portant notre attention sur sa partie la plus apparente : la pupille. Comme nous l'avons vu, cette composante du globe oculaire module le passage de la lumière. Intéressons-nous d'abord à un voisin proche, le chat domestique : en fonction de la luminosité, ses pupilles peuvent changer de la forme parfaitement ronde qu'elle adopte dans l'obscurité pour se contracter graduellement et former cette fente caractéristique en forme de biseau vertical. Les humains présentent un mécanisme similaire, mais la contraction y est uniforme dans toutes les directions, maintenant ainsi une forme ronde.

De manière plus étonnante, les pupilles des moutons se contractent elles selon un axe horizontal, et ceci même quand ces animaux baissent leur tête pour brouter. Cette adaptation est expliquée par le statut de proie plus fréquent chez les moutons et cette configuration leur permet d'étendre leur champ de vision. En revanche, la forme de fente verticale des chats favorise plutôt la perception de la profondeur, et comme prédateurs, cette avantage s'avère plus utile pour une attaque. Ainsi, la sélection naturelle a conduit à une évolution distincte des pupilles de ces deux espèces.

D'autres animaux présentent des pupilles aux formes encore plus remarquables. Un exemple est la seiche, dont la pupille, une fois contractée, arbore une forme ondulée ressemblant à la lettre manuscrite "w". Cette pupille unique dans le règne animal a longtemps suscité une énigme. Il s'avère d'autre part que ces animaux modifient la couleur de leur peau pour communiquer ou se camoufler. Ce comportement constitue un paradoxe, car un tel comportement nécessite la perception de la couleur ou de la texture de l'objet à imiter, hors il a été montré qu'ils ne possèdent pas de photorécepteurs sensibles à différentes couleurs.

Une hypothèse fascinante a émergé qui relie ces deux mystères. Elle suggère que la forme de la pupille pourrait jouer un rôle dans la perception des couleurs. À l'instar d'un arc-en-ciel décomposant les couleurs en bandes distinctes, les systèmes optiques peuvent réfléchir les couleurs à des angles légèrement variés. La pupille singulière de la seiche pourrait ainsi produire différentes formes pour chaque couleur, permettant au cerveau d'en extraire les informations pour discerner les couleurs, et ceci sans nécessiter de photorécepteurs spécifiques. Cette hypothèse nécessite davantage de validation, mais elle illustre l'ingéniosité des stratégies mises en place par ces systèmes. N'oublions pas que la biologie s'explique uniquement à travers la sélection naturelle, où des millions de générations et des milliards d'individus ont favorisé ces traits pour la survie de l'espèce.

## D’autres facettes des yeux

Les yeux des humains, des chats et des moutons présentent une grande variabilité dans leurs formes, mais partagent également de nombreux traits communs. Il semble donc qu'ils aient évolué selon des trajectoires distinctes et indépendantes, tout en ayant probablement un ancêtre commun. Si l'on remonte encore plus loin dans les branches de l'arbre de l'évolution, on découvre une autre forme d'œil radicalement différente. Au lieu de focaliser une image sur la rétine grâce à une pupille, ces yeux sont constitués de multiples éléments oculaires allongés et juxtaposés formant un œil composé.

L'exemple le plus frappant de cette configuration est celui de la mouche. Les yeux d'une mouche commune comportent environ 10 000 facettes organisées en une grille hexagonale relativement régulière. Cette structure permet à la mouche d'avoir un champ de vision panoramique et chacune de ces facettes comprend une lentille et quelques photorécepteurs. Ce système permet aux mouches d'exécuter des manœuvres impressionnantes, avec des accélérations dignes des meilleurs avions de chasse. Plus surprenant encore, ce système pèse moins d'un gramme et consomme très peu d'énergie. Comprendre ce mécanisme pourrait être extrêmement précieux pour guider la conception de futurs robots volants.

Ces yeux dérivent certainement d'un ancêtre commun. En remontant encore plus en avant dans "l'arbre du vivant", on peut identifier une forme encore plus élémentaire chez certains microorganismes dotés d'un mécanisme phototactique, c'est-à-dire un mouvement guidé par la lumière. Ce mécanisme repose sur une association simple entre un capteur photosensible, une position excentrée dans l'organisme définissant une direction et des cils agissant comme des moteurs pour déplacer l'organisme. En fonction de si l'organisme cherche à se diriger vers une source de lumière (potentiellement une source de nourriture) ou à l'éviter, un mécanisme basique entre les cellules sensibles et motrices permet de mettre en place cette orientation.

Des études récentes suggèrent que les yeux ont probablement été "inventés" à plusieurs reprises. Par exemple, considérons le système visuel unique de la coquille Saint-Jacques et ses nombreux yeux indépendants d'un bleu iridiscent (plus de 200), permettant à ce mollusque d'explorer son environnement lumineux immédiat. Ainsi, certaines morphologies sont si distinctes qu'elles semblent ne pas partager d'ancêtre commun. Cette hypothèse semble difficile à accepter, car nous avons tendance à placer les humains au sommet de la hiérarchie. Cependant, nous avons également vu que les yeux évoluent en réponse à des niches écologiques spécifiques, et à la lumière des pressions exercées par la sélection naturelle, il n'y a peut-être pas de nécessité à ce qu'il existe un ancêtre commun pour tous les types d'yeux dans le règne vivant.

## De l'imitation à la compréhension : L'inspiration du vivant pour la technologie.

S'inspirant de cette richesse nouvellement redécouverte des formes du vivant, une approche a récemment émergé dans le domaine de l'ingénierie. Une illustration de cette démarche est l'étude du comportement d'une araignée du désert qui utilise la polarisation différentielle de la lumière autour du soleil dans le ciel, créant une forme de croix. En effet, la lumière possède, en plus de son énergie et de sa couleur, cette propriété dite de polarisation. La lumière polarisée peut être filtrée et les lunettes de cinéma 3D utilisent cette propriété pour présenter des images différentes à chaque œil, créant ainsi une impression de profondeur.

Si nous y sommes naturellement aveugles, ces araignées sont capables de détecter cette configuration grâce à des capteurs sensibles à la polarisation, leur permettant de déterminer la position du soleil. Une équipe de chercheurs dirigée par Stéphane Viollet à Marseille a développé un robot utilisant cette propriété. En utilisant la lumière polarisée, leur système peut avec précision repérer la position du soleil dans le ciel dans diverses conditions météorologiques, même lorsque le ciel est nuageux. Cette technologie pourrait compléter de manière cruciale les systèmes de navigation, comme le GPS, qui peuvent parfois être défaillants ou inaccessibles. Elle pourrait avoir des applications majeures dans les voitures autonomes du futur.

Une autre avancée notable est l'émergence de nouvelles caméras inspirées du fonctionnement de la rétine. Ces caméras sont dites événementielles, car au lieu de représenter à certains instants l'ensemble de la luminance sur une grille de pixels, elles reposent sur le principe de transmettre les événements correspondant à des changements de luminance. Ainsi, les informations sont transformées indépendamment par les neurones de sortie de la rétine, sans nécessité d'une horloge centrale. Cela permet de réduire drastiquement le flux d'informations : dans un cas extrême, une image statique ne génère aucun événement. 

L'utilisation de ces caméras représente un changement de paradigme car, contrairement aux caméras classiques qui traitent des images séquentiellement à, par exemple, 30 images par seconde, ces caméras envoient des informations en continu. L'information temporelle est représentée de manière beaucoup plus précise, souvent à l'échelle de la microseconde. De fait, seules les zones d'intérêt, comme les contours des objets, sont représentées. Cette nouvelle représentation exige un changement radical dans la façon de concevoir les algorithmes de traitement d'image et s'accompagne d'une révolution dans la conception de puces électroniques. De nouvelles technologies inspirées du fonctionnement du cerveau permettent de créer des puces où le calcul est extrêmement parallélisé, bien mieux que les caméras traditionnelles. Cette ingénierie neuromorphique pourrait révolutionner le traitement des images par leur efficacité énergétique bien supérieure. Ce point est crucial pour des systèmes embarqués comme des véhicules autonomes qui doivent répondre à des impératifs de consommation énergétique et d'impact environnemental liés à la transition écologique.

## L'impact de cette compréhension

Cette compréhension a des implications profondes, tant du point de vue de la recherche fondamentale que de l'application technologique. Elle nous pousse à élargir notre vision de ce qui est possible de réaliser en matière de conception de systèmes visuels, en nous inspirant de la nature pour créer des solutions innovantes, plutôt que de se limiter à l'amélioration de modèles basés sur la simple analogie de l'appareil photo. Les découvertes sur les systèmes visuels des animaux, associées aux avancées technologiques telles que les caméras événementielles, ouvrent des perspectives passionnantes dans des domaines tels que la robotique, la navigation autonome et le traitement des images. En fin de compte, cette compréhension approfondie de la vision dans le règne animal peut servir d'inspiration pour repousser les limites de la technologie et de la compréhension scientifique.

L'exploration que nous venons de faire de la diversité des yeux dans le règne animal nous a permis une interaction riche entre les connaissances fondamentales et appliquées dans le domaine de la vision. Les différentes anatomies oculaires que nous avons étudiées révèlent aussi que chaque système visuel est adapté à un ensemble spécifique de comportements et d'environnements. Bien que certaines de ces inventions puissent sembler aussi complexes que les machines créées par les mains d'un horloger, le point essentiel réside dans le fait que les yeux aient évolué indépendamment à plusieurs reprises sans avoir besoin de recourir à l'existence d'un dessein intelligent, mettant ainsi en lumière la diversité des solutions émergentes résultant des mécanismes évolutifs du vivant.


This manuscript is a template (aka "rootstock") for [Manubot](https://manubot.org/ "Manubot"), a tool for writing scholarly manuscripts.
Use this template as a starting point for your manuscript.

The rest of this document is a full list of formatting elements/features supported by Manubot.
Compare the input (`.md` files in the `/content` directory) to the output you see below.

## Basic formatting

**Bold** __text__

[Semi-bold text]{.semibold}

[Centered text]{.center}

[Right-aligned text]{.right}

*Italic* _text_

Combined *italics and __bold__*

~~Strikethrough~~

1. Ordered list item
2. Ordered list item
    a. Sub-item
    b. Sub-item
        i. Sub-sub-item
3. Ordered list item
    a. Sub-item

- List item
- List item
- List item

subscript: H~2~O is a liquid

superscript: 2^10^ is 1024.

[unicode superscripts](https://www.google.com/search?q=superscript+generator)⁰¹²³⁴⁵⁶⁷⁸⁹

[unicode subscripts](https://www.google.com/search?q=superscript+generator)₀₁₂₃₄₅₆₇₈₉

A long paragraph of text.
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Putting each sentence on its own line has numerous benefits with regard to [editing](https://asciidoctor.org/docs/asciidoc-recommended-practices/#one-sentence-per-line) and [version control](https://rhodesmill.org/brandon/2012/one-sentence-per-line/).

Line break without starting a new paragraph by putting  
two spaces at end of line.

## Document organization

Document section headings:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### A heading centered on its own printed page{.center .page_center}

<!-- an arbitrary comment. visible in input, but not visible in output. -->

Horizontal rule:

---

`Heading 1`'s are recommended to be reserved for the title of the manuscript.

`Heading 2`'s are recommended for broad sections such as *Abstract*, *Methods*, *Conclusion*, etc.

`Heading 3`'s and `Heading 4`'s are recommended for sub-sections.

## Links

Bare URL link: <https://manubot.org>

[Long link with lots of words and stuff and junk and bleep and blah and stuff and other stuff and more stuff yeah](https://manubot.org)

[Link with text](https://manubot.org)

[Link with hover text](https://manubot.org "Manubot Homepage")

[Link by reference][manubot homepage]

[Manubot Homepage]: https://manubot.org

## Citations

Citation by DOI [@doi:10.7554/eLife.32822].

Citation by PubMed Central ID [@pmc:PMC6103790].

Citation by PubMed ID [@pubmed:30718888].

Citation by Wikidata ID [@wikidata:Q56458321].

Citation by ISBN [@isbn:9780262517638].

Citation by URL [@{https://greenelab.github.io/meta-review/}].

Citation by alias [@deep-review].

Multiple citations can be put inside the same set of brackets [@doi:10.7554/eLife.32822; @deep-review; @isbn:9780262517638].
Manubot plugins provide easier, more convenient visualization of and navigation between citations [@doi:10.1371/journal.pcbi.1007128; @pubmed:30718888; @pmc:PMC6103790; @deep-review].

Citation tags (i.e. aliases) can be defined in their own paragraphs using Markdown's reference link syntax:

[@deep-review]: doi:10.1098/rsif.2017.0387

## Referencing figures, tables, equations

Figure @fig:square-image

Figure @fig:wide-image

Figure @fig:tall-image

Figure @fig:vector-image

Table @tbl:bowling-scores

Equation @eq:regular-equation

Equation @eq:long-equation

## Quotes and code

> Quoted text

> Quoted block of text
>
> Two roads diverged in a wood, and I—  
> I took the one less traveled by,  
> And that has made all the difference.

Code `in the middle` of normal text, aka `inline code`.

Code block with Python syntax highlighting:

```python
from manubot.cite.doi import expand_short_doi

def test_expand_short_doi():
    doi = expand_short_doi("10/c3bp")
    # a string too long to fit within page:
    assert doi == "10.25313/2524-2695-2018-3-vliyanie-enhansera-copia-i-insulyatora-gypsy-na-sintez-ernk-modifikatsii-hromatina-i-svyazyvanie-insulyatornyh-belkov-vtransfetsirovannyh-geneticheskih-konstruktsiyah"
```

Code block with no syntax highlighting:

```
Exporting HTML manuscript
Exporting DOCX manuscript
Exporting PDF manuscript
```

## Figures

![
**A square image at actual size and with a bottom caption.**
Loaded from the latest version of image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/square.png "Square image"){#fig:square-image}

![
**An image too wide to fit within page at full size.**
Loaded from a specific (hashed) version of the image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/wide.png "Wide image"){#fig:wide-image}

![
**A tall image with a specified height.**
Loaded from a specific (hashed) version of the image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/tall.png "Tall image"){#fig:tall-image height=3in}

![
**A vector `.svg` image loaded from GitHub.**
The parameter `sanitize=true` is necessary to properly load SVGs hosted via GitHub URLs.
White background specified to serve as a backdrop for transparent sections of the image.
](https://raw.githubusercontent.com/manubot/resources/main/test/vector.svg?sanitize=true "Vector image"){#fig:vector-image height=2.5in .white}

## Tables

| *Bowling Scores* | Jane          | John          | Alice         | Bob           |
|:-----------------|:-------------:|:-------------:|:-------------:|:-------------:|
| Game 1 | 150 | 187 | 210 | 105 |
| Game 2 |  98 | 202 | 197 | 102 |
| Game 3 | 123 | 180 | 238 | 134 |

Table: A table with a top caption and specified relative column widths.
{#tbl:bowling-scores}

|         | Digits 1-33                        | Digits 34-66                      | Digits 67-99                      | Ref.                                                        |
|:--------|:-----------------------------------|:----------------------------------|:----------------------------------|:------------------------------------------------------------|
| pi      | 3.14159265358979323846264338327950 | 288419716939937510582097494459230 | 781640628620899862803482534211706 | [`piday.org`](https://www.piday.org/million/)               |
| e       | 2.71828182845904523536028747135266 | 249775724709369995957496696762772 | 407663035354759457138217852516642 | [`nasa.gov`](https://apod.nasa.gov/htmltest/gifcity/e.2mil) |

Table: A table too wide to fit within page.
{#tbl:constant-digits}

|          | **Colors** <!-- $colspan="2" --> |                      |
|:--------:|:--------------------------------:|:--------------------:|
| **Size** | **Text Color**                   | **Background Color** |
| big      | blue                             | orange               |
| small    | black                            | white                |

Table: A table with merged cells using the `attributes` plugin.
{#tbl: merged-cells}

## Equations

A LaTeX equation:

$$\int_0^\infty e^{-x^2} dx=\frac{\sqrt{\pi}}{2}$$ {#eq:regular-equation}

An equation too long to fit within page:

$$x = a + b + c + d + e + f + g + h + i + j + k + l + m + n + o + p + q + r + s + t + u + v + w + x + y + z + 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9$$ {#eq:long-equation}

## Special

<i class="fas fa-exclamation-triangle"></i> [WARNING]{.semibold} _The following features are only supported and intended for `.html` and `.pdf` exports._
_Journals are not likely to support them, and they may not display correctly when converted to other formats such as `.docx`._

[Link styled as a button](https://manubot.org "Manubot Homepage"){.button}

Adding arbitrary HTML attributes to an element using Pandoc's attribute syntax:

::: {#some_id_1 .some_class style="background: #ad1457; color: white; margin-left: 40px;" title="a paragraph of text" data-color="white" disabled="true"}
Manubot Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot.
Manubot Manubot.
Manubot.
:::

Adding arbitrary HTML attributes to an element with the Manubot `attributes` plugin (more flexible than Pandoc's method in terms of which elements you can add attributes to):

Manubot Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot.
Manubot Manubot.
Manubot.
<!-- $id="element_id" class="some_class" $style="color: #ad1457; margin-left: 40px;" $disabled="true" $title="a paragraph of text" $data-color="red" -->

Available background colors for text, images, code, banners, etc:  

`white`{.white}
`lightgrey`{.lightgrey}
`grey`{.grey}
`darkgrey`{.darkgrey}
`black`{.black}
`lightred`{.lightred}
`lightyellow`{.lightyellow}
`lightgreen`{.lightgreen}
`lightblue`{.lightblue}
`lightpurple`{.lightpurple}
`red`{.red}
`orange`{.orange}
`yellow`{.yellow}
`green`{.green}
`blue`{.blue}
`purple`{.purple}

Using the [Font Awesome](https://fontawesome.com/) icon set:

<!-- include the Font Awesome library, per: https://fontawesome.com/start -->
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css">

<i class="fas fa-check"></i> <i class="fas fa-question"></i> <i class="fas fa-star"></i> <i class="fas fa-bell"></i> <i class="fas fa-times-circle"></i> <i class="fas fa-ellipsis-h"></i>

[
<i class="fas fa-scroll fa-lg"></i> **Light Grey Banner**<br>
useful for *general information* - [manubot.org](https://manubot.org/)
]{.banner .lightgrey}

[
<i class="fas fa-info-circle fa-lg"></i> **Blue Banner**<br>
useful for *important information* - [manubot.org](https://manubot.org/)
]{.banner .lightblue}

[
<i class="fas fa-ban fa-lg"></i> **Light Red Banner**<br>
useful for *warnings* - [manubot.org](https://manubot.org/)
]{.banner .lightred}


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

