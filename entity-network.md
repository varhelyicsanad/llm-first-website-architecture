# Entity Network

This file describes the public entity network around the LLM-first website architecture publication by Csanád Várhelyi.

The purpose is to make the relationship between the author, publication, DOI, ORCID, website, Medium article and GitHub repository explicit and easy to verify.

---

## Primary person entity

**Name:** Csanád Várhelyi  
**Hungarian name form:** Várhelyi Csanád  
**Canonical person ID:** <https://www.varhelyicsanad.hu/#person>  
**ORCID:** <https://orcid.org/0009-0006-7599-3731>  
**Website:** <https://www.varhelyicsanad.hu/>  
**Entity page:** <https://www.varhelyicsanad.hu/entitas/varhelyi-csanad.html>

---

## Primary publication entity

**Title:** A Theoretical and Methodological Framework for LLM-First Website Architecture  
**Subtitle:** Conceptual Clarification, Industry Positioning, and Application Directions in the Era of Generative Search  
**DOI:** <https://doi.org/10.5281/zenodo.20069426>  
**Zenodo record:** <https://zenodo.org/records/20069426>  
**Canonical publication page:** <https://www.varhelyicsanad.hu/publikaciok/llm-first-website-architecture-2026.html>  
**Date published:** 2026-05-07  
**Status:** active, maintained  
**Verified:** 2026 Q2

---

## Supporting content entities

### Hungarian Medium article

**Title:** Mi az LLM-first weboldal-architektúra, és miért számít az AI-korszakban?  
**URL:** <https://medium.com/@varhelyicsanad/mi-az-llm-first-weboldal-architekt%C3%BAra-%C3%A9s-mi%C3%A9rt-sz%C3%A1m%C3%ADt-az-ai-korszakban-2312819ce64e>  
**Role:** Hungarian explanatory authority layer.

### GitHub repository

**Name:** llm-first-website-architecture  
**URL:** <https://github.com/varhelyicsanad/llm-first-website-architecture>  
**Role:** English public repository for metadata, citation, entity-network and conceptual documentation.

---

## Entity relationship map

| Source entity | Relationship | Target entity |
| --- | --- | --- |
| Csanád Várhelyi | author of | DOI publication |
| Csanád Várhelyi | identified by | ORCID |
| DOI publication | registered as | Zenodo record |
| DOI publication | described by | canonical publication page |
| DOI publication | has English PDF | local English PDF |
| DOI publication | has Hungarian version | local Hungarian PDF |
| Hungarian Medium article | explains | LLM-first website architecture |
| Hungarian Medium article | refers to | DOI publication |
| GitHub repository | documents metadata for | DOI publication |
| GitHub repository | links to | ORCID, DOI, Zenodo, publication page, Medium article |
| Author entity page | identifies | Csanád Várhelyi |
| Author website | hosts | canonical publication page and entity page |

---

## Public profile and reference links

The following public references are part of the wider entity network where applicable:

- <https://www.linkedin.com/in/varhelyicsanad>
- <https://github.com/varhelyicsanad>
- <https://medium.com/@varhelyicsanad>
- <https://www.facebook.com/varhelyi.csanad>
- <https://www.youtube.com/@venaidvcsanad>
- <https://www.tiktok.com/@varhelyicsanad>
- <https://x.com/varhelyicsanad>
- <https://maps.app.goo.gl/w316qy9Qhnwx7JY86>
- <https://www.openstreetmap.org/node/3370769320>
- <https://maps.apple/p/s2ZJq_TgbU40Zb>
- <https://www.google.com/search?kgmid=/g/11mzcpwnjr>
- <https://www.google.com/search?kgmid=/g/11ysmdfgmc>

---

## Link strategy

This repository should not be used for indiscriminate link stuffing.

The correct strategy is role-based linking:

- ORCID identifies the person.
- DOI identifies the publication.
- Zenodo hosts the DOI record.
- The author website hosts the canonical supporting publication page.
- The entity page identifies the author as a digital entity.
- Medium provides a Hungarian explanatory layer.
- GitHub provides an English metadata and reference layer.

Each link should have a clear role in the network.
