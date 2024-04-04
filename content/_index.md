
+++

title = "Pervasive Computing @ UniBo / Cesena: overview"
description = "Quick overview of the research activities of the Pervasive Computing group at the University of Bologna, Cesena campus"
outputs = ["Reveal"]
aliases = [
    "/index/"
]

+++


# **Pervasive Computing**
# @ UniBo / Cesena: overview

#### [Danilo Pianini](mailto:danilo.pianini@unibo.it) --- {{% today %}}

---

# Who

## Tenured

| Nice picture | Name | Role |
| ---- | ---- | ----- |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=341468&IdFoto=23233366) | [Andrea Omicini](https://www.unibo.it/sitoweb/andrea.omicini/en) | Full professor and Dean |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=355340&IdFoto=e3a7b911) | [Mirko Viroli](https://www.unibo.it/sitoweb/mirko.viroli/en) | Full professor |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=340844&IdFoto=bd99721f) | [Alessandro Ricci](https://www.unibo.it/sitoweb/a.ricci/en) | Associate professor |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=447370&IdFoto=f3c9f266) | [Andrea Roli](https://www.unibo.it/sitoweb/andrea.roli/en) | Assistant professor |

---

# Who

## Tenure track / Fixed time researchers

Danilo pianini and roberto casadei

| Nice picture | Name | Role |
| ---- | ---- | ----- |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=503326&IdFoto=e1c80103) | [Danilo Pianini](https://www.unibo.it/sitoweb/danilo.pianini/en) | Senior Assistant professor |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=649232&IdFoto=4ba13386) | [Roberto Casadei](https://www.unibo.it/sitoweb/roby.casadei/en) | Senior Assistant professor |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=758527&IdFoto=0d144755) | [Giovanni Ciatto](https://www.unibo.it/sitoweb/giovanni.ciatto/en) | Junior Assistant professor |

---

# Who

## Phd Candidates / post-docs

| Nice picture | Name | Role |
| ---- | ---- | ----- |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=979102&IdFoto=73c988ab) | [Gianluca Aguzzi](https://www.unibo.it/sitoweb/gianluca.aguzzi/en) | PhD candidate |

---

# Who

## Phd Candidates / Students

| Nice picture | Name | Role |
| ---- | ---- | ----- |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1444563&IdFoto=cb27afa6) | [Ruslan Shaiakhmetov](https://www.unibo.it/sitoweb/ruslan.shaiakhmetov/en) | PhD student |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1135878&IdFoto=7e5aea53) | [Martina Baiardi](https://www.unibo.it/sitoweb/m.baiardi/en) | PhD student |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1241268&IdFoto=19a442b7) | [Davide Domini](https://www.unibo.it/sitoweb/davide.domini/en) | PhD student |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1057398&IdFoto=d40837ab) | [Nicolas Farabegoli](https://www.unibo.it/sitoweb/nicolas.farabegoli/en) | PhD student |

---

# Who

## Research fellows

| Nice picture | Name | Role |
| ---- | ---- | ----- |
| ![](https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1195649&IdFoto=a66c31ab) | [Angelo Filaseta](https://www.unibo.it/sitoweb/angelo.filaseta/en) | Research fellow |
| ![](cortecchia.jpg) | [Angela Cortecchia](mailto:angela.cortecchia@unibo.it) | Guest reseach fellow |

---

# What

Pervasive computing, full spectrum, from modelling to industrial application

![](group-act.svg)

note: seniors omitted

---

# Conceptualization

## Finding the **right** abstractions

<blockquote>
Pick the <b>right abstractions</b>, and programming will <u>flow naturally from design</u>;
modules will have small and simple interfaces;
and new functionality will more likely fit in without extensive reorganization.
<br>
Pick the <b>wrong abstractions</b>, and programming will be <u>a series of nasty surprises</u>:
interfaces will become baroque and clumsy as they are forced to accommodate unanticipated interactions,
and even the simplest of changes will be hard to make.
<cite>Edmond Lau, The Effective Engineer: How to Leverage Your Efforts In Software</cite>
</blockquote>

{{% multicol %}}{{% col %}}
#### Macroprogramming / aggregate computing
* Control multiple entities at once
* Program space and time, not devices
* **Roberto** will provide an introduction:<br>*From Macro-programming to Aggregate Computing*
{{% /col %}}{{% col %}}
#### Agent-oriented BDI programming
* Model autonomous entities with beliefs, desires, intentions
* **Martina** will show a new experimental tool<br>*Martina metti un titolo*
{{% /col %}}{{% /multicol %}}

---

# Learning

## Learning behavior **collectively**

<blockquote>
Collective wisdom is more likely to arise when sound judgment is based on the entirety of our multiple intelligences.
<cite>Alan Briskin, The Power of Collective Wisdom: And the Trap of Collective Folly</cite>
</blockquote>

{{% multicol %}}{{% col %}}
#### Multi-Agent Reinforcement Learning
* Gianluca add some bullets
* **Gianluca** will gianluca completa<br>*Gianluca metti un titolo*
{{% /col %}}{{% col %}}
#### Specialized federated learning
* Learn a joint model without sharing data
* Model peer-to-peer learning through aggregate computing
* Address data heterogeneity through opportunistic clustered federated learning
* **Davide** will provide an introduction<br>*Field Based Federated Learning*
{{% /col %}}{{% /multicol %}}

---

# Tools

## Ideas need to be brought to **practice**

<blockquote>
If the only tool you have is a hammer, it's hard to eat spaghetti.
<cite>David Allen</cite>
</blockquote>

{{% multicol %}}{{% col %}}
#### Programming Languages
* The practical tool to capture abstractions
* [Protelis](https://protelis.github.io/), a stand-alone aggregate programming language
  * legacy, maintained but no longer evolved
* [Scafi](https://scafi.github.io/), a Scala DSL for aggregate computing
  * **Gianluca** will introduce it
* [Collektive](https://github.com/Collektive/collektive), a Kotlin Multiplatform DSL for aggregate computing
  * **Angela** will introduce it
* [JaKtA](https://github.com/jakta-bdi/jakta), a Kotlin DSL for BDI Agents
  * **Martina** will introduce it
{{% /col %}}{{% col %}}
#### Simulation
* Essential tool for development and evaluation
* [Alchemist](https://alchemistsimulator.github.io/), a simulator for pervasive computing
  * I will show a few use cases
* Improvements to existing industrial simulators for race cars are ongoing
  * **Ruslan** is working on them
{{% /col %}}{{% /multicol %}}

---

# Deployment

## Ideas need to be brought to **practice**

<blockquote>
Good ideas need good strategy to realize their potential.
<cite>Reid Hoffman</cite>
</blockquote>

{{% multicol %}}{{% col %}}
#### Cluster and grid computing
* Experimenting ways to control heterogeneous devices uniformly
* Two main heterogeneous clusters:
  * AlmaAI
  * Area 4.0
* **Giovanni** leads the development
{{% /col %}}{{% col %}}
#### Pulverization
* An approach to break down computation in small pieces and deploy it heterogeneous devices
* Bridge the gap between homo- and heterogeneity
  * **Nicolas** designed a pulverization platform
{{% /col %}}{{% /multicol %}}

---

# Industry

## Ideas need to be brought to **practice**

<blockquote>
Every once in a while, a new technology, an old problem, and a big idea turn into an innovation.
<cite>Dean Kamen</cite>
</blockquote>

{{% multicol %}}{{% col %}}
#### Wood 4.0
* Collaboration with SCM Group
* Software updates in large woodwork industrial machines
* Business-critical
* Heterogeneous machinery
* **Angelo** will discuss it
{{% /col %}}{{% col %}}
#### Racecar simulation reality gap
* Collaboration with Dallara Automobili
* Essential tool for top tier racing
* Correlation between track and simulation is central
* The ability to mimic a human driver is paramount
* **Ruslan** is working on them
{{% /col %}}{{% /multicol %}}

---

# Lists and enums

1. First ordered list item
1. Another item
    * Unordered sub-list.
    * with two items
        * another sublist
            1. With a sub-enum
            1. yay!
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
1. And another item.

---

# Inline images

![Alternative text](https://upload.wikimedia.org/wikipedia/it/6/6c/Scavolino_innevata.jpg)

---

## Fallback to shortcodes for resizing

Autoresize specifying

* `max-w` (percent of parent element width) and/or `max-h` (percent of viewport height) as max sizes , and
* `width` and/or `height` as *exact* sizes (as percent of viewport size)

{{< figure src="https://upload.wikimedia.org/wikipedia/it/6/6c/Scavolino_innevata.jpg" height="20">}}

---

## Multi-column slide

{{% multicol %}}{{% col %}}
Column 1
{{% /col %}}{{% col %}}
Column 2
{{% /col %}}{{% /multicol %}}

---

## Tick and Cross

{{% tick %}} This is something good {{% /tick %}}
{{% cross %}} This is something good {{% /cross %}}

---

## Chart.js

{{< chart >}}
{
    type: 'bar',
    data: {
        labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
        datasets: [{
            label: 'Bar Chart',
            data: [12, 19, 18, 16, 13, 14],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}

---

## FontAwesome

<i class="fa-solid fa-mug-hot"></i>
<i class="fa-solid fa-lemon"></i>
<i class="fa-solid fa-flask"></i>
<i class="fa-solid fa-apple-whole"></i>
<i class="fa-solid fa-bacon"></i>
<i class="fa-solid fa-beer-mug-empty"></i>
<i class="fa-solid fa-pepper-hot"></i>

---

## Bootstrap 1

<div class="card w-100" >
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/View_of_Cesena_from_the_Abbey.jpg/1920px-View_of_Cesena_from_the_Abbey.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>

---

## Bootstrap 2

<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-secondary">Secondary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-light">Light</button>
<button type="button" class="btn btn-dark">Dark</button>

<button type="button" class="btn btn-link">Link</button>

---

## Low res, plain markdown

![](https://upload.wikimedia.org/wikipedia/it/thumb/6/6c/Scavolino_innevata.jpg/260px-Scavolino_innevata.jpg)

---

## Hi res, plain markdown

![](https://upload.wikimedia.org/wikipedia/it/6/6c/Scavolino_innevata.jpg)

---

## Low res, default

{{< figure src="https://upload.wikimedia.org/wikipedia/it/thumb/6/6c/Scavolino_innevata.jpg/260px-Scavolino_innevata.jpg" >}}

---

## Hi res, default

{{< figure src="https://upload.wikimedia.org/wikipedia/it/6/6c/Scavolino_innevata.jpg" >}}

---

## Low res, enlarged horizontally

{{< figure src="https://upload.wikimedia.org/wikipedia/it/thumb/6/6c/Scavolino_innevata.jpg/260px-Scavolino_innevata.jpg" width="100">}}

---

## Low res, enlarged vertically

{{< figure src="https://upload.wikimedia.org/wikipedia/it/thumb/6/6c/Scavolino_innevata.jpg/260px-Scavolino_innevata.jpg" height="100">}}

---

## Hi res, reduced horizontally

{{< figure src="https://upload.wikimedia.org/wikipedia/it/6/6c/Scavolino_innevata.jpg" width="50">}}

---

## Hi res, reduced vertically

{{< figure src="https://upload.wikimedia.org/wikipedia/it/6/6c/Scavolino_innevata.jpg" height="50">}}

---

## Hi res, reducing maximum expansion horizontally

{{< figure src="https://upload.wikimedia.org/wikipedia/it/6/6c/Scavolino_innevata.jpg" width="50">}}

---

## Hi res, reducing maximum expansion vertically

{{< figure src="https://upload.wikimedia.org/wikipedia/it/6/6c/Scavolino_innevata.jpg" height="50">}}

---

{{< slide background-image="https://upload.wikimedia.org/wikipedia/it/6/6c/Scavolino_innevata.jpg" >}}

# Large images as background
## (May affect printing)

---

{{< slide background-image="https://upload.wikimedia.org/wikipedia/it/6/6c/Scavolino_innevata.jpg" state="blur-animation-light"  transition="fade-in fade-out" >}}

# Also available with blur and custom transitions
## (May affect printing)

---

# $$\LaTeX{}$$


Inline equations like $E=mc^2$

$$\frac{n!}{k!(n-k)!} = \binom{n}{k}$$

---

# Code snippets


```kotlin
val x = pippo
```

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello world!")
}
```

---

# Tables

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

---

# Quotes

> Multiple
> lines
> of
> a
> single
> quote
> get
> joined

> Very long one liners of Markdown text automatically get broken into a multiline quotation, which is then rendered in the slides.

---

# Fragments

* {{< frag c="pluto" >}}
* {{< frag c="pluto" >}}
* {{< frag c="pluto" >}}

---

# Graphs via Gravizo

{{< gravizo "Example Gravizo graph" >}}
  digraph G {
    aize ="4,4";
    main [shape=box];
    main -> parse [weight=8];
    parse -> execute;
    main -> init [style=dotted];
    main -> cleanup;
    execute -> { make_string; printf}
    init -> make_string;
    edge [color=red];
    main -> printf [style=bold,label="100 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compare;
  }
{{< /gravizo >}}

---

# Graphs via mermaid.js

```mermaid
classDiagram
  Class01 <|-- AveryLongClass : Coosssl
  Class03 *-- Class04
  Class05 o-- Class06
  Class07 .. Class08
  Class09 --> C2 : Where am i?
  Class09 --* C3
  Class09 --|> Class07
  Class07 : equals()
  Class07 : Object[] elementData
  Class01 : size()
  Class01 : int chimp
  Class01 : int gorillasaaaaaaaaaaaaaaaaaaaaaa
  Class08 <--> C2: Cool label
```


---


# Graphs via mermaid.js with options

```mermaid
%%{init: {'theme':'default', 'themeVariables': { 'fontSize': '.34em', 'fontFamily': 'verdana' }}}%%
classDiagram
  Class01 <|-- AveryLongClass : Coosssl
  Class03 *-- Class04
  Class05 o-- Class06
  Class07 .. Class08
  Class09 --> C2 : Where am i?
  Class09 --* C3
  Class09 --|> Class07
  Class07 : equals()
  Class07 : Object[] elementData
  Class01 : size()
  Class01 : int chimp
  Class01 : int gorillasaaaaaaaaaaaaaaaaaaaaaa
  Class08 <--> C2: Cool label
```


---
# Graphs via mermaid.js 2

```mermaid
graph TD
  SL([fa:fa-user second level]) --> L[solution]
  L -- solution email --> db[(mysql)]
  db --> X[automatic]
  X --> CM([fa:fa-users first level])
  db -- Email --> c([customer support]);
```

---

# Graphs via mermaid.js 3

```mermaid
gitGraph
  commit id: "Initialize project"
  commit id: "Make some changes"
  branch develop
  checkout develop
  commit
  commit
  checkout main
  merge develop
  commit
  commit
```

---

# Import of shared slides

{{% import path="shared-slides/devops/devops-intro.md" %}}

---

# Keystrokes

<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Del</kbd>
