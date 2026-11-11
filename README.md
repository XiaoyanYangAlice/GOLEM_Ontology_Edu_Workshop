# GOLEM Workshop: Fanfiction, Characters, and Knowledge Graphs

## What Happens When Fans Rewrite Characters?

[中文版](README.zh-CN.md)

How do fans reinterpret familiar characters? What changes when a character appears in a new story? How can we turn these questions into a digital humanities research project?

This introductory workshop explores fanfiction as a resource for cultural and literary research. Examples from East Asian fandoms introduce the research questions behind **GOLEM — Graphs and Ontologies for Literary Evolution Models**. We then explore how an ontology and a knowledge graph can represent works, fictional characters, their features, relationships, and narrative events.

The workshop concludes with guided practice in Google Colab. Participants will run prepared SPARQL queries, read the results, and make a small change to a query. **No prior knowledge of Python, RDF, or SPARQL is required.**


## Workshop Information

| Item | Details |
|---|---|
| Host | MA in Digital Humanities programmes, The Education University of Hong Kong |
| Instructor | Xiaoyan Yang, University of Groningen, GOLEM project |
| Mandarin session | 11 November 2026, starting at 15:30 HKT / 08:30 CET |
| English session | 19 November 2026, class scheduled for 18:30–21:30 HKT / 11:30–14:30 CET |
| Workshop duration | Approximately 100 minutes: 70 minutes of presentation and discussion, followed by 30 minutes of guided notebook practice |


## Learning Goals

By the end of the workshop, participants should be able to:

- Identify cultural and literary research questions that fanfiction data can help explore.
- Distinguish platform metadata from information about characters and narrative content.
- Explain the difference between a character in a particular work and the Character-Stoff concept connecting character instances across works.
- Recognise the basic structure of an RDF triple and a simple SPARQL query.
- Run prepared queries and explain what their results do, and do not, tell us.

## Programme

| Elapsed time | Topic | Focus |
|---|---|---|
| 00–15 min | **Fanfiction and East Asian Cultural Research** | Fandoms, AO3, fan wikis, and a case study connecting anime releases with fanfiction activity |
| 15–25 min | **GOLEM Research Questions and Data** | Story transformations, data sources, metadata, and narrative content |
| 25–40 min | **Ontology and Knowledge Graph Basics** | Data modelling, RDF triples, identifiers, properties, and research questions |
| 40–60 min | **Character Modelling Across Works** | Character instances, Character-Stoff, features, social relationships, and narrative events |
| 60–70 min | **SPARQL and Practice Preparation** | Query structure, prefixes, named graphs, and reading results |
| 70–100 min | **Guided Notebook Practice: 30 Minutes** | Running selected queries and interpreting the results |


## Workshop Materials

| Material | Purpose |
|---|---|
| [Presentation slides](materials/GOLEM_EdUHK_Workshop_slides.pptx) | English slides for the introductory presentation |
| [Tutorial notebook](materials/GOLEM_Ontology_Edu_Workshop.ipynb) | Prepared queries for metadata exploration and character analysis |
| [Ontology documentation](https://github.com/GOLEM-lab/golem-ontology/wiki) | A reference for classes, properties, prefixes, and examples |

The longer DHBenelux notebook also serves as a resource for independent exploration after class. We will use selected sections during the workshop rather than work through the entire notebook.

## Before the Workshop

Please bring a laptop with an internet connection if you would like to follow along. You may also work with a classmate.

1. Make sure you can access [Google Colab](https://colab.research.google.com/). A Google account is normally needed to run and save notebooks there.
2. Download the tutorial notebook from the materials section above.
3. In Colab, choose **File → Upload notebook** and open the downloaded `.ipynb` file.
4. Keep the ontology documentation available for consultation.

You do not need to install Python locally or complete the exercises in advance. We will run the setup cells together. Please follow the instructor's classroom notebook and endpoint settings, as the live service and teaching datasets may change.

## Guided Practice

During the practical session, the instructor will share the notebook screen and guide participants through:

| Time | Activity |
|---|---|
| 0–5 min | Open the notebook and run the setup cells |
| 5–11 min | **Query 1.1:** retrieve work titles and creators, then change `LIMIT 10` to `LIMIT 5` |
| 11–17 min | **Query 1.2:** retrieve work metrics and read the resulting table |
| 17–25 min | **Query 2.1:** explore which characters appear in which fanfiction works |
| 25–28 min | Troubleshooting and questions, or **Query 2.2** on victim roles if time permits |
| 28–30 min | Discuss possible follow-up questions and summarise the results |

The practice uses teaching data related to Greek mythology. Its results describe the queried dataset, rather than all fanfiction on AO3. A character's narrative role, an event, and a work's platform tags also represent different kinds of information.

## Reading List

### Before class: a brief orientation

No full research paper is required before the workshop. If you have time, spend around **10–15 minutes** on the following:

1. **This README:** review the programme and practical-session instructions.
2. **The ontology documentation:** skim the explanations of Work, Character, Character-Stoff, character features, and relationships. You do not need to memorise the identifiers.
3. **[GOLEM ontology portal](https://ontology.golemlab.eu/):** browse a few entries to see how the ontology documents concepts and their connections.

### Recommended reading

- **[The GOLEM Ontology for Narrative and Fiction](https://www.mdpi.com/2076-0787/14/10/193)**. *Humanities*, 2025, 14(10), 193. Read for the project's modelling approach and the relationship between literary research questions and ontology design.
- **[Character ontology manuscript](https://www.semantic-web-journal.net/system/files/swj4094.pdf)**. Read for a more detailed treatment of fictional character modelling. The linked manuscript provides further background for the workshop.

### Documentation and further exploration

- **[GOLEM ontology wiki](https://github.com/GOLEM-lab/golem-ontology/wiki):** detailed documentation of the ontology.
- **[Character module repository and case study](https://github.com/GOLEM-lab/Character_Ontology_Paper/tree/main):** supporting material for character modelling and analysis.
- **[GOLEM data portal](https://data.golemlab.eu/):** an entry point for exploring GOLEM data. Use the classroom notebook for the workshop's connection settings.
- **[Original DHBenelux 2026 workshop repository](https://github.com/XiaoyanYangAlice/DHBenelux2026_FanfictionWorkshop_GOLEM):** the earlier workshop materials on which this teaching session builds.

## After the Workshop

Further notebook sections cover publication dates, filtering by engagement metrics, tags, narrative roles, relationships, character features, and comparisons between canonical works and fanfiction.

As you explore, consider: **What would you like to compare across retellings, and which data or annotations would you need to answer that question?**

## Acknowledgements and Reuse

The workshop draws on the work of the GOLEM project, led by Federico Pianzola at the University of Groningen and supported by an ERC Starting Grant (2023–2027). The anime-data example draws on the GOLEM collaboration with the Japanese Visual Media Graph (JVMG) project.

These materials are shared for educational use. Please consult the relevant source repositories for licensing terms and attribution requirements. Screenshots and other third-party materials remain subject to their respective rights. No additional open licence is asserted by this README.

When referring to the ontology in academic work, please cite the GOLEM ontology paper and follow the citation guidance in the relevant repositories.
