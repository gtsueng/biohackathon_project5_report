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
  - name: Alasdair J. G. Gray
    affiliation: 
  - name: Alban Gaignard
    affiliation: 
  - name: Ivan Mičetić
    affiliation: 
  - nameL Leyla Jael Castro
    affiliation: 
  - name: Marcos Casado 
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
group: Project 5
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackrxiv/publication-template
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: Juty, Tsueng \emph{et al.}
---


# Introduction

Bioschemas is an opinionated view on schema.org, targeting the Life Sciences community. This entails defining key data and resource ‘properties’ within specific communities which make those data more findable on the web. Over the past year, a number of these proposed types have been directly incorporated into schema.org. In an effort to build upon this success, we sought to improve the process of proposing specifications (‘types’ and ‘profiles’) for new and existing users of bioschemas. The existing process has been deemed cumbersome, complex and convoluted. Furthermore, even when, for example, a profile is updated, there is an additional step required to put it on the bioschemas website. 

The Data Discovery Engine (DDE) Schema Playground is a tool for extending schemas from Schema.org. It provides a graphical user interface (GUI) for tailoring schemas from Schema.org to suit the needs of the user and expresses user-generated schemas in JSON-LD/JSON Schema format. The suitability of utilizing the DDE for creating and maintaining Bioschemas specifications was explored as an offshoot effort of Project 29 at the European Biohackathon 2021 during which a number of specifications were generated using scripts to convert YAML files generated from a Bioschemas Validation tool to JSON-LD/JSON Schema and tested within the DDE. Since then, ongoing effort has been made to improve the functionality of the DDE Schema Playground to support the needs of the Bioschemas community. 

The focus of Project 5 at the European Biohackathon, 2022 was to simplify the process by which researchers can create and update profiles, and to deploy those changes to the Bioschemas website. In preparation for this event, documentation in the form of 4 tutorials was prepared for creating and updating ‘types’, and for creating and updating ‘profiles’, where profiles identify key metadata properties within a particular type, and furthermore define the cardinality (number of occurrences), marginality (mandatory, recommended or optional) and value range (expected ‘values’ such as ‘text’, ‘url’, etc). In addition, several automated processes were started for updating the website and DDE Schema Registry when new or updated types and profiles are created; however, these processes were not linked nor officially adopted by the Bioschemas community. While efforts to integrate the automated processes have been ongoing, time zone differences and limitations in developer time to work on these processes have hampered the integration process.

The hackathon setting provided an ideal testing ground for the tutorials, additionally allowing us to immediately act upon feedback to improve our tutorials. While efforts were made prior to the hackathon to automate parts of the process, the hackathon served an instrumental role in providing face-to-face opportunities for integrating the individual automated parts of the process. This integration would otherwise be difficult to do, requiring extensive testing of the different parts of the process, and approval by the Bioschemas steering council for merging the integrated process into the main Bioschemas repositories.

## Objectives
1. Refine tutorials based on user feedback
2. Update a number of Bioschemas profiles using DDE and tutorials
3. Invite hackathon participants to work on new profiles and consider the use of Bioschemas for annotating their resouce
4. Engage with ELIXIR Core Data Resources (CDRs) and Deposition Databases (DDs) to push for Bioschemas adoption

# Results

## Tutorial improvements


## Bioschemas specification updates
Issues with Bioschemas specifications are tracked using GitHub’s Issue tracker including many long-standing profile update recommendations. We identified issues which could be addressed during the course of the Biohackathon and labeled them for easier follow-up. During the course of the Biohackathon, X GitHub issues were addressed during the creation of Y updated draft specification JSON-LD/JSON Schema files. Each of these files would be used to test and improve the robustness of the automated processes, in preparation for their integration. Since the Biohackathon, Z draft specification JSON-LD/JSON Schema files have been created, displayed on the Bioschemas website and registered in the DDE Schema Registry

## Automated process integration


## Community engagement and schema adoption
During the initial introduction and midweek progress reports, many groups expressed interest in working with Bioschemas to ensure FAIRness of their hackathon outputs. As seen in Table 1, we met and began discussions with members of these groups with many discussions continuing well after the Biohackathon.

Table:  Projects and discussions initiated during the Biohackathon
| Project # | Project Title | Topic | Follow-up |
| -------- | -------- | -------- | -------- |


# Discussion


# Future directions


# Code, repositories, and links
Bioschemas website repository: https://github.com/BioSchemas/bioschemas.github.io
Bioschemas draft tutorials: https://alasdairgray.github.io/bioschemas.github.io/tutorials/dde/
Bioschemas specification repository: https://github.com/BioSchemas/specifications
Bioschemas DDE integration repository: https://github.com/BioSchemas/bioschemas-dde
Bioschemas project 5 repository for Biohackathon: https://github.com/elixir-europe/biohackathon-projects-2022/tree/main/5
Bioschemas tutorial feedback: https://github.com/elixir-europe/biohackathon-projects-2022/tree/main/5/feedback

# Contributions
NJ introduced the project and furnished all required progress reports. NJ and GT wrote the BioHackRxiv report. GT, NJ, and AJGG generated updated specifications (profiles and types). GT, SF, and AJGG worked on the integration of the automated processes. NJ, LJG, AJGG, and MC provided helpful feedback on the tutorials. LJG, GT, and AJGG improved and integrated the tutorials. NJ, GT, AJGG, LJG, IM, and AG engaged in Bioschemas discussions with other projects.  

# Acknowledgments
Much of this work and key discussions were initiated at the ELIXIR Biohackathon Europe, 2022 held in November. We thank ELIXIR, the research infrastructure for life-science data, for organizing and sponsoring this event which gathered individuals from different communities of practice enabling us to make progress on several Bioschemas community efforts. We thank Egon Willighagen, Sara EL-Gebali, Núria Queralt Rosinach, Marco Brandizi, … for engaging in and/or organizing fruitful discussions. Lastly, we would especially like to thank Dana Cernoskova, Katharina Heil, and other members of the biohackathon organizing committee for their ongoing support throughout the event.


# References


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
