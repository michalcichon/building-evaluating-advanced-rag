# Building and Evaluating Advanced RAG 📚

Retrieval Augmented Generation (RAG) is a powerful technique for fetching context to prompt LLMs, but standard implementations often suffer from hallucinations or poor retrieval. This course focuses on **Advanced RAG** pipelines and, crucially, how to **evaluate** them systematically using the "RAG Triad."

## 🔑 Key Concepts Covered

* **The RAG Triad:** Evaluating Context Relevance, Groundedness, and Answer Relevance.
* **Sentence Window Retrieval:** Enhancing context by retrieving specific sentences and expanding the window around them.
* **Auto-merging Retrieval:** Using a hierarchical tree structure to retrieve parent chunks when enough child chunks are matched.
* **Evaluation:** Using **TruLens** to programmatically benchmark RAG pipelines.

## 🛠️ Tech Stack

* **[LlamaIndex](https://www.llamaindex.ai/):** Framework for connecting custom data sources to large language models.
* **[TruLens](https://www.trulens.org/):** Software tool for evaluating and tracking the performance of LLM apps.
* **[OpenAI API](https://openai.com/):** The LLM and Embedding provider used in the notebooks.
* **Python:** Main programming language.

## 📜 Credits & Disclaimer

* **Course:** [Building and Evaluating Advanced RAG](https://learn.deeplearning.ai/courses/building-evaluating-advanced-rag)
* **Instructors:** Jerry Liu & Anupam Datta
* **Platform:** DeepLearning.AI

This repository is for educational purposes. All original course materials, slides, and proprietary content belong to DeepLearning.AI and the respective instructors.