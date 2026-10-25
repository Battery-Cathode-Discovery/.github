# Battery Cathode Discovery

**Knowledge-driven representation and analysis of battery cathode materials for accelerated discovery.**

We investigate how battery domain knowledge can guide generative models toward viable cathode materials. Our research brings together ontologies, knowledge graphs, hyperbolic embeddings, and crystal generation, with computational screening and experimental validation as the route from generated candidates to useful materials.

## Research focus

- **Represent battery knowledge.** Organise crystallographic structures, material properties, structural families, and battery roles in an ontology and a populated knowledge graph built on EMMO and BattINFO.
- **Learn useful representations.** Encode ontology hierarchies and material instances with OnT, extending the representation to include material-specific scientific attributes.
- **Guide crystal generation.** Condition CrystaLLM through trainable attention adapters, and investigate oxidation-state conditioning for MatterGen.
- **Evaluate candidate materials.** Screen generated structures for chemical validity, stability, uniqueness, and novelty, followed by DFT and electrochemical analysis.

## Research workflow

```text
Battery ontology and knowledge graph
                 |
       OnT knowledge embeddings
                 |
  Knowledge-conditioned CrystaLLM
                 |
 Formula extraction and oxidation-state enumeration
                 |
 MatterGen structure generation with adapters
                 |
 Stability screening and candidate selection
                 |
 DFT, electrochemical analysis, and experimental validation
```

This is the overall research workflow. The knowledge-conditioned generation and oxidation-state-conditioned discovery tracks are being developed and evaluated, with their integration an ongoing objective.

## Repositories

| Repository | Focus |
| --- | --- |
| [battGPT](https://github.com/Battery-Cathode-Discovery/battGPT) | Battery materials ontology and knowledge graph, including crystallography, structural families, DFT properties, and Materials Project data ingestion. |
| [K-Ont](https://github.com/Battery-Cathode-Discovery/K-Ont) | OnT representation learning for ontology classes and knowledge graph instances, including TBox and ABox extensions. |
| [K-OnT-Research](https://github.com/Battery-Cathode-Discovery/K-OnT-Research) | Research workspace for knowledge representations and their integration with crystal generation. |
| [Novo-Oxi-Cathode-Discovery](https://github.com/Battery-Cathode-Discovery/Novo-Oxi-Cathode-Discovery) | Oxidation-state-conditioned cathode discovery, with MatterGen and downstream structure analysis. |

Start with **battGPT** for the knowledge layer, **K-Ont** and **K-OnT-Research** for representations and conditioning, and **Novo-Oxi-Cathode-Discovery** for the structure discovery track. Setup instructions, experiments, and implementation details belong to the individual repositories.

## About us

We are **Team 25**, a five-member student research team working on **Knowledge-Driven Representation and Analysis of Battery Cathode Materials for Accelerated Discovery**.

### Team members

| Name | Register number |
| --- | --- |
| Akshay KS | CB.SC.U4CSE23104 |
| R.D.Tarun | CB.SC.U4CSE23138 |
| S Ajeth | CB.SC.U4CSE23142 |
| Sarvesha NK | CB.SC.U4CSE23145 |
| Shantharam P | CB.SC.U4CSE23146 |

### Research guidance

| Role | Faculty | Designation |
| --- | --- | --- |
| Guide | Dr. Gowtham R | Associate Professor, Department of CSE |
| Co-guide | Dr. M. Ulaganathan | Chairperson, Department of Physics |

## Foundations

Our work builds on EMMO, BattINFO, OnT, CrystaLLM, MatterGen, MatterSim, pymatgen, and Materials Project. Upstream software, ontologies, models, and datasets retain their respective authorship and licences; consult each repository for attribution and usage terms.

---

*Connecting battery knowledge to material discovery.*
