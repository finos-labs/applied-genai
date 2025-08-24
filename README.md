![badge-labs](https://user-images.githubusercontent.com/327285/230928932-7c75f8ed-e57b-41db-9fb7-a292a13a1e58.svg)

# Applied GenAI

**Exploring the Potential of Generative AI (GenAI) in Financial Services**

This repository is the home of the Applied GenAI initiative, a collaborative project focused on identifying and developing innovative use cases for GenAI in the financial services industry, while addressing the challenges of governance, security, and compliance.

The Applied GenAI Initiative is acting as a "proto-SIG" (Special Interest Group), with the goal of becoming an official FINOS SIG. We run our meetings as SIGs, and the goal is to foster the development of cross-industry collaborative code initiatives focused on non-competitive AI/LLM use cases, which can be contributed as full FINOS Projects.

## Goals

*   **Identify valuable GenAI use cases:** Explore how GenAI can be applied to various tasks in finance, such as risk management, customer service, compliance, and investment analysis.
*   **Develop open-source tools and models:** Contribute to the development of open-source models, tools, and frameworks that can be used by the financial services community.
*   **Promote responsible AI:** Address ethical considerations, bias mitigation, and explainability in model development and deployment.
*   **Foster collaboration:** Encourage collaboration between financial institutions, technology providers, and researchers to accelerate LLM adoption and innovation.

## Key Activities

*   **Use Case Exploration:** Identify and prioritize promising use cases for GenAI in finance. This includes:
    *   Financial document analysis and understanding
    *   Regulatory compliance
    *   Risk management
    *   Customer service and engagement
*   **Prototype Development:** Develop prototypes and proof-of-concepts to demonstrate the feasibility and value of GenAI applications.
*   **Open Source Contributions:** Contribute to existing open-source Gen AI projects or create new open-source tools and models.
*   **Community Building:** Organize workshops, hackathons, and other events to foster collaboration and knowledge sharing.
*   **Research and Development:** Conduct research on model capabilities, limitations, and best practices for deployment in finance.
*   **"pied-à-terre"** for AI initiatives within FINOS Labs. See below.

## Maintainers

| Name              | GitHub Handle  | Organization |
| ------------------ | -------------- | ------------- |
| Peter Crosbie (Co-Chair)     | @pjcrosbie    | Provectus     |
| Ganesh Harke (Co-Chair)     | @harkeganesh    | Citi     |
| Yanglet Liu       | @YangletLiu   | SecureFinAI Lab at Columbia    |
| Luca Borella (AI Strategic Initiative PM)     | @lucaborella89 | FINOS         |
| Karl Moll         | @karlmoll     | FINOS         |


## Projects Supported

### Open Financial LLM Leaderboard (OFLL)

The OFLL project ([link to OFLL repo](https://github.com/finos-labs/Open-Financial-LLMs-Leaderboard/)) provides a specialized evaluation framework tailored specifically for the financial sector. It focuses on tasks that matter most to finance professionals, such as:

*   Information extraction from financial documents
*   Market sentiment analysis
*   Financial trend forecasting

OFLL employs a zero-shot evaluation method, testing models on unseen financial tasks without prior fine-tuning. This highlights a model's ability to generalize and perform well in financial contexts.

**Key Features of OFLL:**

*   Diverse task categories (Information Extraction, Textual Analysis, Question Answering, etc.)
*   Robust evaluation metrics (Accuracy, F1 Score, ROUGE Score, MCC)
*   Real-world financial relevance

### Common Domain Model (CDM) / EMIR-specific RAG

The EMIR-specific RAG project ([link to EMIR-specific RAG repo](https://github.com/finos-labs/emir-specific-rag)) addresses the challenges of maintaining and expanding the DRR system, which generates reports based on existing regulations (e.g., EMIR). This initiative leverages AI to reduce maintenance costs and improve scalability across different jurisdictions and regulations.

**Key Features of EMIR-specific RAG:**

*   AI-based validator for checking lineage consistency.
*   AI-based rule generator/copilot for expanding the DRR system.
*   Utilizes the Common Domain Model (CDM) for data standardization.
*   Fine-tunes FinGPT models for analyzing EMIR regulatory data.

### Hackathon and TechSprint Projects and Prototypes

#### TraderX TechSprint 

1) https://github.com/finos-labs/Smoothstack-Banking-App-Traderx-Integration

#### Structured Finance Hackathon 

1) https://github.com/finos-labs/CreditGoose-Finos

#### DTCC Industry Hackathon Feb 2025

1) https://github.com/finos-labs/dtcch-2025-trade-header-unicorns
2) https://github.com/finos-labs/dtcch-2025-xypher
3) https://github.com/finos-labs/dtcch-2025-broadridge-aws
4) https://github.com/finos-labs/dtcch-2025-db
5) https://github.com/finos-labs/dtcch-2025-predicta
6) https://github.com/finos-labs/dtcch-2025-bbva
7) https://github.com/finos-labs/dtcch-2025-cypher-third-eye
8) https://github.com/finos-labs/dtcch-2025-bnp-paribas-team
9) https://github.com/finos-labs/dtcch-2025-lseg-post-trade
10) https://github.com/finos-labs/dtcch-2025-tech-geniuses
11) https://github.com/finos-labs/dtcch-2025-team-cibc
12) https://github.com/finos-labs/dtcch-2025-gradient
13) https://github.com/finos-labs/dtcch-2025-quality-and-compliance-masters
14) https://github.com/finos-labs/dtcch-2025-coforge-ai-whisperers
15) https://github.com/finos-labs/dtcch-2025-que-de-jiu
16) https://github.com/finos-labs/dtcch-2025-accenture-team
17) https://github.com/finos-labs/dtcch-2025-dlt-lsm
18) https://github.com/finos-labs/dtcch-2025-ml-team
19) https://github.com/finos-labs/dtcch-2025-blue-devils
20) https://github.com/finos-labs/dtcch-2025-archie
21) https://github.com/finos-labs/dtcch-2025-abn-clearing-chicago
22) https://github.com/finos-labs/dtcch-2025-OpenAML

