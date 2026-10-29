# Hi, I'm Varshitha Chappidi 👋

**AI Engineer | NLP · Generative AI · RAG · LLM Evaluation**

📍 McKinney, Texas, USA · [Portfolio](https://scintillating-stroopwafel-6e3a8f.netlify.app) · [GitHub](https://github.com/VarshithaChappidi) · [Email](mailto:Chappidi1391@careerattainment.com)

AI Engineer with 3+ years of experience building NLP models, retrieval-augmented generation (RAG) applications, LLM evaluation pipelines, and tool-using AI workflows. Skilled in Python, PyTorch, Hugging Face Transformers, LangChain, and LangGraph, with a background in conversational intelligence and enterprise AI applications. Focused on retrieval quality, reproducible evaluations, reliable deployment, and translating product requirements into testable AI features.

## Technical Skills

- **Programming & Data:** Python, SQL, Pandas, NumPy, data preprocessing, dataset validation
- **Machine Learning & NLP:** PyTorch, Hugging Face Transformers, scikit-learn, BERT, transformer fine-tuning, intent classification, sentiment analysis, text classification, error analysis
- **Generative AI:** RAG, LangChain, LangGraph, Claude API, prompt and context engineering, tool calling, structured outputs, Pydantic, human-in-the-loop workflows
- **Retrieval & Evaluation:** Embeddings, hybrid search, BM25, cross-encoder reranking, PostgreSQL/pgvector, Recall@K, macro F1, groundedness evaluation, human evaluation, regression testing
- **Backend & MLOps:** FastAPI, REST APIs, Docker, AWS, MLflow, GitHub Actions, CI/CD, model versioning, application logging, latency and cost monitoring
- **Engineering Practices:** Pytest, unit and integration testing, Git, code reviews, technical documentation, requirements analysis, cross-functional collaboration

## Professional Experience

### AI Engineer — Scale AI, USA | May 2025–Present
- Developed RAG pipelines using Python, LangChain, and vector search; improved **Recall@5 from 74% to 82%** across 300 labeled queries through chunking improvements, hybrid retrieval, and reranking.
- Built reusable LLM evaluation pipelines for groundedness, instruction adherence, and tool-use correctness, combining automated checks with human-reviewed scoring rubrics.
- Implemented LangGraph workflows with validated tool calls, bounded retries, and human-review checkpoints; improved task completion from **76% to 84%** across 150 evaluation scenarios.
- Optimized evaluation execution with bounded concurrency and batched preprocessing, reducing benchmark runtime from **45 to 36 minutes** on the same workload.
- Deployed containerized inference and evaluation services using FastAPI, Docker, and AWS, integrating MLflow tracking, automated tests, and monitoring for failures, latency, and token usage.
- Partnered with product managers, data annotators, and backend engineers to define acceptance criteria, investigate failure patterns, and document model limitations and release trade-offs.

### AI Engineer Intern — Anthropic, USA | Jan 2025–Apr 2025
- Contributed Python evaluation utilities for Claude-based prototypes, adding regression cases for information extraction, instruction following, and tool-call correctness.
- Refined prompts and tool descriptions, improving prototype task pass rate from **78% to 84%** on a 200-case regression suite scored against a consistent rubric.
- Added reproducible test fixtures, structured error logs, and experiment summaries; reviewed evaluation disagreements and model failure cases with engineering mentors.

### AI Engineer — Observe.AI, India | Jun 2021–Jul 2023
- Developed NLP pipelines for intent classification, sentiment analysis, and conversation tagging from speech transcripts, including text normalization and speaker-turn segmentation.
- Fine-tuned BERT-based intent classifiers using PyTorch and Hugging Face, improving **macro F1 from 0.79 to 0.85** on 1,500 held-out utterances.
- Implemented call-quality checks for greetings, required disclosures, and script adherence, reducing median review time from **6 to 5 minutes per call** in a controlled 100-call review exercise.
- Packaged NLP models as FastAPI services using Docker, adding input validation, prediction logging, and versioned model artifacts for repeatable releases.
- Collaborated with annotation specialists, quality analysts, and product engineers to refine labeling guidelines, investigate misclassifications, and document performance across intent categories.

## Featured Projects

### [Financial RAG Evaluation & Grounded Answering Agent](https://github.com/VarshithaChappidi/financial-rag-eval)

A retrieval-augmented question-answering system over FY2025 SEC 10-K filings for five large U.S. banks. The pipeline combines BM25 and dense retrieval, reciprocal-rank fusion, company filtering, and cross-encoder reranking.

- Processed **6,549 text and table chunks** and evaluated five retrieval configurations on 34 questions.
- Reranking improved **Hit@5 from 0.82 to 0.97** and **MRR@5 from 0.66 to 0.77**.
- Built a LangGraph analyst workflow with source citations, calculator-backed arithmetic, numeric verification, investment-advice refusal, retry handling, and a human-approval checkpoint.
- Added automated tests covering calculator safety, verification, refusal, retries, and human rejection; GitHub Actions runs the test suite.

### [Text-to-SQL Fine-Tuning with QLoRA](https://github.com/VarshithaChappidi/text2sql-qlora) · [Fine-tuned model](https://huggingface.co/Varshitha2603/qwen2.5-coder-3b-text2sql-qlora)

Fine-tuned Qwen2.5-Coder-3B-Instruct on 5,000 examples using 4-bit QLoRA on a Colab T4 GPU, training approximately **0.96% of the model parameters**.

- Evaluated on 300 held-out examples; normalized SQL exact match increased from **57.0% to 77.3%**.
- Analyzed errors involving ambiguous questions, copied values, join logic, and limitations in exact-match scoring.

## Education

- **M.S., Computer and Information Science** — University of North Texas, USA | Aug 2023–May 2025
- **B.S., Computer Science** — K L University, India | Jun 2019–May 2023

## Publication

Co-authored the peer-reviewed IEEE ICAAIC 2023 paper **“Interactive Projection Technology Using Hand Gesture Recognition with Attention Mechanism and ResNet.”**

[Read the paper (DOI)](https://doi.org/10.1109/ICAAIC56838.2023.1014115)

---

*I’m interested in building useful, well-evaluated AI systems that connect machine learning research with reliable, real-world applications.*