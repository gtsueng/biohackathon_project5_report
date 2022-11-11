---
title: 'Enabling profile updates through the Data Discovery Engine (DDE)'
title_short: 'BioHackEU22 #5: Bioschemas profile updates'
tags:
  - metadata schema
  - FAIR data
  - documentation
authors:
  - name: Nick Juty
    orcid: 0000-0002-2036-8350
    affiliation: 1
  - name: Ginger Tsueng
    orcid: 0000-0001-9536-9115
    affiliation: 2
  - name: Sahar Frika
    affiliation: 
  - name: Alasdair Gray
    affiliation: 
  - name: Alban Gaignard
    affiliation: 
  - name: Ivan Mičetić
    affiliation: 
    
affiliations:
  - name: University of Machester
    index: 1
  - name: The Scripps Research institute
    index: 2
date: 10 November 2022
cito-bibliography: paper.bib
event: BH22EU
biohackathon_name: "BioHackathon Europe 2022"
biohackathon_url:   "https://biohackathon-europe.org/"
biohackathon_location: "Paris, France, 2022"
group: Project 26
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackrxiv/publication-template
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: Nick Juty \emph{et al.}
---


# Introduction

Bioschemas is an opinionated view on schema.org, targeting the Life Sciences community. This entails defining key data and resource ‘properties’ within specific communities which make those data more findable on the web. Over the past year, a number of these proposed types have been directly incorporated into schema.org. In an effort to build upon this success, we sought to improve the process of proposing ‘types’ and ‘profiles’ for new and existing users of bioschemas. The existing process has been deemed cumbersome, complex and convoluted. Furthermore, even when, for example, a profile is updated, there is an additional step required to put it on the bioschemas website. 

# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables and figures

Tables can be added in the following way, though alternatives are possible:

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

Table: Note that table caption is automatically numbered.

A figure is added with:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use CiTO annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate why you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* discusses
* extends
* agreesWith
* disagreesWith

# Results


# Discussion

...

## Acknowledgements

...

## References