#### DTCC India Hackathon June 2025

1) https://github.com/finos-labs/dtcc-i-h-2025-aura
2) https://github.com/finos-labs/dtcc-i-h-2025-db-tech-titans
3) https://github.com/finos-labs/dtcc-i-h-2025-quantive
4) https://github.com/finos-labs/dtcc-i-h-2025-error-404
5) https://github.com/finos-labs/dtcc-i-h-2025-ai-sentimental
6) https://github.com/finos-labs/dtcc-i-h-2025-kl-neuro
7) https://github.com/finos-labs/dtcc-i-h-2025-thunderbolts
8) https://github.com/finos-labs/dtcc-i-h-2025-prism
9) https://github.com/finos-labs/dtcc-i-h-2025-drishtikon
10) https://github.com/finos-labs/dtcc-i-h-2025-complichange
11) https://github.com/finos-labs/dtcc-i-h-2025-technical-wizards
12) https://github.com/finos-labs/dtcc-i-h-2025-morgan-stanley-technology
13) https://github.com/finos-labs/dtcc-i-h-2025-null-pointerz
14) https://github.com/finos-labs/dtcc-i-h-2025-citihackers
15) https://github.com/finos-labs/dtcc-i-h-2025-phoenix
16) https://github.com/finos-labs/dtcc-i-h-2025-autokaarargal
17) https://github.com/finos-labs/dtcc-i-h-2025-insight-nexus
18) https://github.com/finos-labs/dtcc-i-h-2025-optimal-minds
19) https://github.com/finos-labs/dtcc-i-h-2025-ctrl-alt-geeks
20) https://github.com/finos-labs/dtcc-i-h-2025-trustkernel
21) https://github.com/finos-labs/dtcc-i-h-2025-finaireadiness ---> [UI for the FINOS AI Governance Framework](https://ai-governance-assessment-web.vercel.app/#) !
22) https://github.com/finos-labs/dtcc-i-h-2025-team-safenest
23) https://github.com/finos-labs/dtcc-i-h-2025-just-a-byte
24) https://github.com/finos-labs/dtcc-i-h-2025-fin-phenoms
25) https://github.com/finos-labs/dtcc-i-h-2025-chai
26) https://github.com/finos-labs/dtcc-i-h-2025-finsight
27) https://github.com/finos-labs/dtcc-i-h-2025-neural-ninja
28) https://github.com/finos-labs/dtcc-i-h-2025-chokers
29) https://github.com/finos-labs/dtcc-i-h-2025-disruptive-minds
30) https://github.com/finos-labs/dtcc-i-h-2025-team-fusion
31) https://github.com/finos-labs/dtcc-i-h-2025-rethink
32) https://github.com/finos-labs/dtcc-i-h-2025-invictus
33) https://github.com/finos-labs/dtcc-i-h-2025-pragnya



## Getting Involved

We encourage financial institutions, technology providers, and researchers to participate in the Applied GenAI Initiative. Here's how you can get involved:

*   **Join the FINOS AI Readiness Special Interest Group (SIG):** [Link to SIG page](https://www.finos.org/ai-readiness)
*   **Contribute to discussions and provide feedback:** Share your ideas, use cases, and challenges on this GitHub Repo as Issues or Discussions, the FINOS mailing list or [FINOS Community Slack](https://finos-lf.slack.com/messages/finos-community/).
*   **Participate in workshops and events:** Attend workshops and hackathons to collaborate with other members of the community.
*   **Contribute to open-source projects:** Contribute code, documentation, or other resources to FINOS projects.
*   **Share your research and insights:** Publish your research findings, best practices, and lessons learned.

## Resources

*   **FINOS AI Readiness Governance Framework:** [[Link to framework](https://air-governance-framework.finos.org/)]


## Contact

*   **Mailing list:** [https://lists.finos.org/g/applied-genai]
*   [help@finos.org]

**Join the FINOS Applied GenAI Initiative and help shape the future of AI in financial services!**

## Contribution Roadmap

Q4 2025: Open Financial LLM Leaderboard (OFLL) to become part of "Evaluationa and Benchmarking Suite" project (currently in formation)
Q1 2026: TBA
Q2 2026: TBA
H2 2026: TBA


## License

Copyright 2024 FINOS

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
