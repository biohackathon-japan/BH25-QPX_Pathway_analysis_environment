---
title: 'QPX: Pathway analysis environment'
title_short: 'QPX'
tags:
  - Pathway analysis
  - 
authors:
  - name: Hidemasa Bono
    orcid: 0000-0003-4413-0651
    affiliation: 1
  - name: Naoya Oec
    orcid: 0000-0002-7491-4994
    affiliation: 2
  - name: Airu Hayashi
    affiliation: 1
  - name: Chiharu Fujita
    affiliation: 1
  - name: Kotaro Uchida
    affiliation: 1
  - name: Ryo Mameda
    orcid: 0009-0007-5830-6482
    affiliation: 1
  - name: Sora Yonezawa
    orcid: 0009-0004-1874-3117
    affiliation: 1
  - name: Kazuki Nakamae
    orcid: 0000-0002-4469-664X
    affiliation: 1
  - name: Ryo Nozu
    orcid: 0000-0002-1099-3152
    affiliation: 1
affiliations:
  - name: Hiroshima University
    ror: 03t78wx29
    index: 1
  - name: Dogrun Inc.
    index: 2
date: 15 September 2025
cito-bibliography: paper.bib
event: BH25JP
biohackathon_name: "DBCLS BioHackathon 2025"
biohackathon_url:   "https://2025.biohackathon.org/"
biohackathon_location: "Mie, Japan, 2025"
group: "QPX: Pathway analysis environment"
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackathon-japan/BH25-QPX_Pathway_analysis_environment
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: First Author \emph{et al.}
---

# Abstract

Building on our work at BioHackathon 2023, where we introduced QPX and promoted pathway modeling with WikiPathways (Pico et al., 2008) using PathVisio (Kutmon et al., 2015), we now focused on creating new pathway diagrams for diverse species and registering them in WikiPathways with functional annotations. In parallel, we deployed WikiPathways node data into Elasticsearch to enable fast and flexible search and integration of pathway information.

## Author information

Information about the authors is given in the [YAML](https://en.wikipedia.org/wiki/YAML) format at the top of this template.
For authors you provide their names, their affiliations, and ideally their [ORCID](https://orcid.org/)
identifier. For affiliations, the [Research Organization Registry](https://ror.org/) (ROR) identifier can be given.
For example, this is the author information for this template:

```yaml
authors:
  - name: First Author
    affiliation: 1
  - name: Last Author
    orcid: 0000-0000-0000-0000
    affiliation: 2
affiliations:
  - name: First Affiliation
    index: 1
  - name: ELIXIR Europe
    ror: 044rwnt51
    index: 2
```

# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables

Tables can be added in the following way, though alternatives are possible:

```markdown
Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |
```

This gives:

Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

## Figures

A figure is added with:

```markdown
![Caption for BioHackrXiv logo figure](./biohackrxiv.png)
```

This gives:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

Figures can be scaled by adding the width or height to the Markdown like this:

```markdown
![Caption for BioHackrXiv logo figure](./biohackrxiv.png){ width=50px }
```

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References
