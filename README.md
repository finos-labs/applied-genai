![badge-labs](https://user-images.githubusercontent.com/327285/230928932-7c75f8ed-e57b-41db-9fb7-a292a13a1e58.svg)

# FINOS LLM Exploration

**Exploring the Potential of Large Language Models (LLMs) in Financial Services**

This repository is the home of the FINOS LLM Exploration initiative, a collaborative project focused on identifying and developing innovative use cases for LLMs in the financial services industry, while addressing the challenges of governance, security, and compliance.

The LLM Exploration Initiative is acting as a "proto-SIG" (Special Interest Group), with the goal of becoming an official FINOS SIG. We run our meetings as SIGs, and the goal is to foster the development of cross-industry collaborative code initiatives focused on non-competitive AI/LLM use cases, which can be contributed as full FINOS Projects.

## Goals

*   **Identify valuable LLM use cases:** Explore how LLMs can be applied to various tasks in finance, such as risk management, customer service, compliance, and investment analysis.
*   **Develop open-source tools and models:** Contribute to the development of open-source LLMs, tools, and frameworks that can be used by the financial services community.
*   **Promote responsible AI:** Address ethical considerations, bias mitigation, and explainability in LLM development and deployment.
*   **Foster collaboration:** Encourage collaboration between financial institutions, technology providers, and researchers to accelerate LLM adoption and innovation.

## Key Activities

*   **Use Case Exploration:** Identify and prioritize promising use cases for LLMs in finance. This includes:
    *   Financial document analysis and understanding
    *   Regulatory compliance
    *   Risk management
    *   Customer service and engagement
*   **Prototype Development:** Develop prototypes and proof-of-concepts to demonstrate the feasibility and value of LLM applications.
*   **Open Source Contributions:** Contribute to existing open-source LLM projects or create new open-source tools and models.
*   **Community Building:** Organize workshops, hackathons, and other events to foster collaboration and knowledge sharing.
*   **Research and Development:** Conduct research on LLM capabilities, limitations, and best practices for deployment in finance.

## Open Financial LLM Leaderboard (OFLL)

The OFLL project ([link to OFLL repo](https://github.com/finos-labs/Open-Financial-LLMs-Leaderboard/)) provides a specialized evaluation framework tailored specifically for the financial sector. It focuses on tasks that matter most to finance professionals, such as:

*   Information extraction from financial documents
*   Market sentiment analysis
*   Financial trend forecasting

OFLL employs a zero-shot evaluation method, testing models on unseen financial tasks without prior fine-tuning. This highlights a model's ability to generalize and perform well in financial contexts.

**Key Features of OFLL:**

*   Diverse task categories (Information Extraction, Textual Analysis, Question Answering, etc.)
*   Robust evaluation metrics (Accuracy, F1 Score, ROUGE Score, MCC)
*   Real-world financial relevance

## Common Domain Model (CDM) / EMIR-specific RAG

The EMIR-specific RAG project ([link to EMIR-specific RAG repo](https://github.com/finos-labs/emir-specific-rag)) addresses the challenges of maintaining and expanding the DRR system, which generates reports based on existing regulations (e.g., EMIR). This initiative leverages AI to reduce maintenance costs and improve scalability across different jurisdictions and regulations.

**Key Features of EMIR-specific RAG:**

*   AI-based validator for checking lineage consistency.
*   AI-based rule generator/copilot for expanding the DRR system.
*   Utilizes the Common Domain Model (CDM) for data standardization.
*   Fine-tunes FinGPT models for analyzing EMIR regulatory data.

## Maintainers

| Name              | GitHub Handle  | Organization |
| ------------------ | -------------- | ------------- |
| Peter Crosbie (Chair)     | @pjcrosbie    | Provectus     |
| Yanglet Liu       | @YangletLiu   | AI4Finance    |
| Luca Borella (AI Strategic Initiative PM)     | @lucaborella89 | FINOS         |
| Karl Moll         | @karlmoll     | FINOS         |


## Getting Involved

We encourage financial institutions, technology providers, and researchers to participate in the LLM Exploration Initiative. Here's how you can get involved:

*   **Join the FINOS AI Readiness Special Interest Group (SIG):** [Link to SIG page](https://www.finos.org/ai-readiness)
*   **Contribute to discussions and provide feedback:** Share your ideas, use cases, and challenges on this GitHub Repo as Issues or Discussions, the FINOS mailing list or [FINOS Community Slack](https://finos-lf.slack.com/messages/finos-community/).
*   **Participate in workshops and events:** Attend workshops and hackathons to collaborate with other members of the community.
*   **Contribute to open-source projects:** Contribute code, documentation, or other resources to FINOS LLM projects.
*   **Share your research and insights:** Publish your research findings, best practices, and lessons learned.

## Resources

*   **FINOS AI Readiness Governance Framework:** [[Link to framework](https://air-governance-framework.finos.org/)]


## Contact

*   **Mailing list:** [open-financial-llm+subscribe@lists.finos.org]
*   [help@finos.org]

**Join the FINOS LLM Exploration Initiative and help shape the future of AI in financial services!**

## Roadmap

Coming soon!


## License

Copyright 2024 FINOS

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
