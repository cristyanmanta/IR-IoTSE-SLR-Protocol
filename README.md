# IR-IoTSE-SLR-Protocol
Information Retrieval for IoT and WoT: State-of-the-Art, Taxonomy Framework and Evolutionary Directions

This repository provides a comprehensive review of search engines for IoT and WoT. It delves into the information retrieval process for these scenarios, defining research questions and selection strategies. The Systematic Literature Review (SLR) details are here: on GitHub and IEEE Data Port(TM). It includes the SLR protocol utilized in this study and the analysis data of the SLR research questions. It contains:
* Raw Data from Selected Sources (IEEE, ACM, Google Scholar, ScienceDirect, and SpringerLink) --> raw_data_source_xxx.csv


## I. Description of the SLR Methodology
It includes a description of the process for collecting primary studies and selecting works to be analyzed in this paper. The SLR is presented on information retrieval for IoT and WoT scenarios, including defining the research questions and the selection strategy. We specify the inclusion and exclusion criteria in conjunction with the quality assurance criteria. The data extraction procedure is then outlined. We have conducted the SLR following an iterative three-phase approach: review planning, execution, and reporting. 

### Map Questions
We define the following Mapping Questions (MQ), which support and guide the scope of this SLR:
- MQ1: How many studies have been published over the years?
- MQ2: Who are the most active researchers in the area?
- MQ3: How have the Information Retrieval sub-tasks on IoT and WoT evolved over the years?
- MQ4: Which challenges have been identified, and which open research questions still require new advancements?

### PICOC Criteria on the SLR

| Criteria     | Description                                                                                                                   |
|--------------|-------------------------------------------------------------------------------------------------------------------------------|
| Population   | "IoT" OR "Internet of Things" OR "WoT" OR "Web of Things"                                                                     |
| Intervention | "Information Retrieval" OR "Crawling" OR "Indexing" OR "Querying" OR "Retrieving" OR "Ranking" OR "Discovery" OR "Presenting" |
| Comparison   | Not Applicable                                                                                                                |
| Outcomes     | Paper on the state-of-the-art, a taxonomy framework and future directions for IR on IoT and WoT.                              |
| Context      | Peer-reviewed and conference publications. IR sub-tasks, methods, algorithms and techniques.                                  |

### Research Questions on the SLR

Overall RQ: What are the state-of-the-art Information Retrieval (IR) models, algorithms, and techniques used for the Internet of Things (IoT) and the Web of Things (WoT)?

| RQ    | Question                                                                                                        |
|-------|-----------------------------------------------------------------------------------------------------------------|
| RQ1   | Is/Are there any other SLR and taxonomies developed for IR-IoT and IR-WoT?. If yes, RQ1.1 to RQ1.8              |
| RQ1.1 | What is the proposed classification in Choudhury:2020?                                                          |
| RQ1.2 | What is the proposed classification in Aziez:2019?                                                              |
| RQ1.3 | What is the proposed classification in Faheem:2019?                                                             |
| RQ1.4 | What is the proposed classification in Pattar:2018?                                                             |
| RQ1.5 | What is the proposed classification in Tran:2017?                                                               |
| RQ1.6 | What is the proposed classification in Suparna De:2017?                                                         |
| RQ1.7 | What is the proposed classification in Zhou:2016?                                                               |
| RQ1.8 | What is the proposed classification in Zhang:2011?                                                              |
| RQ1.9 | What is the proposed classification in Romer:2010?                                                              |
| RQ2   | Which IR sub-tasks have been used, impacted, and proposed for the IoT and WoT paradigms?                        |
| RQ2.1 | Which is the focus of those primary studies?                                                                    |
| RQ2.2 | Are those primary studies classified as IoTSE, WoTSE, or component?                                             |
| RQ2.3 | What are the names of the proposed systems presented?                                                           |
| RQ3 | What are the basic foundations for applying IoT, WoT, and IR sub-tasks to those paradigms?                        |
| RQ3.1 | Which data types and sub-types were considered in those primary studies? Which formats are being considered?    |
| RQ3.2 | Which sensor modeling types and sub-types were considered in those primary studies?                             |
| RQ3.3 | Which are the Thing modeling types and sub-types considered in those primary studies?                           |
| RQ3.4 | Which context-awareness and Absence levels are considered in those primary studies?                             |
| RQ4 | How have the proposed solutions been modeled and/or resolved those challenges algorithmically and technically?    |

