[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-brightgreen.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code_of_conduct.md)

# Incentives

The goal of this project is to build a system to **incentivize**, **recognize** and **reward** contributions to **Digital Public Goods** (DPGs), defined as open source software, open data, open AI models, open standards and open content that adhere to privacy and other applicable best practices, do no harm and are of high relevance for attainment of the [UN’s 2030 Sustainable Development Goals](https://www.undp.org/content/undp/en/home/sustainable-development-goals.html) (SDGs). 

This project is one of the workstreams of the [Digital Public Goods Alliance](https://digitalpublicgoods.net/), and is led by the [UNICEF Office of Innovation](https://www.unicef.org/innovation/). One of the primary objectives of this project is to be designed, developed and implemented in an open, transparent and collaborative way involving the broad open source community. Another primary objective is to understand the relationship between various incentive models and diversity and inclusion in the open source space.

## Motivation

The aim of the [Digital Public Goods Alliance](https://digitalpublicgoods.net/) is to facilitate the discovery, development, use of, and investment in openly licensed technologies, data models, and content of high relevance for attainment of the Sustainable Development Goals (SDGs). Thus, it is our hypothesis that having an incentive system in place will advance our mission in terms of facilitation of the aforementioned *development of* and *investment in* open technologies and open content.

This project addresses the broader issue of the sustainability of open source (always a hot topic 🔥) and rewarding community contributions. While we recognize that there are several other initiatives in this space, we feel there is not a system or implementation that fits our needs that cut across projects and communities, but shares common values on doing good and improving livelihoods around the world.

## Design Considerations

In its simplest form, this system can be thought of having three components:

[![](https://mermaid.ink/svg/eyJjb2RlIjoiZ3JhcGggTFJcblx0QVtJbnB1dF0gLS0-QihQcm9jZXNzKVxuXHRCIC0tPiBDW091dHB1dF1cblx0XHRcdFx0XHQiLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlfQ)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggTFJcblx0QVtJbnB1dF0gLS0-IEIoUHJvY2Vzcylcblx0QiAtLT4gQ1tPdXRwdXRdXG5cblx0XHRcdFx0XHQiLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlfQ)

- **Input** is each of the contributions that are being incentivized.
- **Process** by which the inputs are reviewed, validated and assigned a value.
- **Output** is the value that is assigned to each input and awarded to the corresponding contributor.

### Inputs: Type of Contributions

The contributions to incentivize can take several forms. An initial classification is presented below:

[![](https://mermaid.ink/svg/eyJjb2RlIjoiZ3JhcGggTFJcblx0QShDb250cmlidXRpb25zKSAtLT4gQihOYXRpdmVseSBEaWdpdGFsKVxuXHRBIC0tPiBDKE5hdGl2ZWx5IE5vbi1EaWdpdGFsKVxuXHRCOjo6Z3JlZW4gLS0-IEQoQ29kZSlcblx0QiAtLT4gRShDb250ZW50KVxuXHRCIC0tPiBGKERhdGEpXG5cdEQ6OjpncmVlblxuXHRFOjo6Z3JlZW5cblx0Rjo6OmdyZWVuXG5cdGNsYXNzRGVmIGdyZWVuIGZpbGw6IzBGMDtcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggTFJcblx0QShDb250cmlidXRpb25zKSAtLT4gQihOYXRpdmVseSBEaWdpdGFsKVxuXHRBIC0tPiBDKE5hdGl2ZWx5IE5vbi1EaWdpdGFsKVxuXHRCOjo6Z3JlZW4gLS0-IEQoQ29kZSlcblx0QiAtLT4gRShDb250ZW50KVxuXHRCIC0tPiBGKERhdGEpXG5cdEQ6OjpncmVlblxuXHRFOjo6Z3JlZW5cblx0Rjo6OmdyZWVuXG5cdGNsYXNzRGVmIGdyZWVuIGZpbGw6IzBGMDtcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)

*Natively Digital* contributions are those that inherently exist in the digital world:
- **code** contributions in the form of commits or pull requests to an existing source code repository.
- **content** whether in the form of factual knowledge, narrative or documentation.
- **data** or information, usually numerical, that are collected through observation.

Given the *digital* nature of Digital Public Goods, we will limit the scope of the system to only handle *Natively Digital* inputs, and leaving out *Non-natively digital* inputs. Nonetheless, insofar non-natively digital inputs can be digitized by external processes, these can then be considered as valid digital inputs to this system, but such external processes are considered out of scope of this project.

### Process

The processing of inputs should be designed as flexible as possible to accommodate an ample array of possibilities. On one end of the automation spectrum, the process could be fully automated, where the contribution could be verified and validated through a well-defined set of rules and associated tests. On the other end, manual review by one or more individuals would be required to corroborate the quality, uniqueness, veracity or authorship of the contribution. The system should thus be agnostic to the actual processing of inputs and outputs, and allow for the mechanics of the actual processing to be set on a case by case basis.

### Outputs: Type of Rewards

The outputs of the system, or rewards, can be broken down as follows (not a comprehensive classification):

[![](https://mermaid.ink/svg/eyJjb2RlIjoiZ3JhcGggTFJcblx0QShSZXdhcmRzKSAtLT4gQihGaW5hbmNpYWwpXG5cdEEgLS0-IEMoTm9uLUZpbmFuY2lhbClcblx0QiAtLT4gRChNb25ldGFyeSlcblx0QiAtLT4gRShOb24tTW9uZXRhcnkpXG5cdEUgLS0-IEgoQ3JlZGl0cylcblx0RSAtLT4gSShDb3Vwb25zKVxuXHRFIC0tPiBKKFRpY2tldHMpXG5cdEUgLS0-IEsoQ2FyZWVyIE9wcHMpXG5cdEQgLS0-IEYoRmlhdClcblx0RCAtLT4gRyhDcnlwdG8pXG5cdEMgLS0-IEwoQmFkZ2VzKVxuXHRDIC0tPiBNKFB1YmxpYyBSZWNvZ25pdGlvbilcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggTFJcblx0QShSZXdhcmRzKSAtLT4gQihGaW5hbmNpYWwpXG5cdEEgLS0-IEMoTm9uLUZpbmFuY2lhbClcblx0QiAtLT4gRChNb25ldGFyeSlcblx0QiAtLT4gRShOb24tTW9uZXRhcnkpXG5cdEUgLS0-IEgoQ3JlZGl0cylcblx0RSAtLT4gSShDb3Vwb25zKVxuXHRFIC0tPiBKKFRpY2tldHMpXG5cdEUgLS0-IEsoQ2FyZWVyIE9wcHMpXG5cdEQgLS0-IEYoRmlhdClcblx0RCAtLT4gRyhDcnlwdG8pXG5cdEMgLS0-IEwoQmFkZ2VzKVxuXHRDIC0tPiBNKFB1YmxpYyBSZWNvZ25pdGlvbilcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)

Similar to the inputs described above, the scope of the rewards in this project is bounded to their existence in the digital domain. Having said this, there seems to be greater flexibility here as many of the rewards outlined above can take both a digital and a non-digital form. For example, a traditional monetary reward would be given in cash, yet this can also be coded as a digital payment. Similarly an instance of public recognition could happen in person at a ceremony, or digitized in the form of a tweet or an account of the event in a digital publication.

## Use Cases

* ![](https://img.shields.io/badge/-data-blue) [Project Connect](https://www.projectconnect.world/) maps school location and connectivity globally to inform programmes around education, health and emergencies. A current workstream of this project is to crowdsource the actual locations of the schools in selected countries by either physically visiting each school and submitting a GPS reading, and/or reviewing satellite imagery and identifying the buildings from aerial photographs. The software tools to submit this data are under active development (summer 2020) and could incorporate the necessary elements of an incentive program.

* ![](https://img.shields.io/badge/-content-orange) [Translate a Story](https://translateastory.org/) took place in the form of a sprint from April 8 – May 29, 2020 to translate children’s reading books into new languages: 1,266 volunteers joined to translate 6,614 books into 100+ languages so that children could have access to the books they need to continue to read! This was a collaboration between Norway, UNESCO, UNHCR, ADEA, The Global Book Alliance, Verizon, The Global Digital Library, Pratham Books’ StoryWeaver, The Asia Foundation’s Let’s Read initiative, African Storybook, Learning Equality and Creative Commons in response to the COVID-19 pandemic, resulting in more than 1.5 billion children and youth being left out of school. There is interest in being able to retroactively recognize each of the volunteer translators and/or incentivize further translation in any of the participating children's book repositories.

* ![](https://img.shields.io/badge/-code-brightgreen) From the list of [400+ nominees of Digital Public Goods](https://digitalpublicgoods.net), the DPG Alliance has currently four active Communities of Practice (CoP) in the areas of early grade reading, digital health, financial inclusion and climate adaptation vetting subsets of nominees in each domain. The output of these CoPs will be the selection of certain projects to endorse and support, where we would like to have a system to incentivize contributions in those selected projects.





## Resources

A list of relevant and/or similar projects, initiatives or building blocks for this project (includes a short paragraph summarizing their reason for listing):

* [Badgr](https://badgr.org/) is open source software based on open standards that allows you to work with Open Badges issued by any OB-compliant platform.
* [Open Badges](https://openbadges.org/) is the name of a group of specifications and [open technical standards](https://www.imsglobal.org/activity/digital-badges) that describes a method for packaging information about accomplishments, embedding it into portable image files as a digital badge, and establishing an infrastructure for badge validation. 
* [Fedora Badges](https://badges.fedoraproject.org/) is a fun website built to recognize contributors to the Fedora Project, help new and existing Fedora contributors find different ways to get involved, and encourage the improvement of Fedora's infrastructure.
* [Gitcoin](https://gitcoin.com) is a project that combines the #givefirst mantra of the Boulder community with capitalistic incentives to write great software. By enabling Repo Maintainers, developers, and financiers to find one another, Gitcoin grows open source software, mostly centered around the Ethereum ecosystem in the blockchain domain.
* [GitHub Sponsors](https://github.com/sponsors) allows the developer community to financially support the people and organizations who design, build, and maintain the open source projects they depend on, directly on GitHub.

## Licensing

All the content in this project is licensed under a [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/). Under the terms of this license, you are free to:

* **Share** — copy and redistribute the material in any medium or format
* **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:

* **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
* **No additional restrictions** — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

The licensor cannot revoke these freedoms as long as you follow the license terms.
