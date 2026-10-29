# Hi, I'm Varshitha Chappidi 👋

**AI Engineer | NLP · Generative AI · RAG · LLM Evaluation**

📍 McKinney, Texas, USA · [Portfolio](https://scintillating-stroopwafel-6e3a8f.netlify.app) · [GitHub](https://github.com/VarshithaChappidi)

I build NLP models, retrieval-augmented generation applications, LLM evaluation pipelines, and tool-using AI workflows. My work combines Python, PyTorch, Hugging Face Transformers, LangChain, and LangGraph with reproducible evaluation, retrieval quality analysis, and production-minded deployment using FastAPI, Docker, AWS, and MLflow. I enjoy turning product requirements into testable AI features, understanding failure modes, and making model limitations visible.

## Technical Skills

- **Programming & Data:** Python, SQL, Pandas, NumPy, data preprocessing, dataset validation
- **Machine Learning & NLP:** PyTorch, Hugging Face Transformers, scikit-learn, BERT, transformer fine-tuning, intent classification, sentiment analysis, text classification, error analysis
- **Generative AI:** RAG, LangChain, LangGraph, Claude API, prompt and context engineering, tool calling, structured outputs, Pydantic, human-in-the-loop workflows
- **Retrieval & Evaluation:** Embeddings, hybrid search, BM25, cross-encoder reranking, PostgreSQL/pgvector, Recall@K, macro F1, groundedness evaluation, human evaluation, regression testing
- **Backend & MLOps:** FastAPI, REST APIs, Docker, AWS, MLflow, GitHub Actions, CI/CD, model versioning, application logging, latency and cost monitoring
- **Engineering Practices:** Pytest, unit and integration testing, Git, code reviews, technical documentation, requirements analysis, cross-functional collaboration

## Featured Projects

### [Financial RAG Evaluation & Grounded Answering Agent](https://github.com/VarshithaChappidi/financial-rag-eval)

A retrieval-augmented question-answering system over FY2025 SEC 10-K filings for five large U.S. banks. The pipeline combines BM25 and dense retrieval, reciprocal-rank fusion, company filtering, and cross-encoder reranking.

- Evaluated five retrieval configurations on 34 questions; reranking improved **Hit@5 from 0.82 to 0.97** and **MRR@5 from 0.66 to 0.77**.
- Built a LangGraph analyst workflow with source citations, calculator-backed arithmetic, numeric verification, investment-advice refusal, retry handling, and a human-approval checkpoint.
- Added automated tests for calculator safety, verification, refusal, retries, and human rejection; GitHub Actions runs the test suite.

### [Text-to-SQL Fine-Tuning with QLoRA](https://github.com/VarshithaChappidi/text2sql-qlora) · [Fine-tuned model](https://huggingface.co/Varshitha2603/qwen2.5-coder-3b-text2sql-qlora)

Fine-tuned Qwen2.5-Coder-3B-Instruct on 5,000 examples using 4-bit QLoRA, training approximately **0.96% of the model parameters** on a Colab T4 GPU.

- Evaluated on 300 held-out examples; normalized SQL exact match increased from **57.0% to 77.3%**.
- Analyzed errors involving ambiguous questions, copied values, join logic, and limitations in exact-match scoring.

## Professional Experience

- **AI Engineer — Scale AI, USA** | May 2025–Present
- **AI Engineer Intern — Anthropic, USA** | Jan 2025–Apr 2025
- **AI Engineer — Observe.AI, India** | Jun 2021–Jul 2023

My work spans retrieval quality, LLM evaluation, agent reliability, transformer-based NLP, conversation intelligence, and evaluation-driven model improvement.

## Education

- **M.S., Computer and Information Science** — University of North Texas, USA | Aug 2023–May 2025
- **B.S., Computer Science** — K L University, India | Jun 2019–May 2023

## Publication

Co-authored the peer-reviewed IEEE ICAAIC 2023 paper **“Interactive Projection Technology Using Hand Gesture Recognition with Attention Mechanism and ResNet.”**

[Read the paper (DOI)](https://doi.org/10.1109/ICAAIC56838.2023.1014115)

## Connect

- **Portfolio:** [scintillating-stroopwafel-6e3a8f.netlify.app](https://scintillating-stroopwafel-6e3a8f.netlify.app)
- **GitHub:** [VarshithaChappidi](https://github.com/VarshithaChappidi)
- **Email:** [Chappidi1391@careerattainment.com](mailto:Chappidi1391@careerattainment.com)

---

*I’m interested in building useful, well-evaluated AI systems that connect machine learning research with reliable, real-world applications.*