### Search String used on Engines

| Engine              | Date       | Query                                                                                                                                                                                                                                                                                  | Annex     |
|---------------------|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| ACM Digital Library | 01-07-2024 | "query": { Fulltext:("Internet of Things" OR "Web of Things" OR "IoT" OR "WoT") AND Abstract:("Information Retrieval" OR "Search Engine" OR "Crawling" OR "Service Discovery" OR "Indexing" OR "Ranking" OR "UI") } "filter": { Publication Date: (* TO 03/31/2022), ACM Content: DL } | Annex 1.1 |
| IEEE Xplore         | 01-07-2024 | (("Full Text Only":"Internet of Things" OR "Web of Things" OR "IoT" OR "WoT") AND ("Abstract":"Information Retrieval" OR "Search Engine" OR "Crawling" OR "Service Discovery" OR "Indexing" OR "Ranking" OR "UI"))                                                                     | Annex 1.2 |
| Google Scholar      | 01-07-2024 | allintitle: "Internet of Things" OR "Web of Things" OR "IoT" OR "WoT" "Information Retrieval" OR OR OR "Search Engine" OR OR OR "Crawling" OR OR OR "Service Discovery" OR OR OR "Indexing" OR OR OR "Ranking" OR OR OR "UI"                                                           | Annex 1.3 |
| ScienceDirect       | 01-07-2024 | Title, abstract, keywords: ("Information Retrieval" OR "Search Engine" OR "Crawling" OR "Indexing" OR "Ranking") AND ("Internet of Things" OR "Web of Things" OR "IoT" OR "WoT")                                                                                                       | Annex 1.4 |
| SpringerLink        | 01-07-2024 | query=IoT+AND+WoT+AND+Things+AND+Internet+AND+Web+AND+%28Information+OR+Retrieval+OR+Search+OR+Engine+OR+Crawling+OR+Indexing+OR+Ranking+OR+IoT+OR+WoT+OR+Things+OR+Internet+OR+Web                                                                                                    | Annex 1.5 |

### Inclusion (IC) and Exclusion Criteria (EC)

| IC  | Inclusion Criteria                                                                                                                     | Boolean |
|-----|------------------------------------------------------------------------------------------------------------------------------|---------|
| IC1 | Paper proposing at least one Information Retrieval mechanism (sub-task, method, technique, model, algorithm, search engine). | AND     |
| IC2 | The proposed solution is applied on IoT OR WoT OR precursor.                                                                 | AND     |
| IC3 | The paper publication period must be between 2000 and 2024.                                                                  | AND     |
| IC4 | Study must be available in full text in any predefined digital libraries.                                                    | AND     |

| EC  | Criteria                                                                                 | Boolean |
|-----|------------------------------------------------------------------------------------------|---------|
| EC1 | The study is irrelevant to IoT, WoT or any of its precursor domains and the field of IR. | OR      |
| EC2 | The study is a similar or reduced version of a complete work.                            | OR      |
| EC3 | The paper is a tertiary study or any non-scientific report.                              | OR      |
| EC4 | The study is written in other languages than English.                                    | OR      |

### Quality Assurance (QA) and Self-Assessment (SA)

| QA  | Criteria                                                                                                       | Boolean |
|-----|----------------------------------------------------------------------------------------------------------------|---------|
| QA1 | What is the fineness level in which the study's problem is defined?                                            | OR      |
| QA2 | What is the fineness level in which the study's sub-task, method, technique or algorithm is defined/described? | OR      |
| QA3 | To which extent the contributions of the study are explicit?                                                   | OR      |
| QA4 | Does the study present any future work(s)?                                                                     | OR      |

| SA  | Criteria                                              | Boolean |
|-----|-------------------------------------------------------|---------|
| SA1 | What is the reader's trust level regarding the paper? | OR      |

