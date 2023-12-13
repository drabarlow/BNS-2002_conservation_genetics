---
title       : "Conservation genetics"
subtitle    : "BNS-2002: Genes, Development, and Evolution"
author      : Dr Axel Barlow
job         : "email: a.barlow@bangor.ac.uk"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : zenburn      # {zenburn, tomorrow, solarized-dark, ...}
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
logo        : LA_Full_colour_reversed.svg
biglogo     : A1_FullColour.svg
assets      : {assets: ../../assets}
license     : by-nc-sa

---



<!-- adding bold and italic options -->
<style>
em {
  font-style: italic
}
strong {
  font-weight: bold;
}
</style>

## Phylogenetics and population genetics lectures

- Key concepts and Single locus phylogenetics
- Multi-locus phylogenetics
- Population structure
- **Conservation genetics**
  - **Theory**
  - **Methods**
  - **Discoveries**

--- 

## MEEB

**Molecular Ecology and Evolution at Bangor**

<img src="./assets/img/mb.svg" width="100%" style="display: block; margin: auto;" />

- 3rd year module "Molecular ecology and evolution"
- Dissertation and MSc projects

--- bg:white

## Revision

- lecture material
- Relevant chapters in course textbooks (phylogenetics, population structure and conservation genetics)
- Overview of some of the discussed studies (plus any others you find)
- You may need to draw simple trees:
  - by hand and upload photo
  - newick format: **((human,chimp),cat)**

<img src="assets/fig/unnamed-chunk-2-1.png" width="25%" />

--- .segue .dark 

## Conservation genetics - theory

---

## Conservation genetics

### Applied population genetics for the purpose of conservation

- Identifying management units
- Wildlife crime
- Population/ancestry assignment

### In this lecture we will look at:

- Measuring loss of genetic diversity
  - Caused by drift in small populations
- Measuring inbreeding
  - Caused by mating with close relatives

---

## Loss of genetic diversity

<iframe src = 'https://www.whfreeman.com/BrainHoney/Resource/6716/SitebuilderUploads/Hillis2e/Student%20Resources/Animated%20Tutorials/pol2e_at_1502_genetic_drift_simulation/pol2e_at_1502_genetic_drift_simulation.html' height='600px'></iframe>

---

## Loss of genetic diversity

- At small population sizes this overwhelms the rate of mutation, leading to net loss of diversity

### Inbreeding depression

- Low diversity means recessive alleles of functional genes exposed in an increasingly homozygous state
- Deleterious alleles tend to be recessive
- For some loci, heterozygotes have higher fitness, can also be disrupted

### Reduced evolutionary potential

- Selection acts on variants in the population driving adaptation
- Unpredictable because we don't know the future precisely (disease, climate change, etc)

--- &twocol

## Example: adders

*** =left

- Population in Sweden
- Isolated > 100 years
- Population decline, deformed/stillborn offspring, low genetic diversity
- inbreeding depression

*** =right

<img src="./assets/img/adder_female3.JPG" width="70%" style="display: block; margin: auto;" />

<img src="./assets/img/adder_male2.JPG" width="70%" style="display: block; margin: auto;" />

--- &twocol

## Example: adders

*** =left

<img src="./assets/img/adders.svg" width="100%" style="display: block; margin: auto;" />

*** =right

### Genetic rescue

- 20 males from other (large) populations released
- Left for 4 years
- Remaining 8 males returned to source population
- Dramatic increase in recruitment
- Increase in genetic diversity
- Reduction in stillborn offspring

---

## Adders background reading

<embed src="./assets/img/Madsen_adders.pdf" width="100%" height="500" type="application/pdf" />

--- 

## Inbreeding

- Mating between close relatives
- Not necessarily preferrential
- Becomes unavoidable in small populations
- Basically a form of drift
- Reduces diversity and evolutionary potential
- Effect on genome is more severe, and manifests in a single generation

---

## Inbreeding

<img src="./assets/img/recom_roh.svg" width="100%" style="display: block; margin: auto;" />

--- .segue .dark 

## Conservation genetics - methods

---

## Data

### Measuring diversity

- Many methods
- Heterozygosity is simple and often used
- Note across a large number of loci, heterozosity is same for all individuals in a population (HWE)

### Getting data

- Traditionally a small number of markers (e.g. microsatellites) were used
- These would be selected based on being variable in the study population(s)
- Tends to overestimate diversity (circular reasoning)
- Things get unpredictable when applied to other populations/species
- Makes comparisons between species difficult to impossible

---

## Genomics

<img src="./assets/img/aDNA_seq.svg" width="95%" style="display: block; margin: auto;" />

---

## Multispecies comparisons

<img src="./assets/img/cat_het.svg" width="95%" style="display: block; margin: auto;" />

*Barnett et al. 2020. Current Biology*

--- bg:white

## Measuring inbreeding

- In theory can be calculated from know pedigrees (e.g. "pedigree" pets)
- Genetic approaches shown to be much more accurate
- Plus knowledge of pedigree not required
- In particular, genome sequencing allows identification of **runs of homozygosity (ROH)**

