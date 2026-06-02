# FSCI2026

## E01: AI-assisted Literature Review: Building Open, Machine-Readable Literacy for Research and Education, Featuring the Semantic Climate Encyclopedia  

### Date : 27–31 July 2026

### Class Schedule

- **7:00 AM – 9:00 AM (Pacific Time – UTC-7) / 07:30 PM - 09:30 PM (IST)**

#### Instructor

Course chair: Simon Worthington, semanticClimate, Publishing Knowledge Graph Researcher (TIB – Leibniz Information Centre for Science and Technology and University Library)
Dr. Gitanjali Yadav, BRIC-National Institute of Plant Genome Research (BRIC-NIPGR) (Co-course chair); Prof. Peter Murray-Rust, Cambridge University (Co-course chair); Dr. Renu Kumari, #semanticClimate (Instructor), Ms. Priti, BRIC-National Institute of Plant Genome Research (Instructor), Ms. Udita Agarwal, BRIC-National Institute of Plant Genome Research (Instructor)

### Abstract
The exponential growth of scholarly literature across disciplines has created major challenges for discovering, synthesizing, and reusing knowledge in a systematic and scalable manner. Traditional literature review practices and static reference resources are increasingly inadequate for handling large, heterogeneous, and rapidly evolving information landscapes. The course demonstrates how AI-assisted literature review workflows can be built, evaluated, and adapted using **open access scholarly literature** and transparent, reproducible methods.

The proposed framework leverages semantic technologies, knowledge graphs, and natural language processing to transform unstructured publications, reports, and documents into structured, interoperable, and reusable knowledge representations. AI-assisted literature review supports automated, transparent, and continuously updatable synthesis of evidence, enabling efficient navigation of large corpora and reducing manual effort. Alignment with shared vocabularies and standards ensures consistency, interoperability, and long-term reusability of the curated knowledge.

A core component of the framework is **Named Entity Recognition (NER)**, which enables the automated identification and classification of key entities—such as species name, organizations, locations, diseases, drugs from research publications. NER provides the foundation for linking entities across documents, establishing semantic relationships, and populating knowledge graphs that support advanced querying, comparison, and reasoning. 

Central to this effort is the **Semantic Climate Encyclopedia**—a dynamic, semantic reference that systematically enriches keywords with linked data from Wikimedia sources, and organizes them into a structured, searchable knowledge system. Semantic Encyclopedias can be automatically created for any corpus and are an excellent way for researchers to get an introduction to a new subject within an hour or two.

Together, the Semantic Encyclopedia, AI-assisted review, Named Entity Recognition (NER), and LLM-powered **Retrieval-Augmented Generation (RAG)** form a dynamic, extensible infrastructure that improves research efficiency, enhances knowledge accessibility, and supports data-driven learning and decision-making across disciplines. This integrated approach advances open science by bridging human-readable scholarship with machine-interpretable knowledge, enabling scalable, reusable, and interoperable research and educational ecosystems.

**Course units include:**

- Semantic corpus creation, text and data mining
- Named Entity Recognition (NER) for structured knowledge extraction
- Semantic encyclopedia for knowledge enrichment
- Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) for processing and querying scientific documents

The course will enable to build, deploy, and adapt an AI-assisted literature review workflow for semi-automated discovery, retrieval, and synthesis of peer-reviewed research articles. The instructional example uses scientific chapters and references from large open access article collections comprising millions of research articles. Participants will be introduced to core AI and machine learning concepts for literature analysis, including document retrieval, text mining, NER, and LLM-based retrieval systems, with a strong emphasis on evaluation, bias awareness, and the trustworthiness of AI-assisted outputs.

### Audience: 

Researchers Researchers, librarians, publishers

#### Level: (Beginner, but suitable for all levels)

### Requirements: 

