## Hi, I'm Mahaboob 👋

AI engineer in Bangalore. I work on LLM agents and reasoning, and lately I've been training small models with RL to see how far I can get on free GPUs.

Right now I'm at **Mea**, working on LLM extraction for insurance documents: prompt tuning, digging through model outputs and Lambda logs, and helping build an agent that writes prompts from entity descriptions.

### Things I've built

- **[RL for LLM Agentic Reasoning](https://github.com/Mpasha17/Reinforcement-Learning-for-LLM-Agentic-Reasoning)**: reproduced DeepSeek-R1 style reasoning with GRPO on Qwen2.5-1.5B. GSM8K went from 42% to 58% using 500 examples on two free Kaggle T4s. I also wrote the multi-turn GRPO loop from scratch, without TRL.
- **[Financial News Intelligence](https://github.com/Mpasha17/AI-Powered-Financial-News-Intelligence-System)**: a LangGraph multi-agent pipeline with RAG (ChromaDB) that skips LLM calls on duplicate news and turns articles into structured, ticker-mapped JSON.
- **[Hybrid Log Classification](https://github.com/Mpasha17/Nlp-log-classification)**: regex for easy logs, BERT embeddings for the harder ones, and an LLM only for the really messy legacy ones.
- **[Chest Cancer Classification](https://github.com/Mpasha17/End-To-End-Chest-Cancer-Classification)**: a CNN with a full MLOps setup (DVC, MLflow, Docker, GitHub Actions, AWS).

### Open source

I contribute to [Graphify](https://github.com/Graphify-Labs/graphify), a tool that turns codebases into knowledge graphs. My fixes there have shipped in releases: C# call resolution through casts, Scala context bounds, edge direction in graph diffs, and a few extractor bugs.

### What I use

Python, PyTorch, Hugging Face (TRL, PEFT, LoRA/QLoRA), LangChain/LangGraph, RAG and vector DBs, SQL, Docker, AWS and Azure.

### Reach me

[LinkedIn](https://www.linkedin.com/in/mahaboob-pasha1) · mp5272672@gmail.com · open to ML/AI engineering roles
