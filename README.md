# Production-ready RAG with Azure AI Search

*If you will be delivering this session, consult the [session-delivery-resources](./session-delivery-resources/README.md) guide for slides, demo scripts, and other resources.*

## Session Desciption

Learn how to build a production-ready Retrieval Augmented Generation (RAG) application to chat over your domain's data with Azure AI Search. Discover the benefits of hybrid search with semantic ranker to find both vector and keyword-based results amongst billions of documents. Explore different approaches to data ingestion, to extract, split, vectorize, and store your data in Azure AI Search. Consider multiple ways to evaluate your RAG app answers, to ensure high-quality responses. Finally, see how you can productionize your RAG app with efficient vector storage, private network deployment, and user authentication.

## Learning Outcomes

* Basics of vector embeddings and vector search strategies
* Azure AI Search option: full-text search, vector search, hybrid search, semantic ranker
* Data ingestion process for Azure AI Search, manual and integrated vectorization feature
* Evaluation strategies for RAG app answers: AI Studio, Promptflow-evals SDK
* Efficient vector storage with quantization
* Security best practices: private network deployment, user authentication, data access control

## Technology Used

* Azure OpenAI
* Azure AI Search
* Python

## Additional Resources and Continued Learning

Products:

| Link                             | Description        |
|:---------------------------------|:-------------------|
| [Azure AI Search](https://aka.ms/AzureAISearch) | Landing page, links to pricing and docs. |
| [Azure AI Studio](https://aka.ms/AzureAIStudio) | Portal for building and deploying AI models, fine-tuning, evaluations, etc. |

Documentation:

| Link                             | Description        |
|:---------------------------------|:-------------------|
| [Revolutionize your Enterprise Data with ChatGPT: Next-gen Apps w/ Azure OpenAI and AI Search](https://aka.ms/entgptsearchblog) | Blog post about the RAG app solution for AI Search |
| [Azure AI Search: Outperforming vector search with hybrid retrieval and ranking capabilities](https://aka.ms/ragrelevance) | Blog post with research findings on optimal search mode, chunk size, etc. |
| [Access Control in Generative AI applications with Azure Cognitive Search](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/access-control-in-generative-ai-applications-with-azure/ba-p/3956408) | Blog post with details on how data access controls can be implemented in a RAG app with Azure AI Search and Microsoft Entra |

Samples:

| Link                             | Description        |
|:---------------------------------|:-------------------|
| [RAG app with Azure AI Search](https://aka.ms/ragchat) | Solution for building a full featured RAG app with AI Search and Python on App Service |
| [AI RAG chat app evaluator](https://github.com/Azure-Samples/ai-rag-chat-evaluator) | Scripts and command-line tools for evaluating RAG chat app with promptflow-evals SDK |
| [Vector search examples](https://github.com/pamelafox/vector-search-demos) | Jupyter notebooks used throughout the presentation |

## Responsible AI 

Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI).
Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this samples above - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. We also have an interactive Content Safety Studio that allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [generation quality and risk and safety metrics](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in).

You can evaluate your AI application in your development environment using the [prompt flow SDK](https://microsoft.github.io/promptflow/index.html). Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the prompt flow sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results).

## Content Owners

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
   <tr>
    <td align="center"><a href="https://developer.microsoft.com/advocates/pamela-fox">
        <img src="https://developer.microsoft.com/en-us/advocates/media/profiles/pamela-fox.png" width="100px;" alt="Pamela Fox"/><br />
        <sub><strong>PAMELA FOX</strong></sub></a><br />
         <a href="https://github.com/pamelafox" title="GitHub profile for Pamela">📢</a> 
    </td>
</tr></table>