<img src="assets/fig/unnamed-chunk-10-1.png" width="95%" style="display: block; margin: auto;" />

--- .segue .dark 

## Conservation genetics - discoveries

---

## IUCN designation and diversity poorly correlated

<img src="./assets/img/iucn.svg" width="87%" style="display: block; margin: auto;" />

---

## IUCN designation reading

<embed src="./assets/img/Díez-del-Molino et al. - 2018 - Quantifying Temporal Genomic Erosion in Endangered Species(2).pdf" width="100%" height="500" type="application/pdf" />

--- &twocol

## White rhinos (*Ceratotherium simum*)

*** =left

- Two subspecies: northern and southern
- ~20,000 southern white rhinos (in 2015)
- Northern white rhino functionally extinct (2 females left in 2018)

<img src="./assets/img/rhin_map.svg" width="65%" style="display: block; margin: auto;" />

*** =right

<img src="./assets/img/1920px-Ceratotherium_simum_(21922261908).jpg" width="60%" style="display: block; margin: auto;" />

<img src="./assets/img/rhin_demo.svg" width="75%" style="display: block; margin: auto;" />

---

## White rhinos (*Ceratotherium simum*)

<img src="./assets/img/rhin_res.svg" width="100%" style="display: block; margin: auto;" />

---

## White rhinos background reading

<embed src="./assets/img/Sánchez-Barreiro et al. - 2021 - Historical population declines prompted significant genomic erosion in the northern and southern white.pdf" width="100%" height="500" type="application/pdf" />

--- &twocol

## Pumas (*Puma concolor*)

*** =left

- Puma/cougar/mountain lion/panther
- Widespread across North and South America
- IUCN listed as least concern
- But some populations are small and isolated
- E.g. Florida panther listed as critically endangered
- 8 females introduced from Texas to reduce inbreeding

*** =right

<img src="./assets/img/puma_10.jpg" width="100%" style="display: block; margin: auto;" />

---

## Pumas (*Puma concolor*)

<img src="./assets/img/puma_map.svg" width="100%" style="display: block; margin: auto;" />


---

## Pumas (*Puma concolor*)

<img src="./assets/img/puma_roh.svg" width="100%" style="display: block; margin: auto;" />

---

## Pumas (*Puma concolor*)

<img src="./assets/img/puma_gen.svg" width="100%" style="display: block; margin: auto;" />

---

## Pumas background reading

<embed src="./assets/img/Saremi et al. - 2019 - Puma genomes from North and South America provide insights into the genomic consequences of inbreeding.pdf" width="100%" height="500" type="application/pdf" />

--- &twocol

## Isle Royale wolves

*** =left

- Colonised 2-3 wolves in 1940s
- Expanded to 50 individuals
- Crashed to 14 individuals in 1980s
- Notable improvement 1997 with migration of a single male, followed by second crash
- Moose increased in this period
- 2 wolves left in 2018: father-daughter and half sibs

*** =right

<img src="./assets/img/wolf-isle-royale.jpg" width="85%" style="display: block; margin: auto;" />

<img src="./assets/img/islenpmap.webp" width="85%" style="display: block; margin: auto;" />

---

## Isle Royale wolves

<img src="./assets/img/irwolf.svg" width="90%" style="display: block; margin: auto;" />

--- 

## Wolf reading

<embed src="./assets/img/sciadv.aau0757.pdf" width="100%" height="500" type="application/pdf" />

--- &twocol

## Sand lizards, UK

*** =left

- UK's rarest lizard
- Highly protected
- Historically widespread in coastal and southern areas
- Extinct in Wales by 1960's
- Multiple reintroductions
- Descendents of Merseyside dune race

*** =right

<img src="./assets/img/M_Zauneidechse1_Edit1.jpg" width="90%" style="display: block; margin: auto;" />

--- .class bg:white

## Mean heterozygosity

<img src="assets/fig/unnamed-chunk-28-1.png" width="70%" style="display: block; margin: auto;" />

--- .class bg:white

## ROHs source and introduced populations

<img src="assets/fig/unnamed-chunk-29-1.png" width="100%" style="display: block; margin: auto;" /><img src="assets/fig/unnamed-chunk-29-2.png" width="100%" style="display: block; margin: auto;" /><img src="assets/fig/unnamed-chunk-29-3.png" width="100%" style="display: block; margin: auto;" /><img src="assets/fig/unnamed-chunk-29-4.png" width="100%" style="display: block; margin: auto;" />

---

--- &twocol

## Adders, UK

*** =left

- UK redlist 
- Threatened England
- Near threatened Wales, Scotland
- Large scale declines
- Many pops < 10 adults

*** =right

<img src="./assets/img/adder_female3.JPG" width="70%" style="display: block; margin: auto;" />

<img src="./assets/img/adder_male2.JPG" width="70%" style="display: block; margin: auto;" />

---

## Adders, UK


<img src="./assets/img/adder.svg" width="100%" style="display: block; margin: auto;" />

--- &thankyou

## Thank you!
