# Hi, I'm Sudarshan

AI/ML engineer in Bengaluru, India, with 3 years building LLM applications: RAG systems, evaluation harnesses and AI interview platforms for recruitment. I'm now working one layer down, on how models are served and why they slow down under load.

## Featured work

### [efficient-inference](https://github.com/sudarshan1x1/efficient-inference): LLM serving under concurrent load
An async load-testing and profiling framework for vLLM, with 8 experiments on one T4 GPU at 1 to 100 concurrent users.
- Continuous batching on an optimized engine gave **22.6x** the throughput of a naive Hugging Face server at 100 users.
- A KV cache too small for the load cost only 12% throughput but made first-token latency **6.6x** worse.
- A simple bandwidth model (4.6 ms + 4.1 ms per GB of weights per token) predicted the speed of the 4-bit quantized model.
- [Read the report (PDF)](https://github.com/sudarshan1x1/efficient-inference/blob/main/docs/efficient-inference-report.pdf)

### AI screening interview platform
Adaptive technical interviews with RAG-based retrieval, rubric-based scoring and fairness monitoring.
- Automated grading harness that scores answers against structured rubrics across multiple competencies (1-4 scale).
- Python, FastAPI, PostgreSQL + pgvector, React, WebSockets, Claude API, Sentence-Transformers.

## Currently building
- **Job recommendation system:** two-tower retrieval in PyTorch, pgvector candidate search and LightGBM re-ranking, with a Streamlit demo.

## Publication
- [Social Distancing Monitoring For Real-Time Deep Learning Framework], *[VENUE]*, Springer, [2023]. Computer vision. [doi.org/10.1007/978-981-99-7633-1_5]

## Stack
- **ML and LLMs:** PyTorch, Hugging Face Transformers, vLLM, Sentence-Transformers, QLoRA fine-tuning, RAG, hybrid vector search, cross-encoder re-ranking, RAGAS evaluation
- **Backend and data:** Python, FastAPI, PostgreSQL + pgvector, WebSockets, Docker, Azure
- **Frontend:** React

## Reach me
- LinkedIn: [https://www.linkedin.com/in/sudarshan1x1/]
- Email: [sdrxhan@gmail.com]