Run Google Colab in a browser. See [Google Colab](https://colab.research.google.com/) A Google account to run CoLab Jupyter Notebooks

### Course Learning Objectives

At the end of the course, participants will be able to:

- Conduct a scoping literature review using semantic toolkits.
- Be able to carry out text and data mining and build a corpus from open access sources such as EPMC
- Obtain familiarity with using LLM RAG with PDFs and with HTML
- Use Colab Jupyter Notebooks, execute python commands, and use GitHub.
- Use the provided ‘good practice’ framework for managing LLM projects
- Knowledge Graph

### Course Topics

This course will be presented over three days for 2 hours each day and will cover these  topics:

- Topic 1 : Knowledge extraction from scientific literature corpus
- Topic 2 : Create semantic encyclopedia for knowledge enrichment
- Topic 3 : LLM and RAG for processing and querying scientific documents

### Day 1, Tuesday, July 28, 2026

#### Topic 1: Knowledge extraction from scientific literature corpus

- ##### Instructor: Dr. Renu Kumari, #semanticClimate, BRIC-NIPGR
- ##### Duration: 2 h

#### Software/Tools used: 
  
- pygetpapers [GitHub repository](https://github.com/petermr/pygetpapers)
- amilib [GitHub repository](https://github.com/petermr/amilib)
- docanalysis [GitHub repository](https://github.com/petermr/docanalysis)

### Description: 

Knowledge extraction from a scientific literature corpus involves transforming large volumes of unstructured research articles into structured, machine-readable knowledge that can be queried, analyzed, and reused. Using the #semanticClimate toolkits particularly pygetpapers, amilib, and docanalysis, this process becomes automated, scalable, and reproducible.

The workflow begins with *pygetpapers*, which retrieves relevant open-access scientific articles in bulk using keyword-based queries. These articles are downloaded in structured formats such as XML, enabling downstream computational analysis. The collected corpus is then visualized as datatable using *amilib*. The datatable is browsable and searchable. This contains information about title, author, year of publication, DOIs etc. for all the retrieved articles.

Once a clean and structured corpus is prepared, *docanalysis* is used to perform detailed text mining and natural language processing. It enables section-wise parsing, dictionary-based annotation, and named entity recognition (NER) to extract key information such as organisms, chemicals, locations, diseases, or research concepts. The tool can also generate domain-specific dictionaries and structured outputs (CSV/JSON), facilitating downstream analysis and knowledge graph construction.

Together, these tools form an integrated pipeline that supports *automated literature review*, keyword extraction, and semantic enrichment. The extracted entities and relationships can be organized into knowledge graphs or encyclopedic resources, enabling deeper insights, pattern discovery, and data-driven research across scientific domains. This approach significantly enhances the efficiency, reproducibility, and scalability of knowledge extraction from large scientific corpora.

### Day 2, Wednesday, July 29, 2026

#### Topic 2: Create semantic encyclopedia for knowledge enrichment

- ##### Instructor: Ms. Udita Agarwal, #semanticClimate, BRIC-NIPGR
- ##### Duration: 2 h
 
#### Software/Tools used:
- txt2phrases [GitHub repository](https://github.com/semanticClimate/txt2phrases)
- encyclopedia [GitHub repository](https://github.com/semanticClimate/encyclopedia)  
  
### Description:

Creating a *semantic encyclopedia* for knowledge enrichment involves organizing extracted concepts and terms from scientific literature into a structured, searchable, and interconnected resource. Using the #semanticClimate tools txt2phrases and encyclopedia, this process enables the transformation of raw textual data into a domain-specific knowledge base that supports exploration, discovery, and reuse.

The workflow involves *txt2phrases*, which analyzes cleaned text corpora to automatically identify meaningful keyphrases from the research articles. This helps in generating a rich vocabulary that reflects how knowledge is actually expressed within a specific research domain.
These extracted keyphrases are then passed to the encyclopedia tool, which structures them into an organized semantic resource. The *encyclopedia* tool allows users to create entries, define relationships between concepts, and enrich terms with contextual information such as definitions, figures from the trustable resource Wikimedia. The result is a machine-readable and human-interpretable knowledge system that can function as a lightweight domain ontology or glossary.

Together, *txt2phrases* and *encyclopedia* enable the creation of a continuously evolving semantic encyclopedia that enhances knowledge discovery, supports automated reasoning, and facilitates integration with knowledge graphs and FAIR data systems.

### Day 3, Thursday, July 30, 2026

#### Topic 3: LLM and RAG for processing and querying scientific documents

- ##### Instructor: Ms. Priti, Ms. Udita Agarwal, Dr. Renu Kumari #semanticClimate, BRIC-NIPGR
- ##### Duration: 2 h

### Description: 

This course explains how **Large Language Models (LLMs)** and **Retrieval-Augmented Generation (RAG)** can be used to work with PDF and HTML documents in a simple and efficient way. Participants will learn how to extract useful information from large documents, ask questions, and get accurate answers based on the actual content.

It also introduces how to break documents into smaller sections, store them for quick search, and connect them with LLMs to improve responses. The module focuses on practical, step-by-step workflows that help in reading, summarizing, and exploring large collections of text.

Participants will gain hands-on experience in building simple systems that can search across multiple documents and provide reliable answers. The unit also highlights ways to reduce errors, improve accuracy, and make better use of digital documents for research and learning.

#### Other Helpful Information
- [#semanticClimate tools](https://semanticclimate.github.io/p/en/tools/)
- [#semanticClimate resources](https://semanticclimate.github.io/p/en/posts/resources/)

#### LICENSE

Apache License Version 2.0, January 2004 [http://www.apache.org/licenses/](https://www.apache.org/licenses/) | License information: [LICENSE](https://github.com/semanticClimate/FSCI2026_ALR/blob/main/LICENSE)
